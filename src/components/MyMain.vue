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
                <h3>Orientation</h3>
                <p>In the First week, student try to accommodate with the teaching style and choose their optional coursers
                </p>
            </div>
        </div>
    </section>
    <!-- FINE QUARTA SECTION -->
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
</style>