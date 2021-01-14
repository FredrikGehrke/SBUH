<template>
  <div>
    <navbar />
    <landingHeader />
    <foretaget />
    <prisLista />
    <boka />
    <foton />
    <kunder />
    <myFooter />
  
  </div>
</template>

<script>
import navbar from './components/navbar'
import landingHeader from './components/landingHeader'
import foretaget from './components/foretaget'
import myFooter from './components/footer'
import prisLista from './components/prisLista'
import kunder from './components/kunder'
import foton from './components/foton'
import boka from './components/boka'

export default {
  name: 'App',
  components: {
    navbar,
    landingHeader,
    foretaget,
    myFooter,
    prisLista,
    kunder,
    foton,
    boka
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

html {
  scroll-behavior: smooth;
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

.bg-color {
  background-color: rgba(230, 228, 228, 0.192);
}

.SBUH {
  font-family: 'Roboto Slab', serif;
  font-weight: 700;
}

.title-color {
  color: rgb(32, 32, 32);
}

.btn:hover {
  box-shadow: 0px 0px 20px 2px rgb(243, 141, 7);  
  color: white;
}

h1, h2, h3, h4 , h5 {
  font-family: 'Roboto Slab', serif;
  font-weight: bold;
}


.dark-bg {
  background: linear-gradient(to bottom, rgb(32, 32, 32), rgb(19, 19, 19));
  box-shadow: 0px 5px 20px 10px rgba(0, 0, 0, 0.219);  
}

.lighter-bg {
  background-color: rgba(230, 228, 228, 0.192);
}

::-webkit-scrollbar {
    width: 8px;
}

::-webkit-scrollbar-track {
    background: #1B242F; 
    box-shadow: inset 0 0 6px rgb(7, 6, 6); 
}

::-webkit-scrollbar-thumb {
    background: var(--theme-color); 
    -webkit-border-radius: 50px;
    border-radius: 50px;
}

::-webkit-scrollbar-thumb:hover{
    background: #ff6701; 
}


</style>
