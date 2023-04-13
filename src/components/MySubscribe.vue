<script>
export default {
    name: 'MySubscribe'
}
</script>


<template>
    <div class="container-fluid  my_bgcolor">
        <div class="row">
            <div class="col-7 text-center p-4 ">
                <h1>Subscribe now to Our Newsletter!</h1>
            </div>
            <div class="col-5 position-relative">
                <input class="p-3 mt-4 w-75 my_border" type="text" placeholder="Email Address...">
                <i class="fa-solid fa-paper-plane my_icon"></i>
            </div>
        </div>
    </div>

    <div class="container-fluid mt-5 text-center position-relative">
        <h1>Partners</h1>
        <p class="w-25 m-auto">Leverage agile frameworks to provide a robust synopsis for high level
            overviws,iterative
            approaches to
            corporate strategy</p>
        <div class="row mt-5 justify-content-center">
            <div class="col-1">
                <img class="my_img w-100" src="../../public/partner-2.png" alt="Partner 2">
            </div>
            <div class="col-1">
                <img class="my_img" src="../../public/partner-3.png" alt="Partner 2">
            </div>
            <div class="col-1">
                <img class="my_img " src="../../public/partner-4.png" alt="Partner 2">
            </div>
            <div class="col-1">
                <img class="my_img w-100" src="../../public/partner-5.png" alt="Partner 2">
            </div>
            <div class="col-1">
                <img class="my_img" src="../../public/partner-6.png" alt="Partner 2">
            </div>
            <div class="col-1">
                <img class="my_img" src="../../public/partner-8.png" alt="Partner 2">
            </div>
            <div class="col-1">
                <img class="my_img" src="../../public/partner-1.png" alt="Partner 2">
            </div>
            <div class="col-1">
                <img class="my_img w-100" src="../../public/partner-7.png" alt="Partner 2">
            </div>
        </div>
        <img class="ms_wave " src="../../public/background-wave3.png" alt="wave">

    </div>
</template>



<style scoped lang="scss">
@use '../styles/partials/variables.scss';
@use '../styles/general.scss';
@use 'bootstrap';

.my_bgcolor {
    background-color: variables.$bgcolor-red;
}

.my_bgcolor h1 {
    color: white;

}

.ms_navbarcolor {
    background-color: white;

}

.my_color {
    color: rgb(183, 183, 183);
}

.my_border {
    border-radius: 30px;
    border: none;
}

.my_icon {
    background-color: variables.$bgcolor-yellow;
    color: white;
    padding: 16px;
    border-radius: 30px;
    position: absolute;
    right: 173px;
    top: 25px;
}

.my_img {
    width: 60px;
    color: rgb(179, 179, 179);
}

.ms_wave {
    width: 100%;
    rotate: 180deg;
    background-color: rgb(247, 248, 250);
    height: 100px;
    position: absolute;
    right: 0px;
}
</style>