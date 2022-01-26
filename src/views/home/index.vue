<template>
  <div id="content">
    <div class="header">header</div>
    <vue-particles
      :particle-opacity="0.7"
      :particles-number="100"
      :particle-size="4"
      :lines-width="1"
      :line-linked="true"
      :line-opacity="0.4"
      :lines-distance="150"
      :move-speed="3"
      :hover-effect="true"
      :click-effect="true"
      class="login-bg"
      color="#fff"
      shape-type="circle"
      lines-color="#fff"
      hover-mode="grab"
      click-mode="push"
    />
    <div class="left_aside">left</div>
    <!-- <div class="right_aside">right</div> -->
    <div class="form">333</div>
  </div>
</template>

<script>

</script>

<style >
body {
  margin: 0;
  padding: 0;
  /* overflow-y: hidden; */
}
.content{
    width: 100%;
    height: 100%;
    position: relative;
}
.header {
  width: 100%;
  background-color: white;
  height: 75px;
  position: fixed;
  top: 0;
  border-bottom: 1px solid  black;
  z-index: 2;
}
.left_aside {
  position: fixed;
  left: 0;
  top: 20%;
  height: 514px;
  width: 270px;
  background-color: yellow;
  z-index: 3;
}
/* .right_aside {
  position: fixed;
  right: 0;
  top: 20%;
  height: 514px;
  width: 310px;
  background-color: yellow;
  z-index: 3;
} */
.login-bg{
    width: 100%;
    height: 100%;
    background: linear-gradient(#43C6AC, #F8FFAE);
}
.form {
  background-color: pink;
  height: 1000px;
  width: 100%;
  position: absolute;
  /* left: calc(50% - 444px); */
  /* top: calc(50% - 50px); */
  top: 40%;
  /* border: 1px solid black; */

}

</style>
