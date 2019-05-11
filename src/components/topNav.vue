<template>
  <nav>
    <div class="left">
      <h1>课365</h1>
      <span class="active">首页</span>
      <span>全部课程</span>
      <span>名师汇</span>
    </div>
    <div class="right">
      <div class="search">
        <input type="text">
        <i></i>
      </div>
      <div class="tip">
        <i></i>
      </div>
      <div class="my">
        <div class="detail">
          <ul>
            <li>
              <img src="../assets/img/合并形状.png" alt>个人中心
            </li>
            <li>
              <img src="../assets/img/分组 19.png" alt srcset>管理后台
            </li>
            <li>
              <img src="../assets/img/jiaoxue.png" alt>我的教学
            </li>
            <li>
              <img src="../assets/img/分组 8 copy.png" alt>我的学习
            </li>
            <li>
              <img src="../assets/img/kecheng.png" alt>课程市场
            </li>
            <li>
              <img src="../assets/img/tuichu.png" alt>退出市场
            </li>
          </ul>
        </div>
      </div>
    </div>
  </nav>
</template>

<style lang="scss" scoped>
nav {
  width: 1200px;
  margin: 0 auto;
  box-sizing: border-box;
  height: 80px;
  background: rgba(255, 255, 255, 1);
  .left {
    float: left;
    line-height: 80px;
    h1 {
      display: inline-block;
      font-size: 0;
      width: 105px;
      height: 48px;
      margin-top: 7px;
      margin-right: 48px;
      background: url("../assets/img/资源 2.png") no-repeat center center;
    }
    span {
      height: 25px;
      font-size: 18px;
      font-family: PingFang-SC-Medium;
      font-weight: 500;
      color: #bbbbbb;
      line-height: 25px;
      text-align: left;
      margin-right: 36px;
      &.active {
        color: #1eaefa;
      }
    }
  }
  .right {
    float: right;
    & > div {
      float: left;
    }
    .search {
      position: relative;
      margin-right: 17px;
      input {
        display: block;
        width: 277px;
        height: 46px;
        margin-top: 17px;
        border-radius: 2px;
        opacity: 0.38549999999999995;
        border: 1px solid rgba(51, 51, 51, 1);
      }
      i {
        position: absolute;
        top: 29px;
        left: 241px;
        width: 23px;
        height: 27px;
        background: url("../assets/img/搜索.png") no-repeat center center;
      }
    }
    .tip {
      width: 59px;
      height: 59px;
      background: url("../assets/img/椭圆形.png") no-repeat center center;
      margin: 12px 21px 9px 0;
      overflow: hidden;
      i {
        display: block;
        width: 27px;
        height: 31px;
        background: url("../assets/img/合并形状(1).png") no-repeat center top;
        margin: 17px 16px 11px 16px;
      }
    }
    .my {
      width: 38px;
      height: 38px;
      margin-top: 21px;
      background-color: #049db4;
      position: relative;
      .detail {
        position: absolute;
        z-index: 2;
        top: 59px;
        left: -9px;
        width: 127px;
        background-color: pink;
        background: rgba(236, 248, 255, 1);
        box-shadow: 0px 4px 4px 2px rgba(0, 0, 0, 0.2);
        li {
          height: 48px;
          line-height: 48px;
          padding: 0 24px;
          font-size: 14px;
          color: #666666;
          img {
            width: 15px;
            height: 15px;
            vertical-align: middle;
            margin-right: 8px;
          }
        }
      }
    }
  }
}
</style>


<script>
export default {
  name: "topNav"
};
</script>

