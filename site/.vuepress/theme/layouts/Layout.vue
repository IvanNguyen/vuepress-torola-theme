<template>
    <div>
        <Navbar/>
        <Container></Container> 
        <!-- <Content></Content> -->
        <Footer></Footer>
    </div>
</template>

<script>
// import $ from 'jquery'
// import '../../../../node_modules/bootstrap/dist/js/bootstrap.min.js'
// import '../../public/js/parallax.min.js'
import Navbar from '../components/Nav/Navbar.vue'
import Container from '../components/Container/Container.vue'
import Footer from '../components/Footer/Footer.vue'

// $(document).ready(function(){

//   alert('hello');

// });

    export default {
        components: { Navbar, Container, Footer },
    }
</script>



<style src="../styles/theme.css"></style>

// Use AOS node modules, window.$ Jquery ! use Jquery in Vuejs !
// Parallax : vuejs !
// import jquery, webpack