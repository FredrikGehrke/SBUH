<template>
  <div class="container-fluid pb-5 dark-bg" id="Boka">
    <div class="container">
      <div class="text-center text-white">
        <p class="pt-5 wow heartBeat h1 font-weight-bold" data-wow-duration="2s">Boka!</p>
        <hr class="mb-4" />
        <h6>Skicka gärna din bokning eller meddelande till oss här</h6>
      </div>
      <div class="d-block d-md-flex">
        <div class="col-md-6 mt-5 text-white">
          <i class="fas fa-map-marker-alt fa-2x mt-3 theme-color mb-2"></i>
          <p class="font-weight-bold mb-0 text-white">
            724 63 Stockholm, Sverige eller Finland
          </p>
          <i class="fas fa-phone-square-alt fa-2x theme-color mt-5 mb-2"></i>
          <ul class="list-unstyled text-white font-weight-bold">
            <li>
                <a href="tel:0702200491">070-2200491</a>
            </li>
            <li>
                <a href="tel:0735745403">073-5745403</a>
            </li>
            <li>
                <a href="tel:0762577951">0762-577951</a>
            </li>
          </ul>
          <a href="mailto:leif@sbuh.se"><i class="fas fa-envelope fa-2x theme-color mt-5"></i></a>
          <ul class="list-unstyled font-weight-bold">
            <li>
                <a href="mailto:leif@sbuh.se">leif@sbuh.se</a>
            </li>
          </ul>
        </div>
        <form @submit.prevent="sendEmail" class="col-md-6 mt-5 mx-auto text-white" >
          <div class="form-group">
            <label for="exampleFormControlInput1">Namn<span class="theme-color">*</span></label>
            <input
              class="form-control"
              type="text" 
              v-model="name"
              name="name"
              id="invalidName" required
            />
            <small class="invalid-feedback">
              Skriv ett korrekt namn
            </small>
          </div>
          <div class="form-group">
            <label for="exampleFormControlInput1">Email address<span class="theme-color">*</span></label>
            <input
              class="form-control"
              v-model="email"
              name="email" 
              id="invalidEmail" required
            />
            <small class="invalid-feedback">
              Skriv en korrekt email address.
            </small>
          </div>
          <div class="form-group">
            <label for="exampleFormControlInput1">Telefonnummer</label>
            <input
              name="phone"
              type="text"
              v-model="phone"
              class="form-control"
              id="invalidPhone"
            />
            <small class="invalid-feedback">
              Skriv ett korrekt telefonnummer
            </small>
          </div>
          <div class="form-group">
            <label for="exampleFormControlTextarea1">Skriv ditt meddelande<span class="theme-color">*</span></label>
            <textarea
            class="form-control"
            name="message"
            v-model="message"
            cols="30" rows="8" required
            ></textarea>
          </div>
          <div class="row">
            <button type="submit" class="btn theme-bg text-white ml-3">
              Skicka
            </button>
            <div class="col-12 col-md-6 theme-color mt-3 mt-sm-0 d-none sentEmail" id="sentText">
              Ditt mail har skickats!
            </div>
          </div>
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
      message: '',
      ValidEmail: false,
      ValidName: false,
      ValidPhone: false,
    }
  },
  methods: {
    sendEmail(e) {
      let nameElement = document.getElementById("invalidName")
      let emailElement = document.getElementById("invalidEmail")
      let phoneElement = document.getElementById("invalidPhone")
      let sentTextElement = document.getElementById("sentText")

      if(this.email.match(/^[a-zA-Z0-9.!#$%&'*+/=?^_`{|}~-]+@[a-zA-Z0-9-]+(?:\.[a-zA-Z0-9-]+)*$/)) { 
        this.ValidEmail = true 
        emailElement.classList.remove("is-invalid")
      } else {
        emailElement.classList.add("is-invalid")
      }

      if(this.name.length > 1 && this.name.match(/^[a-zA-Z-,]+(\s{0,1}[a-zA-Z-, ])*$/)) { 
        this.ValidName = true 
        nameElement.classList.remove("is-invalid")
      } else {
        nameElement.classList.add("is-invalid")
      }

      if(this.phone.match(/^[0-9]+$/)) { 
        this.ValidPhone = true 
        phoneElement.classList.remove("is-invalid")
      } else {
        phoneElement.classList.add("is-invalid")
      }

      if(this.ValidName === true && this.ValidEmail === true && this.ValidPhone === true) {
        try {
          emailjs.sendForm('service_znhwm1q', 'template_nr78esb', e.target, 'user_6ZLxEOc8AUgESCsoGdlFa', {
            name: this.name,
            email: this.email,
            message: this.message,
            phone: this.phone
          })

          sentTextElement.classList.add("d-block")
          setTimeout(function(){
            sentTextElement.classList.remove('d-block');
          }, 10000)

        } catch (error) {
            console.log({error})
        }

        this.name = ''
        this.email = ''
        this.message = ''
        this.phone = ''
      } 
    },
  }
};
</script>

<style scoped>

.sentEmail {
  align-self: center;
}

.form-control:focus {
  border-color:rgb(243, 141, 7);
  box-shadow: 0px 1px 1px rgba(243, 141, 7) inset, 0px 0px 8px rgba(243, 141, 7);
}

textarea {
  resize: none;
}

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

a {
    text-decoration: none;
    color: white;
} a:hover {
  color: var(--theme-color)
}
</style>