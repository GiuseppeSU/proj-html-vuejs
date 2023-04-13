<script>
export default {
    name: 'MyCourses'
}
</script>


<template>
    <div class="container">
        <h1 class="mb-3 mt-5">Latest Courses</h1>
        <div class="row">
            <div class="col">
                <div class="card mt-5 ms_card_color" style="width: 18rem;">
                    <img class=" w-50 m-auto" src="../../public/Decisions-icon.png" alt="Decision">
                    <div class="card-body">
                        <h5 class="card-title fw-bold ">Make better decision</h5>
                        <i class="fa-solid fa-user my_fs"></i>
                        <span class="my_fs ">Teacher:</span>
                        <span class="my_fs2 ">JamesCollins</span>
                        <br>
                        <i class="fa-solid fa-money-bill my_fs ms-1"></i>
                        <span class="my_fs ms-1">Price:</span>
                        <span class="my_fs2  ms-1">$21:00</span>
                        <br>
                        <a class=" btn my_color"><i class="fa-solid fa-eye me-1"></i>View Course</a>
                    </div>
                </div>
            </div>

            <div class="col">
                <div class="card mt-5 ms_card_color" style="width: 18rem;">
                    <img class=" w-50 m-auto" src="../../public/Speaker-icon.png" alt="Speaker">
                    <div class="card-body">
                        <h5 class="card-title fw-bold ">How to be a Speaker</h5>
                        <i class="fa-solid fa-user my_fs me-1"></i>
                        <span class="my_fs ms-1">Teacher:</span>
                        <span class="my_fs2 ms-1">JamesCollins</span>
                        <br>
                        <i class="fa-solid fa-money-bill my_fs ms-1"></i>
                        <span class="my_fs ms-1">Price:</span>
                        <span class="my_fs2 ms-1">Free</span>
                        <br>
                        <a class=" btn my_color"><i class="fa-solid fa-eye me-1"></i>View Course</a>
                    </div>
                </div>
            </div>

            <div class="col">
                <div class="card mt-5 ms_card_color" style="width: 18rem;">
                    <img class=" w-50 m-auto" src="../../public/Network-icon.png" alt="Network">
                    <div class="card-body">
                        <h5 class="card-title fw-bold ">Network Introduction</h5>
                        <i class="fa-solid fa-user my_fs"></i>
                        <span class="my_fs ms-1">Teacher:</span>
                        <span class="my_fs2 ms-1">JamesCollins</span>
                        <br>
                        <i class="fa-solid fa-money-bill my_fs ms-1"></i>
                        <span class="my_fs ms-1">Price:</span>
                        <span class="my_fs2 ms-1">Free</span>
                        <br>
                        <a class=" btn my_color"><i class="fa-solid fa-eye me-1"></i>View Course</a>
                    </div>
                </div>
            </div>

            <div class="col">
                <div class="card mt-5 ms_card_color" style="width: 18rem;">
                    <img class=" w-50 m-auto" src="../../public/Brand-icon.png" alt="Brand">
                    <div class="card-body">
                        <h5 class="card-title fw-bold ">Bramd Management</h5>
                        <i class="fa-solid fa-user my_fs"></i>
                        <span class="my_fs ms-1">Teacher:</span>
                        <span class="my_fs2 ms-1">JamesCollins</span>
                        <br>
                        <i class="fa-solid fa-money-bill my_fs ms-1"></i>
                        <span class="my_fs ms-1">Price:</span>
                        <span class="my_fs2  ms-1">Free</span>
                        <br>
                        <a class=" btn my_color"><i class="fa-solid fa-eye me-1"></i>View Course</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="container">
        <img class="ms_icon mt-5" src="../../public/Exam-icon.png" alt="">
        <div class="row">
            <div class="col-6">
                <h1 class=" my_big mt-4">The most efficient examination method</h1>
                <p class="mt-4">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ad accusamus fuga velit rerum
                    blanditiis,
                    perferendis optio placeat sit asperiores? Quidem odit aut aperiam, facere error accusantium corrupti ea
                    quaerat laborum.</p>
                <a class=" btn my_color2 mt-3">Discover the Method</a>
            </div>
            <div class="col-6 d-flex align-items-center">
                <img class="w-75  m-auto" src="../../public/Exam-Illustration.png" alt="Exam Illustration">
            </div>
        </div>
    </div>


    <div class="container mt-5 mb-5">
        <div class="row">
            <div class="col-6 d-flex align-items-center">
                <img class="w-75  m-auto" src="../../public/Girl-Illustration.png" alt="Exam Illustration">
            </div>
            <div class="col-6">
                <img class="ms_icon " src="../../public/Exam-icon-1.png" alt="Exam Icon">
                <h1 class=" my_big mt-4">Variable fees for International students</h1>
                <p class="mt-4">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ad accusamus fuga velit rerum
                    blanditiis,
                    perferendis optio placeat sit asperiores? Quidem odit aut aperiam, facere error accusantium corrupti ea
                    quaerat laborum.</p>
                <a class=" btn my_color3 mt-3">List of fees</a>
            </div>
        </div>
    </div>
</template>


<style lang="scss" scoped>
@use '../styles/partials/variables.scss';
@use '../styles/general.scss';
@use 'bootstrap';

.my_fs {
    font-size: 13px;
    color: rgb(171, 172, 179);
}


.my_fs2 {
    font-size: 13px;

}

.my_color {
    background-color: variables.$bgcolor-salmon;
    border-radius: 20px;
    padding: 7px;
    border: none;
    color: white;
    width: 150px;
}

.my_color2 {

    background-color: variables.$bgcolor-salmon;
    border-radius: 20px;
    padding: 10px;
    border: none;
    color: white;
    width: 180px;
}

.my_color3 {

    background-color: variables.$bgcolor-salmon;
    border-radius: 20px;
    padding: 10px;
    border: none;
    color: white;
    width: 130px;
}


.ms_card_color {
    border: 1px solid rgb(209, 209, 214);
    padding: 20px;
    border-radius: 20px;
}

.ms_icon {
    width: 80px;
}

.my_big {
    font-size: 60px;
}
</style>