<template>
  <div id="index">
    <div class="top">
      <h1 >沧海一粟</h1>
      <p>寄蜉蝣于天地,渺沧海于一粟</p>
    </div>
    <div class="nav">
      <ul>
        <li>首页</li>
        <li>时间轴</li>
        <li>标签</li>
        <li>关于</li>
        <li>检索</li>
      </ul>
    </div>
  </div>


</template>

<script>
export default {
  name: 'index',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
  *{
    padding: 0;
    margin: 0;

  }

 #index .top {
   height: 80px;
   color: azure;
   background-color: #0a0a0a;
   text-align: center;
   width: 100%;
}
#index .nav{
  height: 60px;
  width: 100%;
  background-color:#404040;
  text-align: center;
}
  #index .nav ul{
    display: block;
    list-style: none;
  }
  #index .nav ul li{
    color:white;
    float: left;
  }
</style>
