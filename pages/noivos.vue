<template>
  <div>
    <h4>OS NOIVOS</h4>
    <div class="fotos-row">
      <img src="/ee3MJ_1623791920.jpeg" />
      <img src="/ZPiu2_1623791816.jpeg" />
    </div>
   <p>
      Histórias de amor existem, e, às vezes, nem nós mesmos acreditamos todo o tempo que já estamos juntos. 
      Porém, o brilho intenso e apaixonado dos nossos olhares nos fazem lembrar o porquê de chegarmos até aqui 
      sem sentir tanto o tempo passar....Vamos nos casar! Estamos preparando tudo com muito carinho para curtirmos 
      cada momento com nossos amigos e familiares queridos!
    </p>
    <ssr-carousel class="slider-home"  show-arrows  show-dots>
      <div class="slide" v-for="i in 11" :key="i">
        <img  :src="`/slide_noivos/slide${i}.jpeg`">
      </div>
    </ssr-carousel>
   
  </div>
</template>

<script>

export default {
  // 
}
</script>
<style lang="scss">
.fotos-row {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content:center;
  margin-bottom: 20px;
}
.slider-home {
  margin-bottom: 60px;

  img {
    max-width:100%;
    
    &[aria-expanded="true"]{
      display: none;
    }
  }

}
</style>