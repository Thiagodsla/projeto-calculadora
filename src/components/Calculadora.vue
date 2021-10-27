<template>
<div class="content">
  <div class="corpo">
    
    <div class="visor">
      conteudo do visor
    </div>
    
  <div class="botoes">
    botoes
  </div>

  </div>
  </div>
</template>
<script>
export default {
  name: 'Calculadora',
  props: {
    msg: String
  }
};
</script>

<style scoped>

h1 {
  color:aliceblue
}

.content{
  display: flex;
  justify-content: center;
}
.corpo{
  background: red;
  width: 40rem;
  height: 45rem;
  display: flex;
  justify-content: center;
}

</style>