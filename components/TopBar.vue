<template>
    <div class="top-container">
        <div class="sdn-topo">
            <img src="/top.png" class="lg-show sm-hide" alt="top">
            <img src="/top_small.png" class="lg-hide sm-show" alt="top">
        </div>
    </div>
</template>
<script>
export default {
    // 
}
</script>
<style lang="scss">
.top-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;  
    background-repeat: no-repeat;
    .sdn-topo {
        padding-top: 55px;

        img {
            width: 100%;
            height: 100%;
        }
    }
}
</style>