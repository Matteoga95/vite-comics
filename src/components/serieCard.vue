<script>
export default {
    name: "serieCard",
    props: {
        image: String,
        title: String
    }
}
</script>

<template>
    <div class="col-2 ">
        <div class="serieCard">
            <img class="img-fluid px-2" :src="image" alt="title">
            <h5 class="py-3">{{ title }}</h5>
        </div>
    </div>




</template>


<style lang="scss">
.serieCard {
    color: white;
}
</style>