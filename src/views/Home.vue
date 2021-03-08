<template>
  <div class="home">
    <MenuHome />
    <div>
      <AddTask/>
      <AddProject/>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import MenuHome from '@/components/MenuHome.vue'
import AddTask from '@/components/AddTask.vue'
import AddProject from '@/components/AddProject.vue'
export default {
  name: 'Home',
 components:{
   MenuHome,AddTask,AddProject
 },

}
</script>
