<template>
  <center>
    <h1 style="color: aliceblue;">SECCION INICIADA</h1>
  </center>
</template>

<script>
export default {
  methods: {
    redirigirAOtraPagina() {
      this.$router.push('/MemePage');
    },
    redirigirOpciones() {
      this.$router.push('/configuracionUsuario');

    },
    redirigirCrearCarta() {
      this.$router.push('/CardPage');
    }


  }
}
</script>

<style>
.boton-crear-meme {
  background-color: #007BFF;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  font-size: 16px;
}

.content{
  flex-grow: 1;
}

.boton-crear-meme:hover {
  background-color: #0056b3;
}

.opcionesUsuario {
  background-color: red;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  font-size: 16px;
}

.opcionesUsuario:hover {
  background-color: #eb6f0a;
}


.crearcarta {
  background-color: #0056b3;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  font-size: 16px;
}

.opcionesUsuario:hover {
  background-color: #0056b3;
}
</style>