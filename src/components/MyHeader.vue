<script>
export default {
    name: 'MyHeader',

    data() {
        return {

        }

    },
    methods: {

    }
}
</script>

<template>
    <div class="container">
        <div class="header">
            <img class=ms_foto src=" ../../public/theme_eduprime_logo.png" alt="">
            <ul>
                <li>Home<i class="fa-solid fa-caret-down"></i></li>
                <li>Courses<i class="fa-solid fa-caret-down"></i></li>
                <li>About Us</li>
                <li>News<i class="fa-solid fa-caret-down"></i></li>
                <li>Pages<i class="fa-solid fa-caret-down"></i></li>
                <li class="">Contact</li>
                <li class="">Purchase</li>
                <button class="btn-navbar">VIEW COURSES</button>
            </ul>
        </div>

        <div class="text">
            <h1>Key to your sucess</h1>
            <p>EduPrime is the most versatile WordPress theme for educational pirposes,showcasing
                universities,courses,secondary schol etc.</p>
        </div>
        <div class="btns">
            <button class="btn-yellow"><i class="fa-solid fa-magnifying-glass"></i>VIEW COURSES</button>
            <button class="btn-white"><i class="fa-solid fa-user-plus"></i>Apply for universities</button>
        </div>
        <div class="wave">
            <img src="../../public/Wave-1.png" alt="wave">
        </div>

    </div>
</template>


<style lang="scss">
@use '../styles/partials/variables.scss';


.container {

    background-image: url(../../public/theme_slider2_bg-1.jpg);
    background-size: cover;
    background-color: variables.$bgcolor-salmon;
    height: 550px;
    position: relative;


    .header {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    .ms_foto {
        height: 50px;
        margin-left: 30px;

    }

    ul {
        color: white;
        display: flex;
        list-style: none;

    }

    li {
        margin-left: 15px;
        margin-top: 10px;
    }

    i {
        margin-left: 5px;
    }

    li:hover {
        color: variables.$bgcolor-yellow;
        cursor: pointer;

    }

    .btns {
        text-align: center;
        margin-top: 30px;
    }

    .btn-navbar {
        background-color: variables.$bgcolor-yellow;
        border: none;
        margin-left: 20px;
        border-radius: 20px;
        padding: 14px;
        color: white;
        font-size: 12px;
        width: 150px;
        margin-right: 30px;

    }

    .btn-yellow {
        background-color: variables.$bgcolor-yellow;
        border: none;
        border-radius: 20px;
        padding: 14px;
        color: white;
        font-size: 12px;
        width: 150px;
        margin-right: 30px;

        i {
            margin-right: 10px;
        }
    }


    .btn-white {
        background-color: variables.$bgcolor-white;
        border: none;
        margin-left: 10px;
        border-radius: 20px;
        padding: 14px;
        color: variables.$bgcolor-salmon;
        font-size: 12px;
        width: 170px;

        i {
            margin-right: 10px;
        }


    }


    .text {
        color: white;
        text-align: center;
    }

    .text p {
        width: 27%;
        margin: auto;
    }


    .wave {
        position: absolute;
        bottom: -5px;
        left: 0;
    }


}
</style>