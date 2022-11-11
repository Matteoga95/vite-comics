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
    <div class="col">
        <div class="serieCard">
            <img :src="image" alt="title">
            <h4>{{ title }}</h4>
        </div>
    </div>




</template>


<style lang="scss">

</style>