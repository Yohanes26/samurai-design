<template>
  <div class="headHome">
    <img
      width="100%"
      height="100%"
      src="../assets/ux-designer.jpg"
      alt="background-ux"
      class="background"
    >
  </div>
</template>

<style lang="scss" scoped>
.headHome {
  width: 100vw;
  height: 100vh;
}

@media only screen and (max-width: 700px) {
  .background {
    width: 300%;
    margin-left: -100%;
  }
}
</style>
