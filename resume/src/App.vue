<script setup>
import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <div class="sidebar">
      <img alt="profile" class="logo" src="./assets/profile.png" width="135" height="170" /> 
      <img src="./assets/sea.png" alt="sea_picture" width="190" height="765">
    </div>

    <div>
      <HelloWorld/>
    </div>
  </header>

  <!-- <main>
    <TheWelcome />
  </main> -->
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
display: flex;
flex-direction: flex-start;
  position: absolute;
  background: #fff;
  padding: 10px;
}

.sea {
  position: absolute;
}

.sidebar {
  display: flex;
  flex-direction: columns;
  border: 10px;

}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }


  header .wrapper {
    display: flex;
    flex-direction: columns;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
