<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div class="sea">
      <!-- <img src="../assets/sea.png" alt="sea_picture" > -->
  </div>
</template>

<style scoped>


.sea {
  display: flex;
  flex-direction: flex-start;
  position: absolute;
}



</style>
