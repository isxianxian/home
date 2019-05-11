<template>
  <div class="bottom">
    <div class="box">
      <div class="left">
        <img src="../assets/img/Image 2 Copy.png" alt>
        <i>扫一扫联系我们</i> 
      </div>
      <div class="center">
        <ul>
          <li>首页</li>
          <li>全部课程</li>
          <li>名师汇</li>
        </ul>
        <p>
          Copyright
          <i>c</i>2005 - 2017 ke365.net版权所有 鄂ICP备17028607号-2
        </p>
      </div>
      <div class="right">
        <h4>联系我们</h4>
        <p>地址：武汉市东湖新技术开发区湖北二师</p>
        <p>电话：18901194191</p>
        <p>邮箱：liuqimin2009@163.com</p>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.bottom {
  background-color: #1eaefa;
  width: 100%;
  .box {
    width: 1200px;
    height: 236px;
    margin: 0 auto;
    padding-top: 63px;
    box-sizing: border-box;
    & > div {
      float: left;
    }
    .left {
      color: #fefefe;
      line-height: 20px;
      letter-spacing: 3px;
      padding-top: 10px;
      font-family: PingFang-SC-Regular;
      img {
        display: block;
        width: 101px;
        height: 102px;
      }
      i{
          font-style: normal;
          margin-top:4px;
      }
    }
    .center {
      text-align: center;
      margin: 0 126px 0 164px;
      padding-top: 10px;
      ul {
        height: 20px;
        padding: 3px 0 2px;
        margin-bottom: 54px;
        display: inline-block;
        li {
          float: left;
          font-size: 18px;
          font-family: PingFangSC-Regular;
          font-weight: 400;
          color: #ffffff;
          line-height: 20px;
          padding: 0 28px 0 29px;
          border-right: 2px solid rgba(255, 255, 255, 1);

          &:last-child {
            border-right: 0;
          }
        }
      }

      p {
        font-size: 14px;
        line-height: 20px;
        font-family: PingFangSC-Regular;
        font-weight: 400;
        color: #fefefe;
        i {
          font-style: normal;
        }
      }
    }
    .right {
      color: rgba(255, 255, 255, 1);
      h4 {
        font-size: 18px;
        font-family: PingFang-SC-Medium;
        font-weight: 500;
        line-height: 25px;
      }
      p {
        font-size: 14px;
        font-family: PingFang-SC-Regular;
        font-weight: 400;
        line-height: 20px;
        margin: 7px 0 6px;
        color: #fefefe;
      }
    }
  }
}
</style>

<script>
export default {
  name: "BotNav"
};
</script>
