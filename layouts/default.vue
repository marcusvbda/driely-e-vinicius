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
    color: #fff;
    .container {
        padding-bottom: 60px;
        margin-top: 100px;
    }

    @media screen and (min-width: 972px) {
        .lg-show {
            display: block;
        }

        .lg-hide {
            display: none;
        }
        
        .sm-show {
            display: none;
        }

        .sm-hide {
            display: block;
        }
    }
    @media screen and (max-width: 971px) {
        .lg-show {
            display: none;
        }

        .lg-hide {
            display: block;
        }
        
        .sm-show {
            display: block;
        }

        .sm-hide {
            display: none;
        }
    }
}
</style>