<template>
  <div class="container">
    <Header/>
    <Start/>
    <With/>
    <Easy/>
    <Simple/>
    <Personal/>
    <Ready/>
    <Footer/>
  </div>
</template>




<script>
import Header from './layout/header/header.vue'
import Start from './components/start/start.vue'
import With from './components/with/with.vue'
import Easy from './components/easy/easy.vue'
import Simple from './components/simple/simple.vue'
import Personal from './components/personal/personal.vue'
import Ready from './components/ready/ready.vue'
import Footer from './layout/footer/footer.vue'


export default {
  components : {
    Header,
    Start,
    With,
    Easy,
    Simple,
    Personal,
    Ready,
    Footer
  }
}
</script>




<style scoped>
  
</style>