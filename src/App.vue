<template>
<div class="container mx-auto">
  <Navbar />
  <div>
    <div class="text-xl font-semibold text-gray-700 text-center p-2">
      This is a sample android app
    </div>
    <Butto />  
  </div>
</div>
</template>

<script>
import Butto from './components/btn.vue'
import Navbar from './components/navbar.vue'
// import Loc from './components/inapp.vue'

export default {
  name: 'App',
  data() {    
      return { location : '' }
  },
  components : {
    Butto, Navbar
  }
}
</script>

