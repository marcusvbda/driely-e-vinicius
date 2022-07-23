<template>
  <div>
    <h4>NOSSOS PAIS</h4>
   <p>
     Nosso exemplo, nossa inspiração! Se hoje estamos construindo uma vida juntos, é porque nossos pais nos educaram e nos ensinaram o que é o amor e o que é família. Queremos que, nessa nova etapa das nossas vidas, sejamos motivo de orgulho e alegria para aqueles que sempre fizeram de tudo por nós.
    É hora de retribuir todo carinho e atenção que sempre recebemos de vocês e trazer para esse grande dia sensações únicas e inesquecíveis. Pensamos em cada detalhe para que NOSSO DIA C seja também o melhor dia da vida de vocês.
      <br>
      Juntos no altar e na vida, sempre!
      <br>
      AMAMOS VOCÊS!
    </p>

  <div class="flex-row mb-4 gap-4">
    <div class="flex-column">
      <img src="/pais/eliane.png" />
      <div class="text-center mt-2">Eliane</div>
    </div>
    <div class="flex-column">
      <img src="/pais/eliane_hideo.png" />
    </div>
    <div class="flex-column">
      <img src="/pais/dri_hideo.png" />
      <div class="text-center mt-2">Hideo</div>
    </div>
  </div>

  <div class="flex-row mb-4 gap-4">
    <div class="flex-column">
      <img src="/pais/marilia.jpeg" />
      <div class="text-center mt-2">Marilia</div>
    </div>
    <div class="flex-column">
      <img src="/pais/marilia_marcos.png" />
    </div>
    <div class="flex-column">
      <img src="/pais/marcos_vinicius.jpeg" />
      <div class="text-center mt-2">Marcos</div>
    </div>
  </div>

   <div class="flex-row mb-4 gap-4">
      <img src="/pais/pais_dri.jpg" class="w-100"/>
    </div>

    <div class="flex-row mb-4 gap-4">
      <img src="/pais/pais_vini.jpg" class="w-100"/>
    </div>
   
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