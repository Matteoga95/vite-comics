<script >
import headerSite from "./components/header.vue"
import sezioni from "./components/sezioni.vue"

export default {
  components: {
    headerSite,
    sezioni
  }
}
</script>

<template>
  <headerSite />
  <div id="content">
    <div class="container">
      <h2 class="text-light p-5">--> Content goes Here &lt--</h2>
    </div>
  </div>

  <sezioni />




</template>


<style >
#content {
  background-color: black;

}
</style>
