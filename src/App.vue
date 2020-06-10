<!--<template>-->
  <!--<div id="app">-->
    <!--<div id="nav">-->
      <!--<router-link to="/">Home</router-link> |-->
      <!--<router-link to="/about">About</router-link>-->
    <!--</div>-->
    <!--<router-view/>-->
  <!--</div>-->
<!--</template>-->

<!--<style>-->
<!--#app {-->
  <!--font-family: 'Avenir', Helvetica, Arial, sans-serif;-->
  <!-- -webkit-font-smoothing: antialiased;-->
  <!-- -moz-osx-font-smoothing: grayscale;-->
  <!--text-align: center;-->
  <!--color: #2c3e50;-->
<!--}-->
<!--#nav {-->
  <!--padding: 30px;-->
<!--}-->

<!--#nav a {-->
  <!--font-weight: bold;-->
  <!--color: #2c3e50;-->
<!--}-->

<!--#nav a.router-link-exact-active {-->
  <!--color: #42b983;-->
<!--}-->
<!--</style>-->
<template>
    <div id="app">
        <div id="left">
            <ul>正义的鱼人
                <li></li>
                <li>猎潮</li>
                <li>石塘</li>
                <li>领军</li>
                <li>瞎眼</li>
            </ul>
        </div>
        <div id="top">wrl
            <div id="right">
                <img src="../public/寒光.jpg" alt="">
            </div>
        </div>
    </div>
</template>

<style>
    *{
        background-color: gray;
        padding: 0px;
        margin: 0px;
    }
    #left{
        float: left;
        margin: 5px 50px;
    }
    #top{
        float: left;
        margin: 5px;
    }
    #top img{
        width: 1000px;
        height: 500px;
    }
    li{
        list-style: none;
        cursor: pointer;
    }
</style>


