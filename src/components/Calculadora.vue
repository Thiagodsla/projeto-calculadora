<template>
<div class="content">
  <div class="corpo">

    <div class="visor">
      conteudo do visor
    </div>

    <div class="botoes">

      <div class="teclado">

        <div>
          <button>1</button>
          <button>2</button>
          <button>3</button>
        </div>
        <div>
          <button>4</button>
          <button>5</button>
          <button>6</button>
        </div>
        <div>
          <button>7</button>
          <button>8</button>
          <button>9</button>
        </div>
        <div>
          <button>0</button>
        </div>
        <button class="botaoenter">ENTER</button>
      </div>

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
  color: aliceblue
}

.content {
  display: flex;
  justify-content: center;
  border-radius: 10px;
}

.corpo {
  background: rgb(228, 228, 228);
  width: 40rem;

  height: auto;
  box-shadow: 3px 3px 1px rgb(63, 63, 63);

}

.visor {
  background: white;
  height: 8rem;
  border-style: solid;
  border-width: 80px 20px 40px 20px;
  border-color: gray;
  box-shadow: inset 0 2px 3px 2px black;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.botoes {
  padding: 1rem;
  border-style: solid;
  border-width: 10px 20px 40px 20px;
  border-color: rgb(228, 228, 228);
  border-radius: 10px;
}

.teclado {
  display: flex;
  flex-direction: column;
}

.teclado button {
  color: black;
  font-size: 3rem;
  width: 7rem;
  background-color: rgb(228, 228, 228);
  border-style: solid;
 border-radius: 20px;
 box-shadow: 3px 3px 1px black;
}

.teclado button:hover{
  box-shadow: 0px 0px 0px black;
}

button.botaoenter {
  color: black;
  font-size: 3rem;
  width: 15rem;
  background-color: rgb(228, 228, 228);
}

.teclado div {
  padding: 20px;
}

.teclado div:nth-child(1) {
  display: flex;
  justify-content: space-between;
}

.teclado div:nth-child(2) {
  display: flex;
  justify-content: space-between;
}

.teclado div:nth-child(3) {
  display: flex;
  justify-content: space-between;
}

.teclado div:nth-child(4) {
  display: flex;
  justify-content: center;
}
</style>
