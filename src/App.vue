<script></script>

<template>
  <header class="top-bar spread">
    <nav class="top-bar-nav">
      <router-link to="/" class="top-bar-link">
        <span>WeatherPoint</span>
      </router-link>
      <router-link to="/pins" class="top-bar-link">
        <span>Pins</span>
      </router-link>
      <router-link to="/about" class="top-bar-link">
        <span>About</span>
      </router-link>
    </nav>
  </header>
  <router-view></router-view>
</template>

<style scoped></style>
