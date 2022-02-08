<template>
  <div class="app" id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> ||
      <router-link to="/addcard">Add Card</router-link>
    </div>
    <router-view/>
  </div>
</template>
<script>
export default {
}
</script>

<style lang="scss">
.app{
  display: grid;
  justify-content: center;
}
</style>
