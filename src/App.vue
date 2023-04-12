<script>
import MyHeader from './components/MyHeader.vue';
import MyFooter from './components/MyFooter.vue';
import MyMain from './components/MyMain.vue';






export default {
  components: {
    MyHeader,
    MyFooter,
    MyMain




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
          <img class="img" src="../public/Gavel-v2.png" alt="Gavel">
          <h3>Low Faculty</h3>
          <i class="fa-solid fa-caret-down"></i>
        </div>



        <div class="box">
          <img class="img" src="../public/Coins-tabs-v2.png" alt="Coins">
          <h3>Economy</h3>

        </div>

        <div class="box">
          <img class="img" src="../public/Medicine-tabs-v2.png" alt="Medicine">
          <h3>Medicine</h3>

        </div>

        <div class="box">
          <img class="img" src="../public/Computer-tabs-v2.png" alt="Computer">
          <h3>Computer Science</h3>

        </div>

        <div class="box">
          <img class="img" src="../public/Palette-tabs-v2.png" alt="Palette">
          <h3>Graphic Design</h3>
        </div>
      </div>
    </section>
    <!-- FINE SECONDA SECTION -->

    <!-- TERZA SECTION -->
    <div class="hummer">
      <div class="hummer-left">
        <img class="martello" src="../public/Gavel-Illustration-e1556884768193.png" alt="">

      </div>
      <div class="hummer-right">
        <div class="hummer-text">
          <h1>Law Faculty</h1>
          <p>Learning from world-leading academics and practitioners, you'll not only receive an outstanding grounding in
            the theory of law, but you will be able to understand how those principles are applied in practice trough a
            range of student-led activities and competitions </p>
          <button>Read More</button>
        </div>
      </div>
    </div>
    <div class="container-red">
      <img class="wave-red" src="../public/svg-0.svg" alt="">
    </div>
    <!-- FINE TERZA SECTION -->
    <!--  QUARTA SECTION -->
    <MyMain></MyMain>
    <!-- FINE QUARTA SECTION -->
  </main>





  <MyFooter></MyFooter>
</template>

<style scoped lang="scss">
@use './styles/general.scss';
@use './styles/partials/variables.scss';

.container-main {
  width: 55%;
  margin: auto;
  display: flex;
  justify-content: space-around;
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
  width: 40%;

}

.text p {
  margin-top: 20px;
  width: 70%;
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

  height: 350px;
  z-index: 999;
  position: absolute;
  right: -100px;



}

.home {
  height: 500px;
  position: absolute;
  top: -50px;
  right: -368px;

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
  display: flex;
  border: 1px solid black;
  justify-content: center;
  align-items: center;
  margin-top: 20px;



  .box {
    border: 1px solid black;
    text-align: center;
    padding: 30px;
    position: relative;

  }

  .box i {
    position: absolute;
    bottom: -23px;
    font-size: 35px;
    left: 100px;
    color: variables.$bgcolor-salmon;
  }

  .box h3 {
    color: variables.$bgcolor-salmon;
  }

  .img {
    height: 150px;
    padding: 30px;

  }
}

.hummer {
  margin: 50px;
  display: flex;
  margin-left: 50px;

}

.hummer-left {
  width: 80%;
  display: flex;
  justify-content: center;

}



.martello {
  height: 200px;
}

.hummer-right {
  width: 70%;
  display: flex;
  justify-content: center;

}

.hummer-text p {
  margin-top: 20px;
  width: 60%;
}

.hummer-text button {
  padding: 20px;
  border-radius: 25px;
  border: none;
  background-color: variables.$bgcolor-salmon;
  color: white;
  margin-top: 20px;
  width: 150px;

}

.container-red {
  position: relative;
}

.wave-red {
  width: 100%;
  position: absolute;
  bottom: 0px;
}
</style>
