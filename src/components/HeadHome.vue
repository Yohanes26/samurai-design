<template>
  <div class="headHome">
    <div class="menu">
        <ul class="ulMenu">
            <li class="myAccounts">
              <font-awesome-icon class="bell" icon="user-alt"/>
                My Accounts
            </li>
            <li class="store">
                <font-awesome-icon class="bell" icon="store"/>
                Store
            </li>
        </ul>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.headHome {
  width: 100vw;
  height: 100vh;
    background-image: url("../assets/ux-designer.jpg");
  background-repeat: no-repeat;
  background-size: 100% 100%;
}

.menu {
    position: absolute;
    z-index: 500;
    width: 100%;
}

.ulMenu {
    list-style: none;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    float:right;

    li {
      margin-right: 20px;
      box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.8);
      border-radius: 5px;
      padding: 10px 20px;
      cursor: pointer;
      transition: 0.5s;
    }

    li:hover {
      box-shadow: 0px 0px 8px 2px rgba(62, 67, 212, 0.8);
      .bell {
        animation: tremeTreme 0.2s normal 3 linear ;
        transition: 2s;
      }
    }
}

@keyframes tremeTreme {
  0% {
    transform: translateX(0px);
  }
  50% {
    transform: translateX(3px);
  }
  100% {
    transform: translateX(-3px);
  }
}

@media only screen and (max-width: 700px) {
  .background {
    width: 300%;
    margin-left: -100%;
  }
}
</style>
