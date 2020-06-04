<template>
  <div class="plateform">
    <div class="header">
      <headerbar></headerbar>
    </div>

    <div class="content">
      <!-- //banner -->
      <div class="banner">
        <div class="main-img">
          <div class="ad-title">
            <div class="t1">2020钉钉 春雷计划</div>
            <div class="t2">助力中小企业/教育/政府</div>
            <div>
              <button class="btn">了解更多</button>
            </div>
          </div>
          <div class="item-box">
            <div class="inl-block side-box">《</div>
            <span
              class="inl-block active-item"
              style="margin:0 5px"
              v-for="index in 10"
              :key="index"
            >|</span>
            <div class="inl-block side-box">》</div>
          </div>
        </div>
        <div class="side-img">
          <div class="side-img-box" v-for="index in 4" :key="index">
            <div class="ad-title">
              <div class="t1">专属钉钉</div>
              <div class="t2">打造企业组织专属的数字化工作学习生活方式</div>
            </div>
            <div class="more">了解更多 ——></div>
          </div>
        </div>
        <div class="arrow-box">
          <div class="arrow fl">《</div>
          <div class="arrow fr">》</div>
          <div class="line-bar fl">
            <div class="active-line"></div>
          </div>
        </div>
      </div>

      <!-- //video -->
      <div class="video-box">
        <div class="text">3亿人用钉钉，让工作学习更简单</div>
        <div class="video">
          <img src="@/assets/video.png" alt />
        </div>
      </div>

      <!-- //sell-point -->
      <div class="sell-point">
        <div class="title">
          <div class="tit-box">群聊沟通</div>
          <div class="tit-box">信息专注</div>
          <div class="tit-box">视频会议</div>
        </div>
        <div class="sell-content">
          <div class="sell-img ib">
            <img src="@/assets/laptop.png" alt />
          </div>
          <div class="sell-text fr">
            <div style="margin:30px 0">
              <div class="sell-title">还在耗时耗力奔波开会？</div>
              <div class="sell-cont-text">随时随地一键发起视频会议</div>
              <div class="sell-cont-text">最多支持302人同时在线</div>
            </div>
            <div style="marign:30px 0">
              <div class="sell-title">异地开会效率无法保证？</div>
              <div class="sell-cont-text">随时开启共享窗口同步重要文件</div>
            </div>
          </div>
        </div>
      </div>

      <!-- //30s to use -->
      <div class="easy-to-use">
        <div class="easyuse-tit">30秒快速上手钉钉</div>
        <div class="easyuse-flim ib" v-for="index in 3" :key="index">
          <div class="flim">
            <img src="@/assets/checkin.png" alt />
          </div>
          <div class="flim-text">
            如何用钉钉
            <div class="func">人性化考勤</div>
          </div>
        </div>
      </div>

      <!-- //advance -->
      <div class="advance">
        <div class="adv-tit">
          在钉钉
          <div class="adv-main">工作简单高效更安全</div>
        </div>
        <div class="adv-box ib" v-for="index in 3" :key="index">
          <div class="adv-img">
            <img src="//img.alicdn.com/tfs/TB1nEOtGhz1gK0jSZSgXXavwpXa-216-216.png" alt />
          </div>
          <div class="adv-text">
            <div class="text-tit">组织关系在线化</div>
            <div class="text-cont">安全可靠的组织通讯录，快速找到同事，实现组织架构扁平化、可视化</div>
          </div>
        </div>
        <div class="adv-tit">
          在钉钉
          <div class="adv-main">工作简单高效更安全</div>
        </div>
        <div class="adv-box ib" v-for="index in 3" :key="index">
          <div class="adv-img">
            <img src="//img.alicdn.com/tfs/TB1nEOtGhz1gK0jSZSgXXavwpXa-216-216.png" alt />
          </div>
          <div class="adv-text">
            <div class="text-tit">组织关系在线化</div>
            <div class="text-cont">安全可靠的组织通讯录，快速找到同事，实现组织架构扁平化、可视化</div>
          </div>
        </div>
        <div class="btn-box">
          <button class="ib btn dl">立即下载</button>
          <button class="ib btn reg">立即注册</button>
        </div>
      </div>

      <!-- //simpal -->
      <div class="client-sim">
        <div class="sim-tit">客户案例</div>
        <div class="sim-box ib" v-for="index in 3" :key="index">
          <div class="sim-img">
            <img src="//img.alicdn.com/tfs/TB1tnPJGrj1gK0jSZFOXXc7GpXa-380-220.png" alt />
          </div>
          <div class="sim-text">
            <div class="type">纺织业 | 上海水星家纺</div>
            <div class="way">钉钉让思维和观念的改变成为习惯</div>
            <div class="content">水星家纺借助钉钉这样互联网化的交流工具，办公体系实现透明化、轻娱化，每一位水星人更有参与感、互动感。</div>
            <div class="more">了解更多 ——></div>
          </div>
        </div>
        <div class="look-more">查看更多</div>
      </div>

      <!-- //social -->
      <div class="social">
        <div class="social-tit">
          <div class="tit">钉钉正在为各行各业提供专业解决方案</div>
          <div class="text">
            <p>沉淀钉钉1500万企业组织核心业务场景</p>提供专属钉钉、教育、医疗、新零售等多行业多维度的解决方案
          </div>
        </div>
        <div class="social-cont">
          <div class="lair-top">
            <div class="ding-alone ib">
              <div class="box">
                <div class="tit">专属钉钉</div>
                <div class="cont">我的钉钉我做主，开启专属企业组织的数字化办公模式</div>
              </div>
              <div class="more">了解更多 ——></div>
            </div>
            <div class="dig-campus ib">
              <div class="box">
                <div class="tit">专属钉钉</div>
                <div class="cont">我的钉钉我做主，开启专属企业组织的数字化办公模式</div>
              </div>
              <div class="more">了解更多 ——></div>
            </div>
          </div>
          <div class="lair-top">
            <div class="dig-shop ib" v-for="index in 3" :key="index">
              <div class="box">
                <div class="tit">数字化门店协同</div>
                <div class="cont">构建零售渠道和门店协同的数字化能力，全面提升门店业务的运转效率</div>
              </div>
              <div class="more">了解更多 ——></div>
            </div>
          </div>
        </div>
      </div>

      <!-- //scure -->
      <div class="scure">
        <div class="scure-tit">
          <div class="tit">钉钉正在为企业组织信息安全保驾护航</div>
          <div class="content">
            <p>ISO 27001:2013信息安全管理体系标准认证</p>
            <p>公安部信息系统三级等级保护认证</p>
          </div>
        </div>
        <div class="scure-cont">
          <div class="cont-box ib" v-for="index in 3" :key="index">
            <div class="box-img">
              <img src="//img.alicdn.com/tfs/TB1PGmwGoT1gK0jSZFhXXaAtVXa-216-216.png" alt />
            </div>
            <div class="box-text">
              <div class="box-tit">沟通内容加密</div>
              <div class="box-cont">通讯录、聊天信息采用钉钉和第三方秘钥系统，沟通内容全面保护。</div>
            </div>
          </div>
        </div>
      </div>

      <!-- //download -->
      <div class="download">
        <div class="dl-reg">
          <div class="btn-box">
            <button class="ib btn dl">立即下载</button>
            <button class="ib btn reg">立即注册</button>
          </div>
        </div>
      </div>
    </div>

    <div class="footer">
      <div class="about-ding">
        <div class="about-list ib" v-for="index in 6" :key="index">
          <div class="list-tit">热门产品</div>

          <li class="list-cont">在线课堂</li>
          <li class="list-cont">考勤表</li>
          <li class="list-cont">日志</li>
          <li class="list-cont">公告</li>
          <li class="list-cont">只能填表</li>
        </div>
      </div>
      <div class="cooperation">
        <div class="business-info ib">
          <div>市场商务合作</div>
          <div>dingtalk_market@service.dingtalk.com</div>
        </div>
        <div class="enlarge ib">
          <div class="icon ib" v-for="index in 4" :key="index">
            <img src="https://gw.alicdn.com/tfs/TB16zuGGaL7gK0jSZFBXXXZZpXa-64-64.png" alt />
          </div>
        </div>
        <div class="vision-box ib">
          <div class="vision ib" v-for="index in 4" :key="index">
            <img src="https://gw.alicdn.com/tfs/TB1W1uCGeL2gK0jSZPhXXahvXXa-194-84.png" />
          </div>
        </div>
      </div>
      <div class="offical-info">
        <div class="business-left ib">阿里巴巴集团</div>
        <div class="business ib" v-for="(item,index) in businesslist" :key="index">| {{item.text}}</div>
      </div>
      <div class="copyright">阿里钉钉Ⓒ版权公告© 2014-2020 钉钉（中国）信息技术有限公司和／或其关联公司版权所有</div>
      <div class="allowrance">浙ICP备18037475号 跨地区增值电信业务证号：B2-20184300 浙江省增值电信业务经营许可证：浙B2-20180981</div>
      <div class="police">
        <img class="ib" src="@/assets/police.png" alt />
        <div class="ib">浙公网安备 33011002010140号</div>
        <img class="ib" src="@/assets/police-red.png" alt />
      </div>
    </div>

    <div class="contect-us">
      <img class="img" src="@/assets/chat.png" alt />
      <div class="box">联系我们</div>
    </div>
  </div>
</template>

<script>
import headerbar from "@/components/headerbar.vue";
export default {
  name: "plateform",
  data() {
    return {
      businesslist: [
        {
          text: "淘宝网"
        },
        {
          text: "天猫"
        },

        {
          text: "聚划算"
        },

        {
          text: "全球速卖通"
        },

        {
          text: "阿里巴巴国际交易市场"
        },

        {
          text: "1688"
        },

        {
          text: "阿里妈妈"
        },

        {
          text: "飞猪"
        },

        {
          text: "阿里云计算"
        },

        {
          text: "Alios"
        },
        {
          text: "支付宝"
        },
        {
          text: "支付宝商家平台"
        },

        {
          text: "UC"
        },

        {
          text: "天猫新零售"
        },

        {
          text: "阿里聚安全"
        },

        {
          text: "达摩院"
        },

        {
          text: "友盟"
        }
      ]
    };
  },
  components: {
    headerbar
  }
};
</script>

<style lang="less">
.plateform {
  //   padding: 0 10px;
  .header {
    width: 100%;
    // background: blue;
  }
  .content {
    margin-top: 10px;
    text-align: left;
    // background: rgb(218, 218, 164);
    padding: 0 1%;
    .banner {
      width: 100%;
      //   background: rgb(241, 186, 241);
      .main-img {
        display: inline-block;
        width: 70%;
        height: 500px;
        background-image: url("//img.alicdn.com/tfs/TB1Y6YSGBr0gK0jSZFnXXbRRXXa-940-500.png");
        background-repeat: no-repeat;
        background-size: cover;
        position: relative;
        left: 0;
        .ad-title {
          color: white;
          text-align: left;
          //   background-color: red;
          position: absolute;
          top: 20%;
          left: 8%;
          .t1 {
            font-size: 48px;
            font-weight: bold;
            margin-bottom: 10px;
          }
          .t2 {
            font-size: 18px;
            line-height: 28px;
            margin-bottom: 30px;
          }
          .btn {
            padding: 15px 40px;
            background-color: white;
            color: rgb(66, 165, 204);
            border-radius: 5px;
            border: 1px solid white;
            font-size: 18px;
          }
        }
        .item-box {
          position: absolute;
          bottom: 15px;
          left: 8%;
          font-size: 24px;
          .side-box {
            margin: 0 20px;
          }
          .inl-block {
            display: inline-block;
            color: rgba(199, 199, 199, 0.5);
          }
          .active-item {
            // height: 30px;
            color: rgb(199, 199, 199, 0.5);
            &:hover {
              font-size: 24px;
              font-weight: bold;
              color: white;
            }
          }
        }
      }
      .side-img {
        display: inline-block;
        width: 30%;
        height: 500px;
        // background-color: yellowgreen;
        color: white;
        .side-img-box {
          display: inline-block;
          margin: 5px 0;
          margin-left: 3%;
          width: 47%;
          height: 240px;
          background-image: url("https://gw.alicdn.com/tfs/TB14pDrGpT7gK0jSZFpXXaTkpXa-486-486.png");
          background-repeat: no-repeat;
          background-size: cover;
          position: relative;
          .ad-title {
            color: white;
            text-align: left;
            //   background-color: red;
            position: absolute;
            top: 20%;
            left: 8%;
            .t1 {
              font-size: 18px;
              //   font-weight: bold;
              margin-bottom: 10px;
            }
            .t2 {
              font-size: 14px;
              //   line-height: 28px;
              margin-bottom: 30px;
            }
          }
          .more {
            position: absolute;
            bottom: 5px;
            left: 8%;
          }
        }
      }
      .arrow-box {
        width: 90%;
        height: 50px;
        margin: auto;
        // background-color: red; //
        .arrow {
          width: 25px;
          height: 25px;
          background-color: rgb(255, 255, 255);
          border-radius: 30px 30px;
          text-align: center;
          display: inline-block;
          border: 2px solid rgb(231, 231, 231);
          padding: 5px 10px 15px 10px;
          font-size: 24px;
          color: rgb(184, 184, 184);
        }
        .line-bar {
          top: 30px;
          width: 90%;
          margin-top: 20px;
          margin-left: 20px;
          height: 5px;
          background-color: rgb(199, 199, 199);
          .active-line {
            width: 70%;
            height: 5px;
            background-color: rgb(0, 94, 255);
          }
        }
      }
    }
    .video-box {
      margin: auto;
      margin-top: 60px;
      padding-bottom: 60px;
      width: 100%;
      text-align: center;
      background-color: rgb(246, 246, 246);
      .text {
        font-size: 48px;
        font-weight: bold;
        margin: 30px auto;
      }
      .video {
        margin: auto;
        width: 100%;
      }
    }
    .sell-point {
      margin-top: 20px;
      width: 100%;
      //   background-color: rgb(180, 198, 253);
      .title {
        font-weight: bold;
        font-size: 20px;
        height: 50px;
        text-align: center;
        .tit-box {
          height: 50px;
          display: inline-block;
          margin: 0 50px;
          //   background-color: rgb(0, 94, 255);
          box-sizing: border-box;
          &:hover {
            box-sizing: border-box;
            border: 5px solid transparent;
            border-bottom: 5px solid blue;
            border-radius: 0 0 -10px -10px;
          }
        }
        border-bottom: 1px solid rgb(170, 170, 170);
      }
      .sell-content {
        width: 100%;
        height: 450px;
        // background-color: rgb(142, 225, 65);
        margin-top: 60px;
        .sell-img {
          height: inherit;
          width: 50%;
          //   background-color: royalblue;
          img {
            width: 100%;
          }
        }
        .sell-text {
          //   padding-top: 80px;
          padding-bottom: 80px;
          width: 30%;
          margin: 0 10%;
          //   background-color: rgb(216, 142, 250);
          margin-top: 40px;
          text-align: left;
          .sell-title {
            font-size: 28px;
            margin-bottom: 10px;
          }
          .sell-cont-text {
            font-size: 16px;
            margin-bottom: 5px;
          }
        }
      }
    }
    .easy-to-use {
      width: 100%;
      padding-top: 60px;
      height: 500px;
      background-color: rgb(246, 246, 246);
      .easyuse-tit {
        width: 100%;
        text-align: center;
        font-size: 48px;
        font-weight: bold;
        margin: 20px 0;
      }
      .easyuse-flim {
        width: 30%;
        margin: 0 1.6%;
        // background-color: turquoise;
        .flim-text {
          font-size: 18px;
          color: rgb(87, 87, 87);
          .func {
            font-size: 28px;
            font-weight: lighter;
          }
        }
      }
    }
    .advance {
      width: 100%;
      //   background: rgb(255, 201, 201);
      text-align: center;
      .adv-tit {
        margin-top: 80px;
        font-size: 32px;
        font-weight: bold;
        .adv-main {
          font-size: 48px;
        }
      }
      .adv-box {
        width: 30%;
        margin: 0 1.5%;
        margin-top: 30px;
        // background: rgb(208, 208, 253);
        .adv-text {
          font-size: 20px;
          .text-tit {
            font-size: 32px;
            font-weight: bold;
          }
        }
      }
      .btn-box {
        width: 100%;
        margin: 0 auto;
        margin-top: 60px;
        .btn {
          margin: 0 20px;
          padding: 20px 60px;
          font-size: 24px;
          border-radius: 10px;
        }
        .dl {
          background: rgb(0, 94, 255);
          color: white;
          border: 3px solid rgb(0, 94, 255);
        }
        .reg {
          background: white;
          color: rgb(0, 94, 255);
          border: 3px solid rgb(0, 94, 255);
        }
      }
    }
    .client-sim {
      width: 100%;
      margin-top: 80px;
      text-align: center;
      //   background: rgb(253, 233, 233);
      .sim-tit {
        font-size: 48px;
        font-weight: bold;
      }
      .sim-box {
        width: 30%;
        margin: 30px 1.6%;
        background: rgb(238, 238, 238);
        .sim-img {
          width: 100%;
          img {
            width: 100%;
          }
        }
        .sim-text {
          padding: 10px 20px;
          text-align: left;
          font-size: 16px;
          color: balck;
          height: 250px;
          position: relative;
          .way {
            font-size: 24px;
            font-weight: bold;
          }
          .content {
            margin-top: 20px;
            font-size: 20px;
          }
          .more {
            position: absolute;
            bottom: 5px;
            left: 5%;
            font-weight: bold;
            font-size: 18px;
          }
        }
      }
      .look-more {
        text-align: center;
        color: rgb(0, 94, 255);
        font-size: 24px;
      }
    }
    .social {
      width: 100%;
      //   background: rgb(240, 224, 224);
      margin-top: 80px;

      .social-tit {
        width: 60%;
        margin: 40px auto;
        // background: burlywood;
        text-align: center;
        font-size: 24px;
        font-weight: bold;
        .tit {
          font-size: 48px;
        }
      }
      .social-cont {
        width: 100%;
        // background: rgb(227, 196, 255);
        color: white;
        .lair-top {
          width: 100%;
          margin-top: 40px;
          .ding-alone {
            width: 63%;
            margin: 0 1.5%;
            height: 320px;
            background-image: url(//img.alicdn.com/tfs/TB1JW.0F.z1gK0jSZLeXXb9kVXa-1568-640.png);
            background-repeat: no-repeat;
            background-size: cover;
            position: relative;
          }
          .dig-campus {
            width: 30%;
            margin: 0 1.5%;
            height: 320px;
            background-image: url(//img.alicdn.com/tfs/TB1b3g1FYr1gK0jSZR0XXbP8XXa-766-640.png);
            background-repeat: no-repeat;
            background-size: cover;
            position: relative;
          }
          .dig-shop {
            width: 30%;
            margin: 0 1.5%;
            height: 320px;
            background-image: url(//img.alicdn.com/tfs/TB1lxw1F1T2gK0jSZFvXXXnFXXa-766-640.png);
            background-repeat: no-repeat;
            background-size: cover;
            position: relative;
          }
          .box {
            padding-right: 5%;
            box-sizing: border-box;
            position: absolute;
            top: 20px;
            left: 5%;
            color: white;
            font-size: 20px;
            .tit {
              font-size: 48px;
              margin: 20px 0;
            }
          }
          .more {
            position: absolute;
            left: 5%;
            bottom: 20px;
            font-weight: bold;
            font-size: 18px;
          }
        }
      }
    }
    .scure {
      width: 100%;
      margin-top: 80px;
      padding: 20px 0 80px 0;
      //   background: rgb(252, 225, 225);
      .scure-tit {
        width: 100%;
        text-align: center;
        .tit {
          font-size: 48px;
          font-weight: bold;
        }
        .content {
          text-align: center;
          font-size: 24px;
          p {
            margin: 10px 0;
          }
        }
      }
      .scure-cont {
        width: 100%;
        .cont-box {
          width: 30%;
          margin: 0 1.5%;
          //   background: rgb(252, 208, 208);
          .box-img {
            padding: 10px 25px;
          }
          .box-text {
            font-size: 20px;
            padding: 10px 25px;
            padding-top: 0;
            .box-tit {
              font-size: 36px;
              font-weight: bold;
            }
            .box-cont {
              margin-top: 20px;
              color: rgb(141, 139, 139);
            }
          }
        }
      }
    }
    .download {
      width: 100%;
      margin: 40px 0;
      height: 330px;
      background-image: url(https://img.alicdn.com/tfs/TB1gtTSGEY1gK0jSZFCXXcwqXXa-1440-319.png);
      background-repeat: no-repeat;
      background-size: cover;
      text-align: center;
      position: relative;
      padding: 40px 0;
      .dl-reg {
        padding-top: 80px;
      }
      .btn-box {
        width: 100%;
        margin: 0 auto;
        margin-top: 60px;
        .btn {
          margin: 0 20px;
          padding: 20px 60px;
          font-size: 24px;
          border-radius: 10px;
        }
        .dl {
          background: rgb(0, 94, 255);
          color: white;
          border: 3px solid rgb(0, 94, 255);
        }
        .reg {
          background: white;
          color: rgb(0, 94, 255);
          border: 3px solid rgb(0, 94, 255);
        }
      }
    }
  }
  .footer {
    width: 100%;
    background: rgb(246, 246, 246);
    position: relative;
    padding: 60px 0;
    .about-ding {
      font-size: 20px;
      text-align: left;
      padding-bottom: 60px;
      border-bottom: 1px solid rgb(90, 90, 90);
      .about-list {
        width: 10%;
        margin: 0 3%;
        .list-tit {
          font-weight: bold;
          margin-bottom: 30px;
        }
        .list-cont {
          color: rgb(199, 199, 199);
          &:hover {
            color: black;
          }
        }
      }
    }
    .cooperation {
      margin-top: 30px;
      text-align: left;
      padding: 0 3%;
      font-size: 20px;
      height: 50px;
      //   background: red;
      .enlarge {
        width: 20%;
        height: 50px;
        //   background: red;
        margin-left: 5%;
        .icon {
          margin: 0 2%;
          width: 20%;
          img {
            width: 100%;
          }
        }
      }
      .vision-box {
        width: 40%;
        height: 50px;
        position: absolute;
        text-align: right;
        right: 3%;
        .vision {
          height: 50px;
          margin: 0 1%;
          img {
            height: 50px;
          }
        }
      }
    }
    .offical-info {
      margin-top: 60px;
      font-size: 16px;
      text-align: left;
      margin-left: 3%;
      color: rgb(139, 139, 139);
      .business {
        margin-left: 5px;
      }
      .business-left {
        margin-left: 0;
      }
    }
    .copyright,
    .allowrance {
      text-align: left;
      font-size: 16px;
      color: rgb(139, 139, 139);
      margin-left: 3%;
    }
    .police {
      margin-top: 30px;
      font-size: 16px;
      color: rgb(139, 139, 139);
    }
  }
  .contect-us {
    position: fixed;
    right: 0;
    top: 60vh;
    width: 4%;
    background: rgb(0, 94, 255);
    font-size: 16px;
	box-sizing: border-box;
	padding: 30px 0;
	color: white;
	border-radius: 10px 0 0 10px;
    .img {
      width: 28px;
      height: 28px;
    }
    .box {
      width: 40%;
      margin: 0 30%;
    //   background: red;
    }
  }
}
.fl {
  float: left;
}
.fr {
  float: right;
}
.ib {
  display: inline-block;
}
li {
  list-style: none;
}
</style>