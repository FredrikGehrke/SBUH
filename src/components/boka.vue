<template>
  <div class="container-fluid pb-5 dark-bg" id="Boka">
    <div class="container">
      <div class="text-center text-white">
        <h1 class="pt-5">Boka!</h1>
        <hr class="mb-4" />
        <h6>Skicka gärna din bokning eller meddelande till oss här</h6>
      </div>
      <div class="d-flex">
        <div class="col-md-6 mt-5 text-white">
          <i class="fas fa-map-marker-alt fa-2x mt-3 theme-color mb-2"></i>
          <p class="font-weight-bold mb-0 text-white">
            724 63 Stockholm, Sverige eller Finland
          </p>

          <i class="fas fa-phone-square-alt fa-2x theme-color mt-5"></i>
          <p class="font-weight-bold mb-0">070-2200491</p>
          <p class="font-weight-bold mb-0">073-5745403</p>
          <p class="font-weight-bold mb-0">0762-577951</p>

          <i class="fas fa-envelope fa-2x theme-color mt-5"></i>
          <p class="font-weight-bold mb-0">leif@sbuh.se</p>
        </div>
        <form @submit.prevent="sendEmail" class="col-md-6 mt-5 mx-auto text-white" >
          <div class="form-group">
            <label for="exampleFormControlInput1">Namn</label>
            <input
              class="form-control"
              type="text" 
              v-model="name"
              name="name"
              placeholder="Fullständigt namn"
            />
          </div>
          <div class="form-group">
            <label for="exampleFormControlInput1">Email address</label>
            <input
              class="form-control"
              v-model="email"
              name="email"
              placeholder="hej123@hotmail.com"
            />
          </div>
          <div class="form-group">
            <label for="exampleFormControlInput1">Telefonnummer</label>
            <input
              name="phone"
              type="text"
              v-model="phone"
              class="form-control"
              id="exampleFormControlInput1"
              placeholder="073-00 333 33"
            />
          </div>

          <div class="form-group">
            <label for="exampleFormControlTextarea1"
              >Skriv ditt meddelande</label
            >
            <textarea
            class="form-control"
            name="message"
            v-model="message"
            cols="30" rows="5"
            placeholder="Boknings önskning eller meddelande">
            ></textarea>
          </div>
          <button type="submit" class="btn theme-bg text-white mb-2">
            Skicka
          </button>
        </form>
  
        
      </div>
    </div>
  </div>
</template>

<script>
import emailjs from 'emailjs-com';
export default {
    data() {
    return {
      name: '',
      email: '',
      phone: '',
      message: ''
    }
  },
  methods: {
    sendEmail(e) {
      try {
        emailjs.sendForm('service_znhwm1q', 'template_nr78esb', e.target, 'user_6ZLxEOc8AUgESCsoGdlFa', {
          name: this.name,
          email: this.email,
          message: this.message,
          phone: this.phone
        })
        console.log('it works!!!')

      } catch (error) {
          console.log({error})
      }
      // Reset form field
      this.name = ''
      this.email = ''
      this.message = ''
      this.phone = ''
    },
  }
};
</script>

<style scoped>
hr {
  background: var(--theme-color);
  width: 5%;
  margin: auto;
  padding: 1px;
}

.btn {
  background: linear-gradient(to right, rgb(243, 141, 7), rgb(247, 91, 1));
  font-weight: 600;
  font-size: 14px;
  margin: 0;
}

</style>