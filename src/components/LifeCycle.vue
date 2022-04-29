<template>
  <h1>my name is {{ nome }}</h1>
</template>

<script>
export default {
  name: "LifeCycle",
  data() {
    return {
      nome: "aguardando a criação do componente!!!",
    };
  },
  created() {
    setTimeout(() => {
      this.nome = "Componente Criado";
    }, 1000);
  },
  mounted() {
    setTimeout(() => {
      this.nome = "Patrick Sousa";
    }, 2000);
  },

};
</script>