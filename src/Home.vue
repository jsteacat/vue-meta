<template>
  <div class="home-view">
    <h1>Home View</h1>
    <ul>
      <li><router-link to="/">Home</router-link></li>
      <li><router-link to="/about">About</router-link></li>
      <li><router-link to="/about/nested">Nested Route</router-link></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'home-view',
}
</script>