<script >
import headerSite from "./components/header.vue"
import sezioni from "./components/sezioni.vue"
import linksBanner from "./components/linksBanner.vue"
import footer from "./components/footer.vue"


export default {
  components: {
    headerSite,
    sezioni,
    linksBanner,
    footer
  }
}
</script>

<template >
  <headerSite />
  <div id="content" class="p-5">
    <div class="container">
      <h2 class="text-light p-5">--> Content goes Here &lt--</h2>
    </div>
  </div>

  <sezioni />

  <linksBanner />

  <footer />

  <div id="footer">
    <div class="container">
      <div class="  p-4 d-flex justify-content-between">

        <div class="border border-primary p-2">SIGN-UP NOW!</div>

        <div class="d-flex justify-content-center">
          <h4>FOLLOW US</h4>
          <img class="img-fluid px-3" src="./assets/img/footer-facebook.png" alt="">
          <img class="img-fluid px-3" src="./assets/img/footer-twitter.png" alt="">
          <img class="img-fluid px-3" src="./assets/img/footer-youtube.png" alt="">
          <img class="img-fluid px-3" src="./assets/img/footer-pinterest.png" alt="">
          <img class="img-fluid px-3" src="./assets/img/footer-periscope.png" alt="">
        </div>

      </div>
    </div>
  </div>

</template>


<style >
#content {
  background-color: black;

}

#footer {
  background-color: #303030;
  color: white;
  z-index: 99;
}
</style>
