<script >
import headerSite from "./components/header.vue"
import sezioni from "./components/sezioni.vue"
import linksBanner from "./components/linksBanner.vue"

export default {
  components: {
    headerSite,
    sezioni,
    linksBanner
  }
}
</script>

<template >
  <headerSite />
  <div id="content">
    <div class="container">
      <h2 class="text-light p-5">--> Content goes Here &lt--</h2>
    </div>
  </div>

  <sezioni />

  <linksBanner />

  <!-- footer -->



</template>


<style >
#content {
  background-color: black;

}
</style>
