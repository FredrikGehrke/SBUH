<template>
  <div>
    <navbar />
    <firstSection />
    <secondSection />
    <priceList />
    <myFooter />
  </div>
</template>

<script>
import navbar from './components/navbar'
import firstSection from './components/firstSection'
import secondSection from './components/secondSection'
import myFooter from './components/footer'
import priceList from './components/pricelist'


export default {
  name: 'App',
  components: {
    navbar,
    firstSection,
    secondSection,
    myFooter,
    priceList
    
  }
}
</script>

<style>

* {
  margin: 0;
  padding: 0;
  box-sizing: 0;
  letter-spacing: 1.5px;
  font-family: 'Open Sans', sans-serif;
}

:root {
  --theme-color: #f38d07;
}

.theme-bg {
  background-color: var(--theme-color)
}

.theme-color {
  color: var(--theme-color)
}

</style>
