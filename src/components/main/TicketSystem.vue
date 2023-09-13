<template>
    <header>
        <div class="header_left">
            <div class="logo"></div>
            <div class="city"></div>
        </div>
        <div class="header_right">
            <div class="search"></div>
            <div class="person"></div>
        </div>
    </header>
        

    <div class="top">
      <div></div>
      <div></div>
      <div></div>
      <div></div>
      <div></div>
      <div></div>
      <div></div>
      <div></div>
    </div>
    <div class="main">
        <div class="main_type">
            <ul>
            <li class="piece1">
                <div class="left"></div>
                <div class="right"></div>
            </li>
            <li class="piece2">
                <div class="left"></div>
                <div class="right"></div>
            </li>
            <li class="piece3">
                <div class="left"></div>
                <div class="right"></div>
            </li>
            <li class="piece4">
                <div class="left"></div>
                <div class="right"></div>
            </li>
            <li class="piece5">
                <div class="left"></div>
                <div class="right"></div>
            </li>
            <li class="piece6">
                <div class="left"></div>
                <div class="right"></div>
            </li>
            <li class="piece7">
                <div class="left"></div>
                <div class="right"></div>
            </li>
        
        </ul>
        </div>
       
    </div>
    <footer class="foot"></footer>
  </template>
  
  <script>
  
  </script>
  
  <style scoped>
  *{
    margin:0px;
    padding:0px;
  }
  p,h1,h2,h3,h4,h5,h6,dl,dt,dd,ol,ul,li{margin:0px;padding:0px;}
  li{list-style:none;}
  div{
    display:block;
  }
  header {
    height:40px;
    background:yellow;
    overflow:auto;
  }
  header >div{
    background:pink;
    width:300px;
    height:40px;
    float:left;
    margin-left:397px;

  }
  .header_left{
    margin-left:80px;

  }
   /* .header_right{
    margin-right:80px;
    
  }  */
  .logo{
    background:skyblue;
    height:40px;
    width:150px;
    float:left;
  }
  .city{
    background:rgb(64, 12, 12);
    height:40px;
    width:150px;
    float:left;
  }
  .search{
    background:rgb(200, 119, 48);
    height:40px;
    width:150px;
    float:left;
  }
  .person{
    background:rgb(76, 222, 238);
    height:40px;
    width:150px;
    float:left;
  }
  .top{
    height:45px;
    background: red;
  }
  .main{
    background:green;
    overflow:auto;
  }
  .main_type{
    width:1000px;
    float:left;
    margin:auto;
    background: blue;
    margin-left:80px;
  
  }
  .main ul{
    margin-top:25px;
    margin-bottom:25px;
  }
  .main ul li{
    background:pink;
    width: 940px;
    height: 290px;
    margin: auto;
    margin-top:20px;
    

  }
  
  .foot{
    height:150px;
    background:skyblue;
  }
  </style>