<template>
    <div class="top-container">
        <div class="sdn-topo">
            <img src="/top.png" alt="top">
        </div>
        <div class="menu">
            <NuxtLink class="item" to="/">HOME</NuxtLink>
            <NuxtLink class="item" to="/">OS NOIVOS</NuxtLink>
            <NuxtLink class="item" to="/">PADRINHOS</NuxtLink>
            <NuxtLink class="item" to="/">NOSSAS DAMINHAS</NuxtLink>
            <NuxtLink class="item" to="/">NOSSOS PAIS</NuxtLink>
            <NuxtLink class="item" to="/">A CERIMÔNIA</NuxtLink>
            <NuxtLink class="item" to="/">A RECEPÇÃO</NuxtLink>
            <NuxtLink class="item" to="/">LISTA DE PRESENTES</NuxtLink>
            <NuxtLink class="item" to="/">CONFIRME SUA PRESENÇA</NuxtLink>
            <NuxtLink class="item" to="/">RECADOS</NuxtLink>
            <NuxtLink class="item" to="/">HOSPEDAGEM</NuxtLink>
            <NuxtLink class="item" to="/">DICAS UTEIS</NuxtLink>
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

    .menu {
        margin: 50px 0;
        border-top: 1px solid white;
        padding: 30px 0;
        border-bottom: 1px solid white;
        gap: 15px;
        display: flex;
        flex-wrap: wrap;
        align-items: center;
        justify-content: center;

        .item {
            color : white;
            font-size: 16px;
            font-weight: 500;
            cursor: pointer;
        }
    }
}
</style>