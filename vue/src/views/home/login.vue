<template>
  <div class="denglu">
      11111111
      <h1>圈子登陆</h1>
     <div class="box">
      <input type="text" placeholder="用户名"><br>
      <input type="password" placeholder="密码"><br>
      <button @click="Dengclick()">登陆</button><br>
      <a href="register">没有账号,快速注册</a>

     </div>
  </div>
</template>

<script>
export default {
    data() {
        return {
            
        }
    },
    methods: {
        Dengclick(){
            location.href="/home"
        }
    },
}
</script>

<style lang="scss" >
    *{
        margin: 0;
        padding: 0;
        list-style: none;
    }
    .denglu{
        width: 100%;
        height: 100%;
    }
    h1{
        width: 100%;
        height: 50px;
        line-height: 50px;
        font-size: 20px;
        text-align: center;
    }
   .box{
       width: 100%;
   }
   
    input{
        width: 95%;
        height: 40px;
        margin-left: 2.5%;
      }
    button{
        width: 95%;
        height: 50px;
        background: #f76968;
        margin-left: 2.5%;
    }
    a{
        margin-top: 10px;
        font-size: 16px;
        color: #000;
    }
</style>