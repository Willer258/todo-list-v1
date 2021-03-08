<template>
<div class=" text-indigo-500 flex items-center justify-center px-10">
  <div class="bg-white p-8 w-full rounded-xl shadow-2xl w-1/3">
    <h1 class="text-3xl uppercase font-semibold text-center mb-8">Creer une nouvelle tache</h1>
    <form class="space-y-3 ">
      <div class="mb-5 ">
        <label class="mr-2 block uppercase font-semibold ">Quel tache?</label>
        <input type="text" class="text-black  border transition rounded focus:shadow-xl border-gray-200 focus:bg-indigo-100 focus:outline-none focus:ring-2 focus:ring-indigo-500 w-full bg-transparent p-3" placeholder="Entrer un tache">
      </div> 
      <div class="mb-5">
        <label class="uppercase font-semibold">Pour quand ?</label>
        <input type="date" class="text-black border transition rounded focus:shadow-xl focus:bg-indigo-100 border-gray-200 focus:outline-none focus:ring-2 focus:ring-indigo-500 w-full bg-transparent p-3" >
      </div>
    <div class="mb-5 text-center ">
      <button class=" uppercase font-semibold py-2 px-4 mx-2 border border-transparent text-sm font-medium rounded-md text-white bg-indigo-600 transition hover:bg-indigo-400 hover:text-indigo-900 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500">Ajouter la tache </button>
    </div>
    </form>
  </div>
</div>

</template>

<script>
export default {
name:'AddTask',  
}
</script>
<style scoped>

</style>