<template>
  <header>
    <nav>
      <ul class="flex flex-row bg-red-400 h-12 justify-center">
        <li class="p-4 font-semibold">
          <nuxt-link exact to="/">Home</nuxt-link>
        </li>
        <li class="p-4 font-semibold">
          <nuxt-link to="/applications">Applications</nuxt-link>
        </li>
        <li class="p-4 font-semibold">
          <nuxt-link to="/issues">Issues</nuxt-link>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
  export default {
    
  }
</script>

<style scoped>
.nav-contents {
  display: flex;
  flex-direction: row;
  justify-content: center;

}

h4 {
  margin: 5px;
}
</style>