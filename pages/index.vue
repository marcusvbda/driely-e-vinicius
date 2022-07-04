<template>
  <div>
    <p>
      Criamos esse site para compartilhar com vocês os detalhes da organização do nosso casamento. Estamos muito felizes e contamos com a presença de todos no nosso grande dia!
    </p>
    <p>
      Aqui vocês encontrarão também dicas para hospedagem, salão de beleza, trajes, etc.
    </p>
    <p>
      Ah, é importante também confirmar sua presença. Para isto contamos com sua ajuda clicando no menu "Confirme sua Presença" e preenchendo os dados necessários.
    </p>
    <p>
      Para nos presentear, escolha qualquer item da Lista de Casamento! Já moramos juntos e temos tudo o que precisamos no nosso apê. Por isso, optamos por um sistema de cotas que nos ajuda planejar nossa tão sonhada viagem de Lua de Mel!!
    </p>
    <p>
      Ansiosos, Aguardamos vocês no nosso grande dia!
    </p>
    <ssr-carousel class="slider-home"  show-arrows  show-dots>
      <div class="slide" v-for="i in 13" :key="i">
        <img  :src="`/slide_home/slide${i}.jpeg`">
      </div>
    </ssr-carousel>

    <img src="/save_the_date.jpg" alt="save_the_date" style="width: 100%;">

   
  </div>
</template>

<script>

export default {
  // 
}
</script>
<style lang="scss">
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