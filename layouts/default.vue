<template>
<div class="container">
   <div class="main">
        <TopBar />
        <Nuxt />
   </div>
</div>
</template>
<script>
export default {
    // 
}
</script>
<style lang="scss">
body {
    background: url('static/background-lovelights.jpg') no-repeat top center;
    background-color: #0C0E03;
    color: #fff;
    .container {
        padding-bottom: 60px;
        margin-top: 100px;
        max-width: 950px;
    }
}
</style>