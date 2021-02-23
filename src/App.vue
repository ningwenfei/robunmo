<template>
  <div id="app">
    <div class="head content p-r">
      <div class="p-a l-0 t-0">
        <!-- <img width="13px" height="10px" src="./img/email.png" alt="邮箱"> -->
        <!-- <span style="marginLeft:8px">email: robunmo@outlook.com</span> -->
      </div>
      <div class="m-0a"><img style="margin-top:20px" src="./img/logo.png" alt=""></div>
    </div>
    <router-view />
    <!-- <div class="p-f b-0 l-o w_100"> -->
    <div class="w_100">
      <div class="trademark">
        <div class="content d-f jc-sb">
        <div class="ta-l">
          <p class="title fw-600"></p>
          <p>We are on Deliveroo, Justeat and Ubereats.</p>
        </div>
        <div class="d-f">
          <img width="55px" height="55px" style="margin-top:50px; margin-left: 21px" src="./img/f1.png" alt="">
          <img width="55px" height="55px" style="margin-top:50px; margin-left: 21px" src="./img/f2.png" alt="">
          <img width="55px" height="55px" style="margin-top:50px; margin-left: 21px" src="./img/f3.png" alt="">
        </div>
        </div>
      </div>
      <div class="foot c-f">
        <div class="content d-f jc-sb">
          <div></div>
          <div>
            <span>
              <img src="./img/email.png" alt="">
              email: robunmo@outlook.com
            </span>
            <span>
             follow us:  
             <a style="text-decoration: none; color: #fff;" href="https://www.instagram.com/robunmo?r=nametag" target="_blank" rel="noopener noreferrer">
              <img src="./img/follow.png" alt="">
               robunmo
            </a>
            </span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
