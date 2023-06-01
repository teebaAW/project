<script setup>
import backgroundIMg from "../assets/background.webp";
import image from "../assets/image.jpg";
import house from "../assets/house.png";
import pictureOne from "../assets/picture-one.png";
</script>

<template>
  <div>
    <div class="section-one">
      <div class="box-one">
        <div class="description-side">
          <p>
            Take control of your home's power usage with smart electricals. From
            smart plugs to advanced power strips, you can easily monitor and
            control the energy usage of all your electronic devices. Plus, with
            energy-saving features and real-time monitoring, you can save money
            on your energy bills and reduce your carbon footprint.
          </p>
        </div>
        <div class="image-side"><img :src="house" alt="" /></div>
      </div>
    </div>
    <div class="section-two">
      <h1 class="title">Products</h1>
      <div class="content">
        <div class="box-one">
          <!-- <h1>Header</h1>
          <p>
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Modi saepe
            laborum dolorum, adipisci ab, unde aliquid ducimus porro magni
            inventore doloribus numquam at dolores quam expedita aspernatur
            incidunt cupiditate culpa?
          </p> -->
        </div>
        <div class="box-one">
          <!-- <h1>Header</h1>
          <p>
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Modi saepe
            laborum dolorum, adipisci ab, unde aliquid ducimus porro magni
            inventore doloribus numquam at dolores quam expedita aspernatur
            incidunt cupiditate culpa?
          </p> -->
        </div>
        <div class="box-one">
          <!-- <h1>Header</h1>
          <p>
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Modi saepe
            laborum dolorum, adipisci ab, unde aliquid ducimus porro magni
            inventore doloribus numquam at dolores quam expedita aspernatur
            incidunt cupiditate culpa?
          </p> -->
        </div>
      </div>
    </div>
    <div class="section-three">
      <div class="content">
        <div class="">
          <img :src="pictureOne" alt="" />
        </div>
        <div class="section-three-description">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea suscipit
          perferendis debitis. Ipsa corporis sed, perspiciatis molestiae fugit
          hic velit tenetur, ducimus minima consequuntur voluptatem. Amet ab
          mollitia dicta? Fuga!
        </div>
      </div>
    </div>
  </div>
  <div class="section-four"></div>
</template>

<style>
.container {
  max-width: 1200px;
  margin: auto;
}
.section-one {
  background-color: #005ad5;
  background-size: cover;
  background-position: center;
  height: 800px;
  width: 100%;
  clip-path: polygon(0 0, 100% 0%, 100% 58%, 0 81%);
  padding-top: 100px;
}

.section-one .box-one {
  color: rgb(159, 165, 42);
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.image-side img {
  width: 80%;
  justify-items: center;
  height: 100%;
}

.image-side {
  display: flex;
  justify-content: center;
  display: flex;
  justify-content: center;
  width: 50%;
  justify-items: center;
}

.description-side {
  margin-left: 90px;
  color: aliceblue;
  margin-right: 90px;
  width: 50%;
  font-size: larger;
}

.description-side {
  font-size: larger;
}

.section-two .title {
  display: flex;
  justify-content: center;
  justify-items: center;
  margin-bottom: 60px;
  font-size: 50px;
}
.content {
  height: 500px;
  display: flex;
  margin-left: 20px;
  margin-right: 20px;
  gap: 20px;
}

.content .box-one {
  background-color: #f4f6f7;
  border: 1px solid rgb(240, 230, 230);
  width: 200px;
  height: 400px;
  flex: 1;
  margin: 0 10px;
}

.content .box-one h1 {
  display: flex;
  justify-content: center;
  margin-bottom: 100px;
}
.section-three {
  height: 500px;
  width: 100%;
  background-color: #f4f6f7;
}
.section-three .content {
  padding-top: 100px;
}
.section-three .content .box-one {
  padding-top: 100px;
}
.section-three-description {
  width: 600px;
  margin-left: 100px;
  margin-top: 100px;
  font-size: 20px;
}
.section-four {
  width: 400px;
  height: 400px;
}
</style>
