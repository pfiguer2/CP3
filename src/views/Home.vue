<template>
<div class="home">
  <img alt="Recipe Book Logo" src="../assets/logo.png" width=25%>
  <HomePage msg="Welcome to My Recipe Book" />
</div>
</template>

<script>
// @ is an alias to /src
import HomePage from '@/components/HomePage.vue'

export default {
  name: 'Home',
  components: {
    HomePage
  }
}
</script>
