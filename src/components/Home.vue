<template>
  <div>
    <h1 class="title">All Plug And Play</h1>
    <div class="boxCards">
      <div class="card">
        <router-link class="routerLink" to="/dashboard">
          <div class="subCard">Imagem</div>
          <h1 class="routerLink">DashBoard</h1>
          <i>Free</i>
        </router-link>
      </div>
      <div class="card">
        <router-link class="routerLink" to="/components">
          <h1 class="routerLink">Components</h1>
        </router-link>
      </div>
      <div class="card">
        <router-link class="routerLink" to="/vue-dashboard">
          <h1 class="routerLink">Vue.JS DashBoard</h1>
        </router-link>
      </div>
      <div class="card">
        <router-link class="routerLink" to="/vue-components">
          <h1 class="routerLink">VUE.JS Components</h1>
        </router-link>
      </div>
      <div class="card">
        <router-link class="routerLink" to="/angular-dashboard">
          <h1 class="routerLink">Angular7 DashBoard</h1>
        </router-link>
      </div>
      <div class="card">
        <router-link class="routerLink" to="/angular-components">
          <h1 class="routerLink">Angular7 Components</h1>
        </router-link>
      </div>
      <div class="card">
        <router-link class="routerLink" to="/react-dashboard">
          <h1 class="routerLink">React DashBoard</h1>
        </router-link>
      </div>
      <div class="card">
        <router-link class="routerLink" to="/react-components">
          <h1 class="routerLink">React Components</h1>
        </router-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.boxCards {
  height: 100%;
  width: 100%;
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
}
.card {
  width: 40%;
  height: 500px;
  border-color: #f6f6f6;
  margin-top: 40px;
  border-radius: 6px;
  color: #333;
  background: #fff;
  box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.14), 0 3px 1px -2px rgba(0, 0, 0, 0.2),
    0 1px 5px 0 rgba(0, 0, 0, 0.12);
  position: relative;
  display: flex;
  flex-direction: column;
  min-width: 0;
  word-wrap: break-word;
  min-height: 1px;
  padding-right: 15px;
  padding-left: 15px;
}

.subCard:hover {
  -webkit-transform: translate3d(0, -20px, 0);
  transform: translate3d(0, -20px, 0);
}

.routerLink {
  text-decoration: none;
}

.title {
    width: fit-content;
    margin: 0 auto;
    margin-top: 40px;
}
</style>

