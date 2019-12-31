<template>
    <div class="newFooter">
      <div class="footContent">
        <div class="footItem1">
        </div>
        <div class="footItem2">

        </div>
        <div class="footItem3">
        </div>
      </div>
      <div class="footCopy">
        © 推荐系统
        <br><br><br><br><br><br><br><br><br><br>
      </div>
    </div>
</template>

<script>
export default {
  name: 'newFooter'
}
</script>

<style lang="less" scoped>
  /*common style*/
  a{
    color:#777
  }
  a:hover{
    color:#333
  }
  .newFooter{
    display: flex;
    flex-flow: column;
    width: 100%;
    background: #f5f6f5;
    font-size: 12px;
    color: #777;
    .footContent{
      width: 100%;
      display: flex;
      justify-content: space-around;
      padding: 0 4%;
      box-sizing: border-box;
      .footItem1,.footItem2,.footItem3{
        width: 30%;
        padding:20px 5%;
        text-align: center;
        box-sizing: border-box;
        &>h3{
          margin-bottom:10px;
          display: inline-block;
          width: 100%;
        }
      }
      .footItem2>img{
        width: 50%;
      }
      .footItem1>ul li,.footItem3>ul li{
        margin-top:10px;
        margin-left: -10px;
      }
    }
    .footCopy{
      width: 100%;
      text-align: center;
      margin-top: 20px;
      margin-bottom: 15px;
    }
  }
</style>
