<script>
export default {
    name: 'Mymain'
}
</script>

<template>
    <!-- QUARTA SECTION -->
    <section>
        <div class="università">
            <div class="uni-text">
                <img class="clock" src="../../public/Clock-and-Bell.png" alt="">
                <h1>University Year</h1>
            </div>

        </div>
        <div class="grafico-container">
            <div class="minitext">
                <h3>Demo Classes</h3>
                <p>In the First week, student try to accommodate with the teaching style and choose their optional coursers
                </p>
            </div>

            <div class="minitext2">
                <h3>Graduation Day</h3>
                <p>In the First week, student try to accommodate with the teaching style and choose their optional coursers
                </p>
            </div>
            <img class="grafico" src="../../public/Timeline-Item.png" alt="">

            <div class="minitext3">
                <h3>Orientation</h3>
                <p>In the First week, student try to accommodate with the teaching style and choose their optional coursers
                </p>
            </div>

            <div class="minitext4">
                <h3>Evolution</h3>
                <p>In the First week, student try to accommodate with the teaching style and choose their optional coursers
                </p>
            </div>
        </div>
    </section>
    <!-- FINE QUARTA SECTION -->
    <!-- QUINTA SECTION -->
    <section>
        <div class="eventi-container">
            <div class="box-eventi">
                <img class="clock" src="../../public/upcoming-events-calendar-icon.png" alt="">
                <h1>Upcoming Events</h1>
            </div>
            <div class="card-container">
                <div class="card">
                    <h1>Coaching Session</h1>
                    <i class="fa-solid fa-calendar-days"><span>20 May 21:30 PM</span></i>
                    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Incidunt ratione non delectus labore quis,
                        distinctio voluptates placeat harum neque ut quaerat odio dolorem laborum molestias repellendus?
                        Placeat
                        excepturi quo maiores?</p>
                    <button><i class="fa-solid fa-plus">Find More</i></button>

                </div>
                <div class="card">
                    <h1>Coaching Session</h1>
                    <i class="fa-solid fa-calendar-days"><span>20 May 21:30 PM</span></i>
                    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Incidunt ratione non delectus labore quis,
                        distinctio voluptates placeat harum neque ut quaerat odio dolorem laborum molestias repellendus?
                        Placeat
                        excepturi quo maiores?</p>
                    <button><i class="fa-solid fa-plus">Find More</i></button>

                </div>
                <div class="card">
                    <h1>Coaching Session</h1>
                    <i class="fa-solid fa-calendar-days"><span>20 May 21:30 PM</span></i>
                    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Incidunt ratione non delectus labore quis,
                        distinctio voluptates placeat harum neque ut quaerat odio dolorem laborum molestias repellendus?
                        Placeat
                        excepturi quo maiores?</p>
                    <button><i class="fa-solid fa-plus">Find More</i></button>
                </div>
            </div>
            <div class="btn">
                <button>View All Events</button>
            </div>

            <div class="wave-container">
                <img class="wave" src="../../public/Wave-1.png" alt="">
            </div>
        </div>
    </section>
    <!--FINE QUINTA SECTION -->
</template>


<style lang="scss">
@use '../styles/general.scss';
@use '../styles/partials/variables.scss';

.università {
    padding-top: 60px;
    background-color: rgb(229, 103, 104);
    display: flex;
    justify-content: center;
}

.uni-text {
    text-align: center;
    margin-bottom: 40px;
}

.clock {
    height: 50px;
}

.uni-text h1 {

    background-color: red;
    color: white;
    text-align: center;
    padding: 10px;


}

.grafico-container {
    background-color: rgb(229, 103, 104);
    display: flex;
    justify-content: center;
    padding-top: 100px;
    position: relative;
    height: 350px;


}

.grafico {
    height: 130px;
}

.minitext {
    text-align: center;
    color: white;
    position: absolute;
    right: 525px;
    top: 20px;
    font-size: 13px;
}

.minitext h3 {
    width: 60%;
}

.minitext p {
    width: 60%;
    margin-top: 10px;

}

.minitext2 {
    text-align: center;
    color: white;
    position: absolute;
    right: 180px;
    top: 20px;
    font-size: 13px;
}

.minitext2 h3 {
    width: 60%;
}

.minitext2 p {
    width: 60%;
    margin-top: 10px;

}

.minitext3 {
    text-align: center;
    color: white;
    position: absolute;
    left: 400px;
    top: 250px;
    font-size: 13px;
}

.minitext3 h3 {
    width: 60%;
}

.minitext3 p {
    width: 60%;
    margin-top: 10px;

}

.minitext4 {
    text-align: center;
    color: white;
    position: absolute;
    right: 355px;
    top: 250px;
    font-size: 13px;
}

.minitext4 h3 {
    width: 60%;
}

.minitext4 p {
    width: 60%;
    margin-top: 10px;

}

.eventi-container {
    background-color: rgb(229, 103, 104);
    padding-top: 40px;



}

.card-container {
    display: flex;
    justify-content: center;

}

.box-eventi {
    text-align: center;
    color: white;
    font-size: 30px;

}

.card {
    margin-top: 50px;
    padding: 30px;
    width: 25%;
    text-align: center;
    background-color: white;
    border-radius: 20px;
    position: relative;
    margin-left: 20px;
}

.card i {
    margin: 10px;
}

.card span {
    margin-left: 10px;
}

.card button {
    border-radius: 20px;
    border: 1px solid black;
    color: white;
    background-color: rgb(229, 103, 104);
    margin: 10px 0px;
    position: absolute;
    bottom: -27px;
    left: 150px;

}

.btn {
    display: flex;
    justify-content: center;
    margin: 50px;
    margin-bottom: 50px;
}

.btn button {
    border: none;
    border-radius: 20px;
    padding: 20px;
    color: white;
    background-color: variables.$bgcolor-yellow ;

}

.wave-container {
    position: relative;
    padding-top: 50px;
}

.wave {
    width: 100%;
    position: absolute;
    bottom: 0px;
}
</style>