<template>
 <div class="footer">
   <div class="footer-logo">
     <img src="/imgs/logo-footer.png" alt="">
     <p>小米商城</p>
   </div>
   <div class="footer-link">
     <a href="javascript:;">Cmotal主页</a> <span>|</span>
     <a href="javascript:;">Vue项目</a> <span>|</span>
     <a href="javascript:;">React项目</a> <span>|</span>
     <a href="javascript:;">微信支付项目</a> <span>|</span>
   </div>
   <div class="copyright">Copyright ©2019 <span class="domain">mi.futurefu.com</span> All Rights Reserverd.</div>
 </div>
</template>

<script>
export default {
  name: 'nav-footer'
}
</script>

<style lang="scss" scoped>
@import '../assets/scss/config.scss';

.footer{
  height: 234px;
  border-top: 4px solid  $colorA;
  background-color: $colorB;
  color: $colorD;
  font-size: 16px;
  text-align: center;
  .footer-logo{
    margin-top: 46px;
    margin-bottom: 31px;
    img{
      width: 53px;
      height: 36px;
      margin-bottom: 13px;
    }
  }
  .footer-link{
    margin-bottom: 13px;
    a{
      color: $colorD;
      display: inline-block;
    }
    span{
      margin: 0 10px;
    }
  }
  .copyright{
    .domain{
      color: $colorA;
    }
  }
}
</style>
