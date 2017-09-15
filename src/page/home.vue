<template>
<div class="home-box">
    <img src="http://cangdu.org/happyfri/static/img/1-2.png" class="home-img" />
    <router-link to="item" class="com-next-btn">开始</router-link>
</div>
</template>

<script>
import '../common.css'
import '../common.js'

export default {
  name: 'home',
  mounted() {
        document.body.style.background = 'url(http://cangdu.org/happyfri/static/img/1-1.jpg)  no-repeat center / cover';
    },
}
</script>

<style scoped>
body {
    padding-top: 7rem;
}
.home-img {
    display: block;
    margin: 0 auto 2rem;
    width: 20rem;
    padding-top: 8rem;
}
</style>
