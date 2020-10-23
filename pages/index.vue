/*
 * @Author: web.王晓冬
 * @Date: 2020-10-22 18:31:52
 * @LastEditors: web.王晓冬
 * @LastEditTime: 2020-10-22 19:45:53
 * @Description: file content
*/

<template>
  <div class="app-content">
    <div class="app-home d-flex-center">
      <div class="app-home-box">
        <h2 class="app-home-title">LINGO新标签页</h2>

        <div
          data-function="spicr"
          data-interval="false"
          data-touch="false"
          class="spicr spicr-slider home-mac app-home-scale"
        >
          <iframe
            class="home-mac-screen"
            width="100%"
            height="86%"
            src="http://dreamwq.com/search/"
            frameborder="0"
          ></iframe>
          <div class="home-mac-bar"></div>
          <img class="home-mac-bar-zuo" src="@/assets/img/bar.png" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="less">
.app-content {
  height: 100vh;
  width: 100vw;
}
.app-home {
  width: 100%;
  height: 100%;
  text-align: center;
  background-color: #101010;
  .app-home-title {
    font-size: 60px;
    color: #fff;
  }
  .home-mac {
    margin-top: -10px;
    width: 1100px;
    height: 740px;
    .home-mac-screen {
      border: 35px solid #000;
      border-radius: 20px 20px 0 0;
    }
    .home-mac-bar {
      height: 12%;
      background-color: #1f1f21;
      background-image: linear-gradient(to right, #070707, #4f4e54);
      border-radius: 0 0 20px 20px;
    }
    background: #101010;
  }
  .app-home-scale {
    transform: scale(0.8);
  }
}
</style>
