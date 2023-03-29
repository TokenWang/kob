<template>
  <Navbar />
  <router-view/>
</template>

<script>
import Navbar from '@/components/NavBar.vue'
import "bootstrap/dist/css/bootstrap.min.css"
import "bootstrap/dist/js/bootstrap"
import $ from "jquery";
import { ref } from 'vue';
export default {
  components: {
    Navbar
  },
  name: "App",
  setup: () => {
    let bot_name = ref("");
    let bot_lv = ref("");
    $.ajax({
      

    })

    return {
      bot_name,
      bot_lv
    }
  }
}

</script>


<style>
body {
  background-image: url(@/assets/images/background.jpg);
  background-size: cover;
}
</style>
