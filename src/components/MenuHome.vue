<template>
  <div class="flex flex-wrap justify-center items-center my-5">
    <button class="group relative flex justify-center py-2 px-4 mx-2 border border-transparent text-sm font-medium rounded-md text-white bg-indigo-600 transition hover:bg-indigo-400 hover:text-indigo-900 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500" @click="AddTask">Creer une tache</button>
    <button class="group relative flex justify-center py-2 px-4 mx-2 border border-transparent text-sm font-medium rounded-md text-white transition  hover:text-pink-900 bg-pink-600 hover:bg-pink-400 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-pink-500"  @click="AddProject">Creer un projet</button>
    <p>{{message}}</p>
  </div>
</template>

<script>
export default {
  name:'MenuHome',
  data(){
return {
  message :''
}
  },
  methods: {
    AddTask(){
       
    },
    AddProject(){
      this.message= 'block'
    }
  }
}

</script>
<style scoped>
button{
  text-transform: uppercase;
  font-size: 15px;
  font-weight: bold;
}
</style>