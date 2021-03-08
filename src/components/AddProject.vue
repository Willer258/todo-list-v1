<template>
  <div :style="exitApppProject" class=" text-pink-500 flex items-center justify-center p-10">
  <div class="bg-white w-1/2 p-8 rounded-xl shadow-2xl ">
    <h1 class="text-3xl uppercase font-semibold text-center mb-8">Creer une liste</h1>
    <form class="space-y-3 ">
      <div class="mb-5 ">
        <label class="mr-2 uppercase font-semibold ">Quel tache?</label>
        <input type="text" class="text-black  border transition rounded focus:shadow-xl border-gray-200 focus:bg-pink-100 focus:outline-none focus:ring-2 focus:ring-pink-500 w-full bg-transparent p-3" placeholder="Entrer un tache">
      </div> 
      <div class="mb-5">
        <label class="uppercase font-semibold">Pour quand?</label>
        <input type="date" class="text-black border transition rounded focus:shadow-xl focus:bg-pink-100 border-gray-200 focus:outline-none focus:ring-2 focus:ring-pink-500 w-full bg-transparent p-3" >
      </div>
    <div class="mb-5 text-center ">
      <button class=" uppercase  py-2 px-4 mx-2 border border-transparent text-sm font-medium rounded-md text-white bg-pink-600 transition hover:bg-pink-400 hover:text-pink-900 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-pink-500">Ajouter la tache </button>
    </div>
    </form>
  </div>
  <div class="mx-4 bg-white w-1/2 p-8 rounded-xl shadow-2xl ">
      <h1 class="text-3xl uppercase font-semibold text-center mb-8">Listes des taches</h1>

      <div class=" border-b-1 border-t-1 flex items-center ">
          <div class=" w-full rounded-full bg-pink-100 p-3">
           <label class="uppercase ml-2" >Essai</label>
          </div> 
          <div class="text-right">
             <button class="rounded-full uppercase  py-2 px-4  border border-transparent text-sm font-medium text-white bg-red-600 transition hover:bg-red-400 hover:text-red-900 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-red-500">delete</button>
          </div>
      </div>
      <div class="text-center my-5"><button class="uppercase  py-2 px-4 mx-2 border border-transparent text-sm font-medium rounded-md text-white bg-pink-600 transition hover:bg-pink-400 hover:text-pink-900 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-pink-500 ">Valider la liste</button></div>
  </div>
</div>
</template>

<script>

export default {
name:'AddProject',  
  data() {
    return {
      exitAppProject:{
        display:'none'
      }
    }
  },
  props: {
      exitApppProject:{
        color:'blue'
      }
  },
}

</script>
<style scoped>

</style>