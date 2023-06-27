<template>
  <NavBarComp/>
  <router-view/>
  <FooterComp/>
</template>

<script>
// Navbar displaying into website
import NavBarComp from './components/Navbar.vue';
// Footer displaying into website
import FooterComp from './components/Footer.vue';

export default {

components:{NavBarComp,FooterComp}
}

</script>

