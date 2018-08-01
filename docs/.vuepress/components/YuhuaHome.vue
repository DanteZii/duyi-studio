<template>
  <div class="">
      <div class="home-page-wrapper banner-wrapper" id="banner">
        <div class="banner-bg-wrapper">
          <div class="banner page">
            <div class="text-wrapper">
              <h1>YuhuaTrade</h1>
              <p>
                <span>
                  一个服务于企业级海产品国际供应商，遵循『快速』和『信誉』的价值观和模块化的解决方案，让企业专注于更好的专注于业务。
                </span>
              </p>
              <div class="banner-btns">
                <router-link to="/Product/" class="banner-btn components"><span>产品列表</span></router-link>
              </div>
            </div>
            <div class="img-wapper"><img src="https://gw.alipayobjects.com/zos/rmsportal/KDpgvguMpGfqaHPjicRK.svg" alt=""></div>
            </div>
        </div>
      </div>
  </div>

</template>

<script>

</script>

<style>
.banner-wrapper {
    overflow: initial;
    position: relative;
    z-index: 1;
}
.home-page-wrapper {
    width: 100%;
    padding: 0;
    overflow: hidden;
    position: relative;
    color: #314659;
    font-family: Avenir,Monospaced Number,Chinese Quote,-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,PingFang SC,Hiragino Sans GB,Microsoft YaHei,Helvetica Neue,Helvetica,Arial,sans-serif;
}
.home-page-wrapper .page {
    width: 100%;
    max-width: 1200px;
    margin: auto;
    position: relative;
    padding: 0 24px;
}
.banner {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    height: 576px;
}
.banner .text-wrapper {
    width: 54%;
    max-width: 560px;
    min-width: 420px;
    min-height: 336px;
    color: #0d1a26;
}
.banner .text-wrapper h1 {
    font-size: 68px;
    font-weight: 600;
    line-height: 76px;
    margin: 8px 0 28px;
    letter-spacing: 0;
    font-family: Avenir,Monospaced Number,Chinese Quote,-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,PingFang SC,Hiragino Sans GB,Microsoft YaHei,Helvetica Neue,Helvetica,Arial,sans-serif;
}
.banner .text-wrapper p {
    font-size: 20px;
    line-height: 40px;
    color: #314659;
}
.banner .img-wrapper {
    width: 46%;
    max-width: 482px;
    position: absolute;
    right: 0;
    bottom: 26px;
    margin-left: 50%;
}
img {
  margin-left: 90%;
  width: 130%;
  height: 130%;
}

/*按钮*/
.banner .banner-btns {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    margin-top: 24px;
    min-width: 520px;
}
.banner .banner-btns {
    display: -webkit-box;
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: center;
    -webkit-align-items: center;
    -ms-flex-align: center;
    align-items: center;
    margin-top: 24px;
    min-width: 520px;
}
.banner .banner-btn.components {
    background: #2f54eb;
    color: #fff;
}
.banner .banner-btn {
    padding: 0 24px;
    border-radius: 100px;
    font-size: 16px;
    line-height: 38px;
    display: inline-block;
    height: 40px;
    text-align: center;
    margin-right: 16px;
    text-decoration: none;
    border: 1px solid #2f54eb;
    font-family: Monospaced Number,Chinese Quote,-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,PingFang SC,Hiragino Sans GB,Microsoft YaHei,Helvetica Neue,Helvetica,Arial,sans-serif;
}

</style>
