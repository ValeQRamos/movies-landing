<script setup></script>

<template>
  <div class="main">
    <p id="title">The same movies project in different frameworks.</p>
    <div class="container">
      <div class="link">
        <a href="https://movies-angular-app.netlify.app/" target="_blank">
          <img class="img" src="./assets/images/angular.png" alt="angular" />
        </a>
      </div>

      <div class="link">
        <a href="https://movie-vue-app3.netlify.app/" target="_blank">
          <img class="img" src="./assets/images/vue.jpg" alt="vue" />
        </a>
      </div>

      <div class="link">
        <a href="https://movie-react-app2.netlify.app/" target="_blank">
          <img class="img" src="./assets/images/react.jpg" alt="react" />
        </a>
      </div>

      <div class="link">
        <a
          href="https://movie-js-app.netlify.app/"
          id="javascript"
          target="_blank"
        >
          <img
            class="img"
            src="./assets/images/javascript.jpg"
            alt="javascript"
          />
        </a>
      </div>
    </div>
  </div>
</template>

<style scoped>
.main {
  width: 100%;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
  align-items: center;
}

.container {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
  width: 550px;
  height: 550px;
}
#title {
  font-size: 40px;
  text-align: center;
  margin-top: 25px;
}
.link {
  width: 250px;
  height: 250px;
  margin: 5px 10px;
  box-shadow: rgba(0, 0, 0, 0.4) 0px 2px 4px,
    rgba(0, 0, 0, 0.3) 0px 7px 13px -3px, rgba(0, 0, 0, 0.2) 0px -3px 0px inset;
}

@media (max-width: 830px) {
  #title {
    font-size: 30px;
  }
}

@media (max-width: 630px) {
  .container {
    flex-direction: column;
    justify-content: space-evenly;
    flex-wrap: nowrap;
    height: calc(100vh - 50px);
    width: 100%;
  }
  .link {
    width: 125px;
    height: 125px;
  }
  .img {
    width: 125px;
    height: 125px;
  }
  #title {
    font-size: 20px;
  }
}
</style>
