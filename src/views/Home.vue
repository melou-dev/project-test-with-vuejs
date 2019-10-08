<template>
  <div>
    <HomeQuoteAboutLille />
    <HomeImage />
  </div>
</template>

<script>
import HomeImage from '@/components/HomeImage.vue';
import HomeQuoteAboutLille from '@/components/HomeQuoteAboutLille.vue';

export default {
  name: 'home',
  components: {
   HomeImage,
   HomeQuoteAboutLille,
  }
}
</script>
