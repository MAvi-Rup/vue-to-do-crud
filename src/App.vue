<script setup>
import { RouterView } from 'vue-router'
import TodoHeader from './components/TodoHeader.vue';

</script>

<template>
  <TodoHeader />


  <RouterView />
</template>
<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,500;0,600;1,300;1,400;1,500&family=Rubik:wght@300;400;500;700&family=Varela+Round&display=swap');
 

* {
  font-family: "Rubik", sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  max-width: 1100px;
  margin: 0 auto;
}
  
</style>