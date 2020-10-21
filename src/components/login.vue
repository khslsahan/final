<template>
<div>

<header>Login World </header>
<div>
    <Header />
    <h1>SAhan Lakshitha </h1>
    <img id="bgimage" src="../assets/login.jpg">
    <Footer />

</div>
</div>
</template>

<script>
import Header from './hedfoo/Header';
import Footer from './hedfoo/Footer';

export default {
    components: {
        'Header': Header,
        'Footer': Footer
    }

}
</script>

<style>
#bgimage {
    width: 100%;
    height: 400px;
}
</style>
