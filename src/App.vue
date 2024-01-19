<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header> 
   <div class="container m-auto justify-between">
      <nav>
       

          <ul class="text-green-800 justify-items-start">
            <li>
              <RouterLink to="/">Home</RouterLink>
            </li>
            <li>
              <RouterLink to="/about">About</RouterLink> 
            </li>
            <li>
              <RouterLink to="/contact">Contact</RouterLink>
            </li>
            <li>
              <RouterLink to="/login">Login</RouterLink>
            </li>
            <li>
              <RouterLink to="/logout">Logout Profile</RouterLink>
            </li>
          </ul>

      </nav>
   </div>  
  </header>

   <div class="container m-auto text-center">
        <RouterView />
   </div>

</template>
<style scoped>

</style>
