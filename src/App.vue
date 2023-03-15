<script setup></script>

<template>
  <p id="title">the same movies project in different frameworks</p>
  <div class="container">
    <div class="link">
      <a
        href="https://movie-js-app.netlify.app/"
        id="javascript"
        target="_blank"
      >
        <img src="./assets/images/javascript.jpg" alt="javascript" />
      </a>
    </div>
    <div class="link">
      <a href="https://movie-vue-app3.netlify.app/" target="_blank">
        <img src="./assets/images/vue.jpg" alt="vue" />
      </a>
    </div>
    <div class="link">
      <a href="https://movie-react-app2.netlify.app/" target="_blank">
        <img src="./assets/images/react.jpg" alt="react" />
      </a>
    </div>
  </div>
</template>

<style scoped>
.container {
  display: flex;
  align-items: center;
  justify-content: center;
}
#title {
  font-size: 40px;
  text-align: center;
  margin-top: 25px;
}
.link {
  width: 250px;
  height: 250px;
  margin: 40px 25px;
  box-shadow: rgba(0, 0, 0, 0.4) 0px 2px 4px,
    rgba(0, 0, 0, 0.3) 0px 7px 13px -3px, rgba(0, 0, 0, 0.2) 0px -3px 0px inset;
}

@media (max-width: 800px) {
  .container {
    flex-direction: column;
  }
  #title {
    font-size: 25px;
  }
}

@media (max-width: 500px) {
  #title {
    font-size: 20px;
  }
}
</style>
