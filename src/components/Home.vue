<template>
  <div>
    <head-home></head-home>
    <h1 class="title">All Designs Plug And Play</h1>
    <div class="boxCards">
      <div class="card">
        <router-link class="routerLink" to="/dashboard">
          <div class="boxSubCard">
            <div class="subCard">
              <img
                class="imageStyle"
                src="../assets/example.jpg"
                alt="exemplo"
                width="100%"
                height="100%"
              >
            </div>
          </div>
          <div class="boxSubTitles">
            <h1 class="titleCard">DashBoard</h1>
            <div class="boxBadges">
              <i class="eachBadges free">Free</i>
              <i class="eachBadges paid">Paid</i>
            </div>
          </div>
        </router-link>
      </div>
      <div class="card">
        <router-link class="routerLink" to="/components">
          <div class="boxSubCard">
            <div class="subCard">
              <img
                class="imageStyle"
                src="../assets/example.jpg"
                alt="exemplo"
                width="100%"
                height="100%"
              >
            </div>
          </div>
          <div class="boxSubTitles">
            <h1 class="titleCard">Components</h1>
            <div class="boxBadges">
              <i class="eachBadges free">Free</i>
              <i class="eachBadges paid">Paid</i>
            </div>
          </div>
        </router-link>
      </div>
      <div class="card">
        <router-link class="routerLink" to="/vue-dashboard">
          <div class="boxSubCard">
            <div class="subCard">
              <img
                class="imageStyle"
                src="../assets/example.jpg"
                alt="exemplo"
                width="100%"
                height="100%"
              >
            </div>
          </div>
          <div class="boxSubTitles">
            <h1 class="titleCard">Vue.JS DashBoard</h1>
            <div class="boxBadges">
              <i class="eachBadges free">Free</i>
              <i class="eachBadges paid">Paid</i>
            </div>
          </div>
        </router-link>
      </div>
      <div class="card">
        <router-link class="routerLink" to="/vue-components">
          <div class="boxSubCard">
            <div class="subCard">
              <img
                class="imageStyle"
                src="../assets/example.jpg"
                alt="exemplo"
                width="100%"
                height="100%"
              >
            </div>
          </div>
          <div class="boxSubTitles">
            <h1 class="titleCard">Vue.JS Components</h1>
            <div class="boxBadges">
              <i class="eachBadges free">Free</i>
              <i class="eachBadges paid">Paid</i>
            </div>
          </div>
        </router-link>
      </div>
      <div class="card">
        <router-link class="routerLink" to="/angular-dashboard">
          <div class="boxSubCard">
            <div class="subCard">
              <img
                class="imageStyle"
                src="../assets/example.jpg"
                alt="exemplo"
                width="100%"
                height="100%"
              >
            </div>
          </div>
          <div class="boxSubTitles">
            <h1 class="titleCard">Angular 7 DashBoard</h1>
            <div class="boxBadges">
              <i class="eachBadges free">Free</i>
              <i class="eachBadges paid">Paid</i>
            </div>
          </div>
        </router-link>
      </div>
      <div class="card">
        <router-link class="routerLink" to="/angular-components">
          <div class="boxSubCard">
            <div class="subCard">
              <img
                class="imageStyle"
                src="../assets/example.jpg"
                alt="exemplo"
                width="100%"
                height="100%"
              >
            </div>
          </div>
          <div class="boxSubTitles">
            <h1 class="titleCard">Angular 7 Components</h1>
            <div class="boxBadges">
              <i class="eachBadges free">Free</i>
              <i class="eachBadges paid">Paid</i>
            </div>
          </div>
        </router-link>
      </div>
      <div class="card">
        <router-link class="routerLink" to="/react-dashboard">
          <div class="boxSubCard">
            <div class="subCard">
              <img
                class="imageStyle"
                src="../assets/example.jpg"
                alt="exemplo"
                width="100%"
                height="100%"
              >
            </div>
          </div>
          <div class="boxSubTitles">
            <h1 class="titleCard">React DashBoard</h1>
            <div class="boxBadges">
              <i class="eachBadges free">Free</i>
              <i class="eachBadges paid">Paid</i>
            </div>
          </div>
        </router-link>
      </div>
      <div class="card">
        <router-link class="routerLink" to="/react-components">
          <div class="boxSubCard">
            <div class="subCard">
              <img
                class="imageStyle"
                src="../assets/example.jpg"
                alt="exemplo"
                width="100%"
                height="100%"
              >
            </div>
          </div>
          <div class="boxSubTitles">
            <h1 class="titleCard">React Components</h1>
            <div class="boxBadges">
              <i class="eachBadges free">Free</i>
              <i class="eachBadges paid">Paid</i>
            </div>
          </div>
        </router-link>
      </div>
    </div>
  </div>
</template>

<script>
import HeadHome from './HeadHome.vue';
export default {
  components: {
    'head-home': HeadHome,
  }
};
</script>

<style lang="scss" scoped>
.boxCards {
  height: 100%;
  width: 100%;
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
}
.card {
  width: 40%;
  height: fit-content;
  border-color: #f6f6f6;
  margin-top: 80px;
  margin-bottom: 40px;
  border-radius: 10px;
  color: #333;
  background: #fff;
  box-shadow: 0px 0px 35px 7px rgba(0, 0, 0, 0.1);
  position: relative;
  display: flex;
  flex-direction: column;
  min-width: 0;
  word-wrap: break-word;
  min-height: 1px;
  padding-right: 15px;
  padding-left: 15px;
  font-size: 1rem;
}

.subCard {
  width: 90%;
  height: 350px;
  margin: 0 auto;
  margin-top: -30px;
  background-color: black;
  border-radius: 10px;
  transition: 1.4s;
}

.boxSubCard:hover, .boxSubCard:active {
  .subCard {
    transform: translate3d(0, -50px, 0);
    transition: transform 1.4s;
  }
}

.routerLink {
  text-decoration: none;
}

.titleCard {
  margin-top: 10px;
  display: inline-block;
  width: fit-content;
  left: 0px;
  font-family: 'Crimson Text', serif;
  color: #a4a4a4;
}

.title {
  width: fit-content;
  margin: 0 auto;
  margin-top: 40px;
  font-family: 'Indie Flower', cursive;
  font-size: 3rem;
  font-weight: 900;
  color: #FFFFFF;
}

.imageStyle {
  border-radius: 10px;
}

.boxSubTitles {
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: row;
  align-content: center;
  justify-content: space-around;
}

.eachBadges {
  margin-left: 10px;
  margin-right: 10px;
  font-weight: 900;
  font-size: 1.2rem;
  padding: 2px 10px;
  border-radius: 15px;
  transition: 2s;
}

.boxBadges {
  width: 150px;
  display: flex;
  justify-content: space-between;
}

.free {
  color: #5cce4d;
}

.free:hover {
  background-color: #5cce4dda;
  color: #fff;
}

.paid {
  color: #455fd1;
}

.paid:hover {
  background-color: #455fd1de;
  color: #fff;
}

@media only screen and (max-width: 700px) {
  .boxCards {
    width: 100vw;
    flex-direction: column;
  }

  .card {
    width: 80%;
    margin: 80px auto;
    font-size: 0.6rem;
  }

  .boxSubTitles {
    flex-direction: column;
  }

  .boxBadges {
    width: 100%;
    margin-bottom: 15px;
    display: flex;
    justify-content: space-between;
  }

  .eachBadges {
    width: fit-content;
    margin-right: 25px;
    margin-left: 25px;
  }

  .title {
    font-size: 1.8rem;
  }

}
</style>

