<template>
  <banner></banner>
  <div class="main-container">
    <h1>Monte o seu burguer</h1>
    <formulario></formulario>
  </div>
</template>

<script>
import Banner from '@/components/Banner.vue';
import Formulario from '@/components/Formulario.vue';
// @ is an alias to /src

export default {
  name: "HomeView",
  components:{
    Banner,
    Formulario
  },
};

</script>
