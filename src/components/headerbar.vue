<template>
  <div class="headerbar">
    <div class="reg-login">
      <div class="fr box company">企业登录</div>
      <div class="fr box login">下载钉钉</div>
      <div class="fr box reg">注册钉钉</div>
    </div>
    <div class="fl">
      <img src="@/assets/icon.png" alt />
    </div>

    <div class="fl func-list">
      <div class="func-item" v-for="(item,index) in flist" :key="index">{{item.text}}</div>
      <div class="func-item">
        简体中文
        <img class="arrow-down" src="@/assets/arrow-down.png" alt="选择语言" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "headerbar",
  data() {
    return {
      flist: [
        {
          text: "产品"
        },

        {
          text: "智能办公硬件"
        },
        {
          text: "钉钉直播间"
        },
        {
          text: "解决方案"
        },
        {
          text: "服务与支持"
        }
      ]
    };
  }
};
</script>

<style lang="less">
.headerbar {
  max-width: 1210px;
  width: 95%;
  margin: auto;
  height: 80px;
  text-align: left;
  align-items: center;
  //   background: rgb(205, 205, 255);

  //   功能按钮
  .func-list {
    font-size: 16px;
    color: black;
    height: 80px;
    // background: rgb(255, 197, 197);
    .func-item {
      display: inline-block;
      height: 20px;
      //   background: greenyellow;
      margin: 30px 10px;
      .arrow-down {
        background: rgb(206, 206, 206);
      }
    }
  }

  //登录注册
  .reg-login {
    font-size: 16px;
    .box {
      height: 20px;
      margin: 10px 5px;
      //   background: red;
      margin-right: 10px;
      padding: 20px 25px;
      border-radius: 40px;
    }
    .reg {
      background-color: white;
      border: 2px solid rgb(0, 94, 255);
    }
    .login {
      background-color: rgb(0, 94, 255);
      border: 1px solid rgb(0, 94, 255);
      color: white;
    }
  }
}
.fl {
  float: left;
}
.fr {
  float: right;
}
</style>