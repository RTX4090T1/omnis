<template>

  <router-view />

</template>
<script>


export default {
  name:"App",
  created() 
  {
      this.$store.dispatch("auth/initializeAuth");
  }
}
</script>


<style>

</style>
