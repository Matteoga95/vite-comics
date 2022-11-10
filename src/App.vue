<script >
import headerSite from "./components/header.vue"

export default {
  components: {
    headerSite
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
</template>

<style >
#content {
  background-color: black;

}
</style>
