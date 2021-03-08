<template>
  <div id="nav">
    <Header />
  </div>
  <div class="bg-white py-5">
    
  </div>
  <router-view/>
</template>

<script>
import Header from '@/components/Header.vue'
export default {
  name:'App',
  components: {
    Header,
  },
}
</script>
<style>

</style>
