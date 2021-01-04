<template>
  <div>
    <navbar />
    <firstSection />
    <secondSection />
  </div>
</template>

<script>
import navbar from './components/navbar'
import firstSection from './components/firstSection'
import secondSection from './components/secondSection'

export default {
  name: 'App',
  components: {
    navbar,
    firstSection,
    secondSection
  }
}
</script>

<style>

* {
  margin: 0;
  padding: 0;
  box-sizing: 0;

}

</style>
