<template>
  <div class="about">
    <div class="about-head">
      <div class="content p-r ">
        <!-- <p style="padding-top:95px" class="c-f fw-600">Robunmo</p>
        <p class="c-f fw-600">Chinese street food</p> -->
        <img class="p-a" height="400px" width="100%" src="../img/robunmo.jpg" alt="">
      </div>
    </div>
    <div class="about-robunmo fs-14">
      <div class="content d-f jc-sb">
        <div class="ta-l fs-16" style="width: 465px;margin-top:190px">
          <h3>About</h3>
          <h3 class="title-robunmo">Robunmo</h3>
          <div>
            Robunmo is a typical Chinese street food takeaway.
            <div></div>
            Robunmo is a transliterated word of Chinese rougamo, which is a
            street food originating from the cuisine of Shanxi Province and
            consumed all over China. It means ‘meat in a bun’, which sort of
            makes it like what we’d think of as a hamburger and it is probably
            the world’s oldest hamburger, dates back to the Qin Dynasty
            (221BC-206BC).
          </div>
          <div style="margin-top:70px">
            Now, Robunmo brings this ancient oriental street food to UK along
            with well-known Chinese street food like Bao Bun, Spring Roll, Gyoza
            and more chicken and beef dishes.
          </div>
        </div>
        <img
          width="627px"
          height="400px"
          style="margin-top:190px"
          src="../img/h2.png"
          alt=""
        />
      </div>
    </div>
    <div class="checck">
      <div class="content">
        <div class="fs-36" style="margin-top:65px;margin-bottom:20px">Menu</div>
        <h3></h3>
        <ul class="c-b">
          <li><img src="../img/menu.png" alt="" /></li>
          <li><img src="../img/robunmo.png" alt="" /></li>
          <li><img src="../img/bao.png" alt="" /></li>
          <li><img src="../img/spring_roll.jpg" alt="" /></li>
          <li><img src="../img/salt.jpg" alt="" /></li>
          <li><img src="../img/fried_gyoza.jpg" alt="" /></li>
          <li><img src="../img/1.png" alt="" /></li>
          <li><img src="../img/2.png" alt="" /></li>
          <li><img src="../img/3.png" alt="" /></li>
          <li><img src="../img/4.png" alt="" /></li>
          <li><img src="../img/5.png" alt="" /></li>
          <li><img src="../img/6.png" alt="" /></li>
        </ul>
        <div @click="$router.push('/about')" class="button c-f c-p">
          View Menu
        </div>
      </div>
    </div>
    <div>
      <div class="content branches-box">
        <div class="d-f ta-l jc-sb">
          <div class="branches">
            <h3>Robunmo’s Locations</h3>
            <div>
              Robunmo aims to serve happy customers with high quality and
              affordable price and an authentic approach makes us the place to
              get Chinese street food in famous shopping malls.
            </div>
          </div>
          <div>
            <!-- <a  href="https://www.instagram.com/robunmo?r=nametag" target="_blank" rel="noopener noreferrer">
              <img class="d-b" style="margin-top:50px;margin-bottom:22px" width="144px" height="43px" src="../img/logo2.png" alt="">
            </a> -->
            <!-- <img width="144px" height="144px" src="../img/logo3.png" alt=""> -->
          </div>
        </div>
        <div class="d-f jc-sb foot-detail-box">
          <div class="p-r">
            <img
              class="p-a l-0 t-0 w_100 h_100"
              src="../img/logo4.png"
              alt=""
            />
            <div class="p-a">The Centre MK, near Gate 5, Milton Keynes, MK9 3ES</div>
          </div>
          <div class="p-r">
            <img
              class="p-a l-0 t-0 w_100 h_100"
              src="../img/logo5.png"
              alt=""
            />
            <div class="p-a">Centre Court Shopping, upper mall, Wimbledon, London, SW19 8YE</div>
          </div>
          <div class="p-r">
            <img
              class="p-a l-0 t-0 w_100 h_100"
              src="../img/logo6.png"
              alt=""
            />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
