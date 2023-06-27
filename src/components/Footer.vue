<template>
<div class="footer">
    <h6>Footer</h6>
    <p class="footer-text">
    <router-link class="menu" to="/">Home</router-link>
    <router-link class="menu" to="/tutorials">Tutorials</router-link>
    <router-link class="menu" to="/about">About</router-link>
    </p>

</div>
</template>
<script>
export default {

}
</script>

<style scoped>
.footer{
    bottom: 0;
    left: 0;
    /* height: 90px; */
    width: 100%;
    background-color: darkgreen;
}
h6{
    text-align: center;
    font-size: 20px;
    color: whitesmoke;
    letter-spacing: 10px;
}

.menu{
    background-color: yellowgreen;
    font-size: 25px;
    padding-left: 40px;
    word-spacing: 50px;
    text-decoration: none;
    letter-spacing: 10px;
    text-align: center;
}
.menu:hover{
    background-color: whitesmoke;
    font-size: 20px;
}
</style>