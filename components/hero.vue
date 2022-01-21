<template>
  <div class="container">
    <header class="header">
      <navigation></navigation>
    </header>
    <div>
      <h1>hero</h1>
    </div>
  </div>
</template>

<script>
import Navigation from './navigation.vue'
export default {
name: 'HeroPage',
components: {
  Navigation
}

}
</script>
<style scolped>
.container {
  display: flex;
  /* flex-direction: column; */
  background: url(../assets/img/home/background-home-desktop.jpg);
  color: white;
  background-size: cover;
  background-repeat: no-repeat;
  max-width: 1444px;
  max-height: 980px;
}

.header {
  display: flex;
  /* position: relative; */
}
</style>
