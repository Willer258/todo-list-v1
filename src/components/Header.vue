<template>
  <header class="lg:px-16 px-6 bg-purple-600 flex flex-wrap shadow items-center lg:py-0 py-2">
    <div class="flex-1 flex justify-between items-center">
      <label for="menu-toggle" class="cursor-pointer title">Todo-List</label>
      <ul class="flex-1 flex justify-end items-center">
        <li class="transition hover:bg-white rounded-md hover:text-purple-600"><router-link to="/">Accueil</router-link></li>
        <li class="transition hover:bg-white rounded-md hover:text-purple-600"><router-link to="/Tasklist">Listes des taches</router-link></li>
        <li class="transition duration-500 hover:bg-white rounded-md hover:text-purple-600"><router-link to="/Project">Projets</router-link></li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {
  name:'Header',
  content:
  {

  }
}
</script>

<style scoped>

header{
  color: aliceblue;
}
.title{
  font-size: 35px;
}
a{
  font-size: 15px;
  text-transform: uppercase;
  font-weight: bold;
  }
li{
  padding:10px ;
  margin: 10px;
}
</style>