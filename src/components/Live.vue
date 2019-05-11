<template>
  <div class="box">
    <div class="live">
      <div class="tit">
        <h2>直播课程</h2>
        <p>LIVE COURSE</p>
      </div>
      <div class="course">
        <div class="detail hover">
          <img src="../assets/img/1 copy.png" alt>
          <h4>高一 地理 必修1 同步课程</h4>
          <p>本课程让你形成科学的人地观,提高学生对人口、资源、环境的理解，培养孩子对地理的兴趣….</p>
          <div class="study">
            <span class="price">￥ 免费</span>
            <span class="inStudy">
              <i></i>18人正在学习
            </span>
          </div>
          <div class="teacher">
            <i></i>马长兵
          </div>
        </div>
        <div class="detail">
          <img src="../assets/img/1 copy.png" alt>
          <h4>高一 地理 必修1 同步课程</h4>
          <p>本课程让你形成科学的人地观,提高学生对人口、资源、环境的理解，培养孩子对地理的兴趣….</p>
          <div class="study">
            <span class="price">￥ 免费</span>
            <span class="inStudy">
              <i></i>18人正在学习
            </span>
          </div>
          <div class="teacher">
            <i></i>马长兵
          </div>
        </div>
        <div class="detail">
          <img src="../assets/img/1 copy.png" alt>
          <h4>高一 地理 必修1 同步课程</h4>
          <p>本课程让你形成科学的人地观,提高学生对人口、资源、环境的理解，培养孩子对地理的兴趣….</p>
          <div class="study">
            <span class="price">￥ 免费</span>
            <span class="inStudy">
              <i></i>18人正在学习
            </span>
          </div>
          <div class="teacher">
            <i></i>马长兵
          </div>
        </div>
        <div class="detail">
          <img src="../assets/img/1 copy.png" alt>
          <h4>高一 地理 必修1 同步课程</h4>
          <p>本课程让你形成科学的人地观,提高学生对人口、资源、环境的理解，培养孩子对地理的兴趣….</p>
          <div class="study">
            <span class="price">￥ 免费</span>
            <span class="inStudy">
              <i></i>18人正在学习
            </span>
          </div>
          <div class="teacher">
            <i></i>马长兵
          </div>
        </div>
      </div>
      <div class="more">更多课程<i>></i></div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.box {
  width: 1200px;
  margin:48px auto 14px;
  .live {
    .tit {
      text-align: center;
      margin-bottom: 36px;
      h2 {
        font-size: 32px;
        line-height: 45px;
        color: #464c60;
      }
      p {
        margin-top:1px;
        font-size: 18px;
        line-height: 25px;
        color: #d8d8d8;
      }
    }
    .course {
      .detail {
        display: inline-block;
        width: 289px;
        height: 364px;
        background: rgba(255, 255, 255, 1);
        box-sizing: border-box;
        padding: 6px;
        margin:0 14px 24px 0;
        img {
          width: 277px;
          height: 158px;
        }
        h4 {
          color: #333333;
          font-size: 14px;
          margin: 23px 0 8px;
        }
        p {
          color: #666666;
          font-size: 12px;
          line-height: 17px;
        }
        .study {
          margin: 19px 0 13px;
          display: flex;
          justify-content: space-between;
          .price {
            color: #ff974d;
            font-size: 16px;
            line-height: 28px;
          }
          .inStudy {
            color: #999999;
            font-size: 12px;
            i {
              display: inline-block;
              margin-right: 4px;
              width: 14px;
              height: 12px;
              background: url("../assets/img/分组 8.png") no-repeat center
                center;
            }
          }
        }
        .teacher {
          i {
            display: inline-block;
            width: 28px;
            height: 28px;
            margin-right: 11px;
            vertical-align: middle;
            background-color:#049DB4;
          }
        }
        &:nth-of-type(4n){
          margin-right: 0;
        }
        &.hover {
          box-shadow: 1px 8px 16px 4px rgba(187, 187, 187, 0.38);
        }
      }
    }
    .more {
      width: 117px;
      height: 38px;
      line-height: 38px;
      box-sizing: border-box;
      border-radius: 19px;
      margin:16px auto 0;
      border: 1px solid rgba(210, 210, 210, 1);
      font-size: 16px;
      color:#666666;
      padding-left: 16px;
      i{
         font-style: normal;
         margin-left: 9px;
      }
    }
  }
}
</style>

<script>
export default {
  name: "live"
};
</script>
