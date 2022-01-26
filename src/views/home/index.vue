<template>
  <div id="login">
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
    <div class="form">333</div>
    <div>222</div>
  </div>
</template>

<script>

</script>

<style >
body {
  margin: 0;
  padding: 0;
  overflow-y: hidden;
}
	.login{
    width: 100%;
    height: 100%;
}
.login-bg{
    width: 100%;
    height: 100%;
    background: linear-gradient(#43C6AC, #F8FFAE);
}
.form {
  background-color: white;
  height: 75%;
  width: 90%;
  position: fixed;
  /* left: calc(50% - 150px);
  top: calc(50% - 50px); */
  left: 5%;
  top: 25%;

}

</style>
