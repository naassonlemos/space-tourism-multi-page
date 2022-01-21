<template>
  <nav class="nav">
    <div class="logo__container">
      <img class="logo" src="../assets/img/logo.jpg" alt="logo" />
    </div>
    <hr class="hr" />
    <div class="links__container">
      <ul class="links">
        <li class="link__1">
          <a href="../index.html">00 Home</a>
        </li>
        <li class="link__2">
          <a href="../index.html">01 Destination</a>
        </li>
        <li class="link__3">
          <a href="../index.html">02 Crew</a>
        </li>
        <li class="link__4">
          <nuxt-link to="/article" >03 Technology</nuxt-link>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'NavigationPage',
}
</script>

<style scolped>
.nav {
  display: flex;
  /* position: absolute; */
  width: 100vw;
  height: 100vh;
  left: 55px;
  top: 40px;
}

.logo__container {
  display: flex;
  /* justify-content: center;
  align-items: center;
  width: 100%;
  height: 100%; */
}

.logo {
  display: flex;
  /* background: url(../assets/img/logo.jpg); */
  width: 48px;
  height: 48px;
  border-radius: 50%;
}

.hr {
  position: absolute;
  width: 473px;
  height: 1px;
  left: 167px;
  top: 88px;

  background: #ffffff;
  mix-blend-mode: normal;
  opacity: 0.25;
}

.links__container {
  /* display: flex;
  flex-direction: row; */
  position: absolute;
  width: 830px;
  height: 96px;
  left: 610px;
  top: 40px;

  background: rgba(255, 255, 255, 0.04);
  backdrop-filter: blur(81.5485px);
}

.links {
  display: flex;
  justify-content: space-evenly;
}


</style>
