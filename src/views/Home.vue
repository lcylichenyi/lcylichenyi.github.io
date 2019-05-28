<template>
  <div style="display: flex; height: 130%">
    <div class="header">
      <div class="container">
        <div class="line-1">
          <div>
            <p class="hidden-xs-only">天路云</p>
          </div>
          <div>
            <span>请务必<i>收藏本页</i>！随时更新主链接！</span>
            <span><i>Ctrl + D</i>快速加入书签</span>
          </div>
        </div>
        <div class="line-2">
          <h1>
            <span>世界这么大</span>
            <span>你要出去看看</span>
          </h1>
          <p>
            <span>Android/ iOS / Windows / MacOS/Linux/Steam/PS4客户端全支持</span>
          </p>
          <p>
            <span>无限流量, 畅快上网</span>
            <span>可能是唯一保证14天无条件退款的服务商</span>
          </p>
        </div>
        <div class="line-3">
          <a href="http://91tianlu.band/aff.php?aff=1589">
            进入官方主页
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component({
  components: {
  },
})
export default class Home extends Vue {

}
</script>

<style lang="scss" scope>

@media (min-width: 1200px) {
  .container {
    // background-color: pink;
    padding-left: 200px;
    padding-right: 200px;
  }
}

@media (min-width: 992px) and (max-width: 1200px) {
  .container {
    // background-color: red;
    padding-left: 70px;
    padding-right: 70px;
  }
}

@media (min-width: 768px) and (max-width: 992px) {
  .container {
    // background-color: green;
    padding-left: 20px;
    padding-right: 20px;
  }
}

@media (max-width: 768px) {
  .container {
    // background-color: grey;
    padding-left: 20px;
    padding-right: 20px;
  }
}

.header {
  padding-top: 20px;
  box-sizing: border-box;
  flex: 1;
  background-color: #2c2f4c;
  .line-1 {
    display: flex;
    justify-content: space-between;
    div {
      letter-spacing: 1px;
      &:first-child {
        color: #FFF;
        height: auto;
        font-size: 26px;
      }
      &:last-child {
        box-sizing: border-box;
        border: 1px solid #fff;
        border-radius: 20px;
        padding: 20px;
        color: #FFF;
        height: auto;
        font-size: 26px;
        flex-direction: column;
        display: flex;
        box-shadow: 0px 0px 1px 1px;
        span {
          flex: 1;
        }
        i {
          color: red;
          font-weight: 700;
          font-style: normal;
        }
      }
    }
  }
  .line-2 {
    margin-left: -10px;
    margin-top: 105px;
    h1 {
      display: flex;
      flex-wrap: wrap;
      font-weight: 400;
      flex-direction: column;
      color: #fff;
      font-size: 48px;
      margin-bottom: 15px;
    }
    p {
      line-height: 30px;
      font-size: 18px;
      letter-spacing: 1px;
      &:nth-child(2) {
        color: #008ed6;
      }
      &:last-child {
        display: flex;
        flex-direction: column;
        color: #999;
      }
    }
  }
  .line-3 {
  margin-top: 80px;
  margin-left: -10px;
    a {
      border-radius: 3px;
      font-size: 34px;
      font-weight: bold;
      padding: 34px 70px;
      background: transparent;
      border: 1px solid rgba(255, 255, 255, 0.6);
      color: #fff;
      text-decoration: none;
      transition: 0.3s;
      &:hover {
        background: #fff;
        color: #008ed6;
        box-shadow: inset 0 3px 5px rgba(0,0,0,.125);
      }
    }
    
  }
}
</style>
