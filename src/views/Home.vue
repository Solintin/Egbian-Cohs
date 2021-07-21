<template>
  <div>
    <div class="homepage">
      <div class="left">
        <h1>
          This Website is Under Construction
        </h1>
        <h5>
          We will be back soon!
        </h5>
      </div>
      <div class="right">
        <img src="../assets/Under-cons.svg" alt="under-contruction" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Home",
  created() {},
  data() {
    return {};
  },
  props: {},
  methods: {},
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Ubuntu&display=swap");
.homepage {
  height: 100vh;
  width: 100%;
  margin: 0;
  display: flex;
  flex-direction: row;
}
.left {
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 100px;
  width: 50%;
}
.left h1 {
  color: #00bfff;
  font-weight: 700;
  font-size: 50px;
  margin: 0;
}
.left h5 {
  font-weight: 700;
  font-size: 20px;
}

.right {
  display: flex;
  justify-content: center;
  flex-direction: column;
  padding: 100px;
  width: 50%;
  background: #00bfff;
}
.right img {
  height: 100%;
  width: 100%;
}
/* Mobile Responsiveness */
@media screen and (max-width: 765px) {
  .homepage .right {
    display: none !important;
  }

  .homepage .left {
    text-align: center ;
    width: 100%;
    align-items: center;
  }
  .left h1 {
    font-size: 40px !important;
    line-height: 2.5rem;
  }
}

@media screen and (max-width: 960px) {
  .left h1 {
    font-size: 35px !important;
    line-height: 2.5rem;
  }
}
</style>
