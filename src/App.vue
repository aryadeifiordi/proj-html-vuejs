<template>
  <div id="app">
    <Header :menuItems="headerMenuItems" />
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
      headerMenuItems: [
        { label: 'Home', link: '/' },
        { label: 'About', link: '/about' },
        { label: 'Services', link: '/services' }

      ],
      footerMenuItems: [
        { label: 'Privacy Policy', link: '/privacy' },
        { label: 'Terms of Service', link: '/terms' },
        { label: 'Contact Us', link: '/contact' }

      ]
    };
  }
};
</script>

<style></style>
