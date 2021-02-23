<template>
  <div class="detail-page">
    <div class="back c-f fs-36 ta-c p-r">
      <!-- <img src="../img/Vector.png" /> -->
      Menu
    </div>
    <div class="content p-r">
      <el-tabs @tab-click="handleClick" tab-position="left" class="tabs ta-l">
        <el-tab-pane label="all（11）">
          <ul class="c-b detail-box">
            <li v-for="(item, i) in snacks" :key="i" class="list">
              <div class="d-f">
                <img :src="item.src" :alt="item.name" />
                <div class="p-r">
                  <div class="fs-20 fw-600 c-3">{{ item.name }}</div>
                  <div class="fs-14 li-detail">{{ item.detail }}</div>
                  <div class="p-a b-0 fs-14 c-6">{{ item.Allergens }}</div>
                </div>
              </div>
            </li>
          </ul>
          <div class="c-b detail-box">
            <div class="list">
              <div class="d-f">
                <img src="../img/bao.png" />
                <div class="p-r">
                  <div class="fs-20 fw-600 c-3">Bao Bun</div>
                  <div class="fs-14 li-detail">
                    A type of yeast-leavened filled bun in various Chinese
                    cuisines. There are many variations in fillings (meat or
                    vegetarian).
                    <p>Available now:</p>
                    <p>
                      BBQ Pork, Teriyaki Chicken, vegetarian, Pork with Chinese
                      leaves, and Chicken & Mushroom.
                    </p>
                  </div>
                  <div class="p-a b-0 fs-14 c-6">Allergens: Gluten</div>
                </div>
              </div>
            </div>
            <div class="list">
              <div class="d-f">
                <img src="../img/robunmo.png" />
                <div class="p-r">
                  <div class="fs-20 fw-600 c-3">Robunmo</div>
                  <div class="fs-14 li-detail">
                    A handmade Chinese bun stuffed with slow cooked meat and
                    pepper, spring onion. It is so called ‘Chinese Hamburger’.
                    <div>Available now:</div>
                    Beef and Chicken.
                  </div>
                  <div class="p-a b-0 fs-14 c-6">
                    Allergens: Celery, Gluten, Soybeans
                  </div>
                </div>
              </div>
            </div>
          </div>

          <ul class="c-b detail-box">
            <li v-for="(item, i) in dishes" :key="i" class="list">
              <div class="d-f">
                <img :src="item.src" :alt="item.name" />
                <div class="p-r">
                  <div class="fs-20 fw-600 c-3">{{ item.name }}</div>
                  <div class="fs-14 li-detail">{{ item.detail }}</div>
                  <div class="p-a b-0 fs-14 c-6">{{ item.Allergens }}</div>
                </div>
              </div>
            </li>
          </ul>
        </el-tab-pane>
        <el-tab-pane label="Snacks（3）">
          <ul class="c-b detail-box">
            <li v-for="(item, i) in snacks" :key="i" class="list">
              <div class="d-f">
                <img :src="item.src" :alt="item.name" />
                <div class="p-r">
                  <div class="fs-20 fw-600 c-3">{{ item.name }}</div>
                  <div class="fs-14 li-detail">{{ item.detail }}</div>
                  <div class="p-a b-0 fs-14 c-6">{{ item.Allergens }}</div>
                </div>
              </div>
            </li>
          </ul>
        </el-tab-pane>
        <el-tab-pane label="Bao Bun">
          <div class="c-b detail-box">
            <div class="list">
              <div class="d-f">
                <img src="../img/bao.png" />
                <div class="p-r">
                  <div class="fs-20 fw-600 c-3">Bao Bun</div>
                  <div class="fs-14 li-detail">
                    A type of yeast-leavened filled bun in various Chinese
                    cuisines. There are many variations in fillings (meat or
                    vegetarian).
                    <p>Available now:</p>
                    <p>
                      BBQ Pork, Teriyaki Chicken, vegetarian, Pork with Chinese
                      leaves, and Chicken & Mushroom.
                    </p>
                  </div>
                  <div class="p-a b-0 fs-14 c-6">Allergens: Gluten</div>
                </div>
              </div>
            </div>
          </div>
        </el-tab-pane>
        <el-tab-pane label="Robunmo">
          <div class="c-b detail-box">
            <div class="list">
              <div class="d-f">
                <img src="../img/robunmo.png" />
                <div class="p-r">
                  <div class="fs-20 fw-600 c-3">Robunmo</div>
                  <div class="fs-14 li-detail">
                    A handmade Chinese bun stuffed with slow cooked meat and
                    pepper, spring onion. It is so called ‘Chinese Hamburger’.
                    <div>Available now:</div>
                    Beef and Chicken.
                  </div>
                  <div class="p-a b-0 fs-14 c-6">
                    Allergens: Celery, Gluten, Soybeans
                  </div>
                </div>
              </div>
            </div>
          </div>
        </el-tab-pane>
        <el-tab-pane label="Main Dishes（6）">
          <ul class="c-b detail-box">
            <li v-for="(item, i) in dishes" :key="i" class="list">
              <div class="d-f">
                <img :src="item.src" :alt="item.name" />
                <div class="p-r">
                  <div class="fs-20 fw-600 c-3">{{ item.name }}</div>
                  <div class="fs-14 li-detail">{{ item.detail }}</div>
                  <div class="p-a b-0 fs-14 c-6">{{ item.Allergens }}</div>
                </div>
              </div>
            </li>
          </ul>
        </el-tab-pane>

        <el-tab-pane class="to-home" label="Back To Home"></el-tab-pane>
      </el-tabs>
    </div>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from "vue-property-decorator";
import sweet from "../img/1.png";
import chicken from "../img/2.png";
import spicy from "../img/3.png";
import sauce from "../img/4.png";
import noodle from "../img/5.png";
import beef from "../img/6.png";
import springRoll from "../img/spring_roll.jpg";
import salt from "../img/salt.jpg";
import friedGyoza from "../img/fried_gyoza.jpg";

@Component({
  components: {
    // HelloWorld
  },
})
export default class About extends Vue {
  // private handleClick() {

  // }
  private dishes = [
    {
      src: sweet,
      name: "Sweet Sour Chicken Hong Kong Style",
      detail:
        "Crispy chicken stir-fried balls in a sweet and sour scrumptious sauce with pineapple tubes. Served with steamed rice.",
      Allergens: "Allergens:  Egg, Gluten, Soybeans ",
    },
    {
      src: chicken,
      name: "Chicken Curry",
      detail:
        "Panko breaded chicken pie paired with exquisite curry sauce, offered on a base of steamed rice. ",
      Allergens: "Allergens:  Egg, Gluten, Soybeans ",
    },
    {
      src: spicy,
      name: "Spicy Chicken Szechuan",
      detail:
        "Balance of pleasantly sweet, savoury and hot flavours. Served with steamed rice.",
      Allergens: "Allergens:  Egg, Gluten, Soybeans ",
    },
    {
      src: sauce,
      name: "Chicken in Black Bean Sauce",
      detail:
        "Chicken stir-fry with vegetables along with a punch of fermented black beans. Served with steamed rice.",
      Allergens: "Allergens:  Egg, Gluten, Soybeans ",
    },
    {
      src: noodle,
      name: "Chicken Fried Noodle",
      detail: "Noodles topped with a saucy chicken and vegetable stir fry.",
      Allergens: "Allergens:  Egg, Gluten, Soybeans ",
    },
    {
      src: beef,
      name: "Beef in Hoi Sin Sauce",
      detail: "Slow cooked beef in Hoi Sin Sauce served with Japanese Ramen.",
      Allergens: "Allergens:  Egg, Gluten, Soybeans ",
    },
  ];
  private snacks = [
    {
      src: springRoll,
      name: "Vegetable Spring Rolls 5Pcs",
      Allergens: "Allergens: Gluten",
    },
    {
      src: salt,
      name: "Salt & Pepper Chicken Wings 3Pcs",
      Allergens: "Allergens: Gluten",
    },
    {
      src: friedGyoza,
      name: "Vegetable Fried Gyoza 5Pcs or Chicken Fried Gyoza 5Pcs",
      Allergens: "Allergens: Gluten",
    },
  ];
  private handleClick(tab: any, e: any) {
    if (tab.label === "Back To Home") {
      this.$router.push("/");
    }
  }
}
</script>
