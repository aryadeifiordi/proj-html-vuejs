<template>
  <div id="app">
    <Header />
    <Main />
    <Footer :menuItems="footerMenuItems" />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  },
  data() {
    return {
      footerMenuItems: [
        { label: 'Privacy Policy', link: '/privacy' },
        { label: 'Terms of Service', link: '/terms' },
        { label: 'Contact Us', link: '/contact' }
      ]
    };
  }
};
</script>

<style>
html,
body {
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
}

#app {
  width: 100%;
  min-height: 100%;
}
</style>
