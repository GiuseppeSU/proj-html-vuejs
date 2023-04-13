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
    <div class="container-fluid my_container mt-5">
        <div class="row justify-content-center">
            <div class="col-3 mt-5">
                <img class="w-50 mt-5" src="../../public/theme_eduprime_logo.png" alt="EduPrime logo">
                <p class="mt-4 ms_color">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ex recusandae, explicabo
                    porro a
                    voluptates rem
                    magnam provident voluptatibus quae aut perspiciatis quis iusto maxime quos saepe eligendi? Quam, optio
                    alias?</p>
                <i class="fa-brands fa-facebook-f m-1 ms_icon"></i>
                <i class="fa-brands fa-twitter m-1 ms_icon"></i>
                <i class="fa-brands fa-instagram m-1 ms_icon"></i>
            </div>
            <div class="col-2 mt-5 ms_color">
                <h4 class="mt-5">Get EduPrime</h4>
                <p>Request a website</p>
                <p>Browse themes</p>
                <p>Payment option</p>
                <p>Support System</p>
                <p>Checkout</p>
                <p>Purchase theme</p>

            </div>

            <div class="col-1 mt-5 ms_color">
                <h4 class="mt-5">Networking</h4>
                <p>Purchase theme</p>
                <p>Our Benefits</p>
                <p>Our team</p>
                <p>Our Service</p>
                <p>Other Product</p>
                <p>My account</p>

            </div>

            <div class="col-3 mt-5 ms_color position-relative ms-5">
                <input class="p-3 mt-4  w-50 my_border" type="text" placeholder="Search..">
                <i class="fa-solid fa-magnifying-glass my_icon"></i>
                <div class="text-center ms-5 mt-4 mb-2">Search categories</div>
                <button class="my_button m-1">ECONOMY</button>
                <button class="my_button m-1">DESIGN</button>
                <button class="my_button m-1">COACHING</button>
                <button class="my_button m-1">BUSINESS</button>
                <br>
                <div class=" text-end me-5 mt-1">
                    <button class="my_button m-1 ">MEDICINE</button>
                    <button class="my_button m-1 ">LAW</button>
                    <button class="my_button m-1 me-5 ">FITNESS</button>
                </div>
                <div class="text-center me-5 mt-3 ms_link">ModelThee.All right reserved</div>
                <div class="mt-5">
                    <i class="fa-solid fa-chevron-up my_icon2"></i>
                </div>
            </div>
        </div>
    </div>
</template>


<style lang="scss" scoped>
@use '../styles/partials/variables.scss';
@use '../styles/general.scss';
@use 'bootstrap';



.my_container {
    background-color: variables.$bgcolor-red;
}

.ms_color {
    color: white;
}

.ms_icon {
    padding: 8px;
    border: 1px solid rgb(232, 193, 91);
    height: 30px;
    width: 30px;
    color: white;
    text-align: center;
    border-radius: 30px;
    font-size: 13px;
}

.my_border {
    border-radius: 30px;
    border: none;
    margin-left: 90px;
}

.my_icon {
    background-color: variables.$bgcolor-yellow;
    color: white;
    padding: 16px;
    border-radius: 30px;
    position: absolute;
    right: 110px;
    top: 25px;
}

.my_icon2 {
    background-color: variables.$bgcolor-yellow;
    color: white;
    padding: 10px;
    border-radius: 30px;
    position: absolute;
    right: 0px;
    bottom: 20px;
}

.my_button {
    border: 1px solid white;
    border-radius: 30px;
    padding: 8px;
    font-size: 10px;
    color: rgb(254, 250, 250);
    background-color: transparent;
}

.ms_link {
    color: variables.$bgcolor-yellow;
}

.my_container p {
    font-size: 13px;
    color: rgb(244, 189, 190);
}

.my_container button {
    color: rgb(244, 189, 190);
}
</style>