<template>
  <div class="about">
    <div class="about-head">
      <div class="content p-r ">
        <p style="padding-top:95px" class="c-f fw-600">Robunmo</p>
        <p class="c-f fw-600">Chinese street food</p>
        <img class="p-a" height="400px" src="../img/h1.png" alt="" />
      </div>
    </div>
    <div class="about-robunmo fs-14">
      <div class="content d-f jc-sb">
        <div class="ta-l" style="width: 465px;margin-top:190px">
          <h3>About</h3>
          <h3 class="title-robunmo">Robunmo</h3>
          <div>
            Robunmo is a typical Chinese street food takeaway, as trademark
            registered with Intellectual Property Office by Xu & Lee Catering
            <div></div>
            Ltd. Robunmo is a transliterated word of Chinese rougamo, which is a
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
        <img
          width="60px"
          height="68px"
          style="margin-top:65px;margin-bottom:20px"
          src="../img/logo1.png"
          alt=""
        />
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
          Checck All
        </div>
      </div>
    </div>
    <div>
      <div class="content branches-box">
        <div class="d-f ta-l jc-sb">
          <div class="branches">
            <h3>Robunmo’s Branches</h3>
            <div>
              Robunmo aims to serve happy customers with high quality and
              affordable price and an authentic approach makes us the place to
              get Chinese street food in famous shopping malls.
            </div>
          </div>
          <div>
            <div class="d-f" style="margin-top:50px;margin-bottom:22px">
              <img style="margin-right:18px" src="../img/logo2.png" alt="" />
              <div>
                <p class="c-6 fs-12">Follow Us</p>
                <p class="c-3 fs-18">robunmouk</p>
              </div>
            </div>
            <!-- <img class="d-b"  width="144px" height="43px" src="../img/logo2.png" alt=""> -->
            <img width="144px" height="144px" src="../img/logo3.png" alt="" />
          </div>
        </div>
        <div class="d-f jc-sb foot-detail-box">
          <div class="p-r">
            <img
              class="p-a l-0 t-0 w_100 h_100"
              src="../img/logo4.png"
              alt=""
            />
            <div class="p-a">The Centre MK, Milton Keynes</div>
          </div>
          <div class="p-r">
            <img
              class="p-a l-0 t-0 w_100 h_100"
              src="../img/logo5.png"
              alt=""
            />
            <div class="p-a">Centre Court Shopping, Wimbledon</div>
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
