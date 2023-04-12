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
        <div class="row">
            <div class="col-5">
                <img class=ms_foto src="../../public/theme_eduprime_logo.png" alt="">

            </div>
            <div class="col-7 d-flex ">
                <ul class=" list-unstyled d-flex align-items-center mt-2">
                    <li>Home<i class="fa-solid fa-caret-down ms-2 me-4"></i></li>
                    <li>Courses<i class="fa-solid fa-caret-down ms-2 me-4"></i></li>
                    <li>About Us</li>
                    <li>News<i class="fa-solid fa-caret-down ms-2 me-4"></i></li>
                    <li>Pages<i class="fa-solid fa-caret-down ms-2 me-4"></i></li>
                    <li class="me-4">Contact</li>
                    <li class="me-4">Purchase</li>
                </ul>
                <img class=ms_button src="../../public/hover-button-4.png" alt="Button">
            </div>
        </div>
    </div>
</template>


<style lang="scss">
@use '../styles/partials/variables.scss';
@use 'bootstrap';

.container {
    background-color: variables.$bgcolor-salmon;



    .ms_foto {
        height: 50px;
    }


    .ms_button {
        height: 50px;



    }

    ul {
        color: white;
    }

    li:hover {
        color: yellow;
        cursor: pointer;

    }


}
</style>