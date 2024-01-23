<template>
  <Banner />
  <div class="main-container">
    <H1>Monte o seu burger</H1>
    <BurgerForm />
  </div>
</template>

<script>

import Banner from '@/components/Banner.vue';
import BurgerForm from '@/components/BurgerForm.vue';

export default{
  name: 'HomerView',
  components: {
    Banner,
    BurgerForm
  }
}
</script>
