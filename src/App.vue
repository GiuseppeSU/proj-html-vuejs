<script>
import MyHeader from './components/MyHeader.vue';
import MyFooter from './components/MyFooter.vue';

export default {
  components: {
    MyHeader,
    MyFooter


  },
  data() {
    return {

    }

  },
  methods: {

  }

}

</script>

<template>
  <MyHeader></MyHeader>
  <!-- PRIMA SECTION -->
  <main>
    <section>
      <div class="container-main">
        <div class="container-left">
          <img class="book" src="../public/Books-icon.png" alt="Books">
          <div class="text">
            <h1>Thousands of courses for any type of student</h1>
            <p>At EduPrime, it doesn't matter what domain you wish to pursue a career in . Here you can find a course that
              satisfies your needs within a click away and applies for a course in a matter of minutes. EduPrime is ranked
              as
              the most versatile university in the world, thanks to the number of course it provides.</p>
            <button class="btn-yellow">Browse throught courses</button>
          </div>
        </div>
        <div class="container-right">
          <img class="graduation" src="../public/Graduation-Illustration.png" alt="Graduation">
          <img class="home" src="../public/home-background.png" alt="Home background">
        </div>
      </div>
    </section>

    <!-- FINE SECTION -->

    <!-- SECONDA SECTION -->
    <section class="faculties">
      <div class="title">
        <h1>Faculties available at EduPrime</h1>
        <p>A sigle university with a load of coursers,tailored to satisfy any student's needs</p>
      </div>

      <div class="container-box">
        <div class="box">
        </div>

        <div class="box">
          <img class="img" src="../public/Gavel-v2.png" alt="Gavel">
        </div>


        <div class="box">
          <img class="img" src="../public/Gavel-v2.png" alt="Gavel">

        </div>

        <div class="box">
          <img class="img" src="../public/Gavel-v2.png" alt="Gavel">

        </div>

        <div class="box">
          <img class="img" src="../public/Gavel-v2.png" alt="Gavel">

        </div>

        <div class="box">
          <img class="img" src="../public/Gavel-v2.png" alt="Gavel">

        </div>
      </div>

    </section>




    <!-- FINE SECONDA SECTION -->



  </main>

  <MyFooter></MyFooter>
</template>

<style scoped lang="scss">
@use './styles/general.scss';
@use './styles/partials/variables.scss';

.container-main {
  width: 75%;
  margin: auto;
  display: flex;
  justify-content: center;
  align-items: center;
}

.container-left {
  width: 70%;
  margin-top: 70px;

}

.book {
  height: 40px;
}

.text {
  margin: 20px 0px;
}

.text h1 {
  width: 55%;

}

.text p {
  margin-top: 20px;
  width: 80%;
}

.btn-yellow {
  background-color: variables.$bgcolor-yellow;
  border: none;
  border-radius: 20px;
  padding: 14px;
  color: white;
  font-size: 12px;
  width: 180px;
  margin-top: 30px;
}

.container-right {

  width: 30%;
  position: relative;
  height: 200px;
  display: flex;
  justify-content: end;

}

.graduation {
  margin-top: 20px;
  height: 300px;
  z-index: 999;
  position: absolute;
  right: 0px;



}

.home {
  height: 400px;
  position: absolute;

  top: -80px;

}

.title {
  margin-top: 50px;
  text-align: center;
}

.title p {
  width: 20%;
  margin: auto;
  margin-top: 30px;
  font-size: 15px;
}

.container-box {
  height: 200px;
  display: flex;



  width: calc(100% / 7);



  .box {

    border: 1px solid black;

  }

  .img {
    height: 200px;
    padding: 30px;



  }
}
</style>
