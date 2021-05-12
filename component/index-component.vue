<template>
    <div class="main">
        <div class="head">
            <div class="flex">
                <img class="logo" src="https://img.wenhairu.com/images/2021/05/12/aTZqP.png" alt="">
                <ul class="tab">
                  <li class='tab0' @click="goHome">首页</li>  
                  <li @click="handleClick">资金池</li>  
                </ul>
            </div>
             <img class="cn-en" src="../img/cn-en@2x.png" alt="">
        </div>
        <div class="content">
            <h1 class="title">XDOG</h1>
            <h2>PROJECT BRIEF</h2>
            <h3>2021年以“狗狗币”为代表的宠物系列代币崛起，去中心化分布式自治组织再次触及人们内心深处，掀起浪潮般的新社会实践。XDOG狗王币DAO组织应运而生，做为时代潮流趋势的倡导者，致力于传播金融正念。<br>
            鉴于目前去中心化链与链之间，跨链繁琐复杂，XDOG的科学家们正在努力解决跨链资产管理，打造资产秒跨链协议，未来XDOG将用于结算跨链费用、合约保险、DeFi激励等一系列跨链金融资产的润滑剂。<br>
            XDOG狗王币DAO组织不仅拥有顶级域名（xdog.dog），还有独创的DeFi签到打卡挖矿激励，极致的交易燃烧通缩机制，零预挖、全流通、DAO社区自治。这是一次伟大的社会实践，更是探索人类文明，促进人与人之间增加信任的基石。</h3>
        </div>
        <div class="btn">
           <img class="handle" src="../img/btn@2x.png" alt="" @click="handleClick">
        </div>
    </div>
</template>
 
<script>
module.exports = {
  data: function() {
    return {};
  },
  methods: {
    goHome() {},
    handleClick() {
      window.location.href = 'recharge.html'
    },
  },
};
</script>
 
<style>
.main {
  height: 100%;
  width: 100%;
  background: url("../img/bgc.png") no-repeat center;
  background-size: cover;
}
.head {
  width: 100%;
  height: 120px;
  display: flex;
  justify-content: space-between;
  background-color: rgba(255, 255, 255, 0.1);
  padding: 0 100px 0 120px;
  box-sizing: border-box;
}
.logo {
  width: 80px;
  height: 80px;
  margin-top: 20px;
}
.tab {
  display: flex;
  justify-content: space-around;
  padding-top: 28px;
}
.tab li {
  list-style: none;
  height: 35px;
  width: 100px;
  text-align: center;
  line-height: 35px;
  border-radius: 3px;
  color: white;
}
.tab0 {
  background-color: #D4341F;
}
.cn-en {
  height: 40px;
  float: right;
  margin-top: 40px;
}
.flex{
    display: flex
}
.content{
    color: white;
    width: 52%;
    padding-left: 88px;
    margin-top: 70px;
    margin-bottom: 100px;
}
h1{
    color: #D4341F;
    font-size: 70px;
    font-weight: 500;
    text-align: right;
    width: 420px
}
h2{font-size: 40px;margin-bottom: 28px !important;letter-spacing: 8px;width: 420px}
h3{font-size: 12px;margin-bottom: 140px;line-height: 20px;}
.btn{
    text-align: center;
    width: 100%;
}
.handle{
    height: 86px;
}
h1,h2,h3{margin: 0}
</style>