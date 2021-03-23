<template>
 
    <div class="card container mt-3">
    <div class="card-body">
       <Header msg="Task Manager"/>
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue'

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style>
  body {
    font-family: monospace;
  }
</style>
