<template>
  <div id="app" class="d-flex flex-column h-100">
    <nav-bar />
    <div class="container flex-grow-1">
      <error />
      <div class="mt-5">
        <router-view />
      </div>
    </div>
    <footer class="bg-light text-center p-3">
      <img
      src="Logo.png"
            alternate="ConversateLogo"
            width="80px"
            height="80px"
            />
      <p>
        <!--Text for the footer can go here-->
      </p>
    </footer>
  </div>
</template>

<script>
import NavBar from "./components/NavBar";
import Error from "./components/Error";
export default {
  components: {
    NavBar,
    Error,
  }
};
</script>

<style>

</style>
