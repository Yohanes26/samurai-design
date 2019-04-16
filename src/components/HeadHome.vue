<template>
  <div class="headHome">
    <div class="menu">
        <ul class="ulMenu">
            <li class="myAccounts">
                My Accounts
            </li>
            <li class="store">
                Store
            </li>
        </ul>
    </div>
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

.menu {
    position: absolute;
    z-index: 500;
}

.ulMenu {
    list-style: none;
}

@media only screen and (max-width: 700px) {
  .background {
    width: 300%;
    margin-left: -100%;
  }
}
</style>
