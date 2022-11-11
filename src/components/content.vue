<script>
import serieCard from "./serieCard.vue"
import seriesTV from "./dc-comics.js"

export default {
    components: {
        serieCard
    },
    data() {
        return {
            seriesTV
        }
    }

}
</script>

<template>

    <!-- prima metto il jumbotron e poi tramite un componente dinamico inserisco le serie -->
    <div id="jumbotron">

        <div class="container ">
            <!-- div dello span current series -->
            <div class="current-series ">
                <h2 class="px-4 pt-1">CURRENT SERIES</h2>
            </div>
        </div>

    </div>

    <!-- div dinamico delle serie -->

    <div class="bg-dark p-5 d-flex flex-wrap">

        <serieCard v-for="serieCard in seriesTV" :image="serieCard.thumb" :title="serieCard.series" />
    </div>


</template>


<style scoped>
#jumbotron {
    background-image: url("../assets/img/jumbotron.jpg");
    height: 500px;
    background-size: cover;

}

.current-series {
    position: absolute;
    color: white;
    top: 470px;
    left: auto;
    background-color: #0282f9;
}

.container {
    position: relative;
}
</style>