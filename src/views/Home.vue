<template>
  <div class="hello">
    <Header />
    <Section title="{ email: hello@broadley.email }" />
    <Footer />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue';
import Footer from '@/components/Footer.vue';
import Section from '@/components/Section.vue';

export default {
  name: 'home',
  components: {
    Header,
    Section,
    Footer,
  },
};
</script>

<style lang="less">
</style>