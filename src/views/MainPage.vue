<script setup>
import backgroundIMg from '../assets/background.webp';
import image from '../assets/image.jpg';
import house from '../assets/house.png';
import pictureOne from '../assets/picture-one.png';
</script>

<template>
  <div class="container">
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
      <div class="section-three-content">
        <div class="section-three-image">
          <img :src="pictureOne" alt="" />
        </div>
        <div class="section-three-description">
          <p>Lorem ipsum dolor sit amet consectetur adipisicing.</p>
        </div>
      </div>
    </div>
  </div>
  <div class="section-four"></div>
</template>

<style>
/*.section-one {
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
  justify-items: center;
}

.description-side {
  margin-left: 90px;
  color: aliceblue;
  margin-right: 90px;
  width: 50%;
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
  width: 300px;
  height: 400px;
  flex: 1;
  margin: 0 10px;
  flex-direction: row;
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
 */

.container {
}
.section-one {
  background-color: #005ad5;
  background-size: cover;
  background-position: center;
  height: 250px;
  width: 100%;
  clip-path: polygon(0 0, 100% 0%, 100% 79%, 0 100%);
  padding-top: 60px;
}
.section-one .box-one {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.description-side {
  font-size: 10px;
  margin-left: 10px;
  color: aliceblue;
  font-family: 'Times New Roman', Times, serif;
}

.image-side img {
  width: 200px;
}

.section-two {
  height: 1400px;
}
.section-two .title {
  display: flex;
  justify-content: center;
  justify-items: center;
  margin-bottom: 60px;
  font-size: 30px;
}

.section-two .content {
  height: 500px;
  display: flex;
  flex-wrap: wrap;
  margin-left: 20px;
  margin-right: 20px;
  gap: 20px;
  justify-content: center;
}

.section-two .content .box-one {
  background-color: #f4f6f7;
  border: 1px solid rgb(240, 230, 230);
  width: 300px;
  height: 400px;
  flex-direction: column;
}

.section-three {
  height: 300px;
  width: 100%;
}

.section-three-image {
  display: flex;
  justify-content: center;
}
.section-three-image img {
  width: 300px;
}

.section-three-description {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 10px;
}
.section-four {
  background-color: #d5e0ee;
  height: 200px;
}

@media screen and (min-width: 280px) and (max-width: 374px) {
  .description-side {
    font-size: 10px;
  }

  .image-side img {
    width: 150px;
  }
  .section-two .title {
    font-size: 20px;
  }
  .section-three-image {
    display: flex;
    justify-content: center;
  }
  .section-three-image img {
    width: 200px;
  }

  .section-three-description {
    font-size: 10px;
  }
}
@media screen and (min-width: 450px) and (max-width: 640px) {
  .description-side {
    font-size: 12px;
  }
}

@media screen and (min-width: 640px) {
  .description-side {
    font-size: 15px;
    margin-left: 10px;
    color: aliceblue;
    font-family: 'Times New Roman', Times, serif;
  }

  .image-side img {
    width: 300px;
  }
  .section-three {
    height: 300px;
    width: 100%;
  }

  .section-three-image {
    display: flex;
    justify-content: center;
  }
  .section-three-image img {
    width: 400px;
  }

  .section-three-description {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 15px;
  }
}

@media screen and (min-width: 664px) {
  .section-two {
    height: 1000px;
  }
}
</style>
