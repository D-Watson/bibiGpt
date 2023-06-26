<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <div class="page">
    <div class="title">
      <h1>❃一键总结音视频内容❃</h1>
    </div>
    <div class="input">
      <input class="input-fit" placeholder="请输入视频url">
      <span class="text"> or </span>
      <button class="upload">➹上传文件</button>
    </div>
    <button class="submit">➳➳ 一键总结</button>
   <div class="summary">
      <div class="">
          
      </div>

   </div>
   
  </div>
</template>

<style scoped>
  .page{
    background-image: url('./assets/starry.jpg');
    background-size: cover;
    width: 100%;
    height: 100vh;
    display: flex;
    flex-direction: column;
    font-family:"Times New Roman";
    /* 上下居中 */
    /* justify-content: center; */
    /* 左右居中 */
    align-items: center;
  }
  .title{
    padding: 1.8em;
    font-size: 22px;
    color: white;
    display:flex;
    text-align: center;
    margin-top: 80px;
  }
  .input{
    display: flex;
    color: white;
  }
  .text{
    font-size: 30px;
    margin-left: 10px;
    margin-right: 10px;
  }
  .input-fit{
    height: 30px;
    width: 450px;
    border: 1px solid #ccc;
    border-radius: 16px;
    font-size: 20px;
    /* 上右下左 */
    padding: 10px 10px 10px 20px;
}
.upload{
  width: 150px;
  height: 50px;
  background-color:#FF5853;
  color: white;
  text-align: center;
  font-size: 22px;
  border-radius: 16px;
}
.submit{
  width: 350px;
  height: 50px;
  background-image: linear-gradient(to right, #FF5853, #EE7F10);
  color: white;
  text-align: center;
  font-size: 22px;
  border-radius: 16px;
  margin-top: 50px;
}
</style>
