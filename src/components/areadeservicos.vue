<template>
  <section id="servicos">
    <div id="titulo"><h1>SERVIÇOS</h1></div>

    <ul id="lista" class="animate__animated animate__fadeInLeft">
      <li>Limpeza de nome</li>
      <li>Consulta ao Serasa</li>
      <li>Consulta nas Empresas Credoras</li>
      <li>Blindagem de Consulta ao seu Nome</li>
      <li>Aumento de Score</li>
    </ul>
  </section>
</template>

<script>
export default {
  name: "servicos",
};
</script>

<style scoped>
#servicos {
  background-color: rgb(4, 4, 4);
  width: 100%;
  height: 500px;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 200px;
}

h1 {
  font-size: 80px;
  border-left: 5px solid #fcba02;
  border-bottom: 5px solid #fcba02;
  border-radius: 10px;
  padding-left: 5px;
  font-weight: bold;
  color: #fffffe;
}

ul {
  margin-bottom: 25px;
}
ul li {
  padding-top: 45px;
  padding-bottom: 5px;
  text-align: center;
  box-shadow: 15px 13px 20px rgba(244, 237, 237, 0.359);
  list-style: none;
  color: #fcba02;
  font-size: 2rem;
  padding-left: 5px;
  font-weight: bold;
}

/*responsivo max 450px*/
@media (max-width: 450px) {
  #servicos {
    height: 850px;
    flex-direction: column;
    margin-top: 0%;
  }

  h1 {
    font-size: 60px;
    margin-top: 20px;
  }

  ul {
    margin-bottom: 25px;
    width: 100%;
  }
  ul li {
    padding-top: 30px;
    margin-bottom: 20px;
    font-size: 30px;
  }
}

/*responsivo 450px a 600px*/
@media (min-width: 450px) and (max-width: 600px) {
  #servicos {
    height: 850px;
    flex-direction: column;
    margin-top: 0%;
  }

  h1 {
    font-size: 60px;
    margin-top: 20px;
  }

  ul {
    margin-bottom: 25px;
    width: 100%;
  }
  ul li {
    text-align: center;
    box-shadow: 15px 13px 20px rgba(244, 237, 237, 0.359);
    list-style: none;
    color: #fcba02;
    font-size: 2rem;
    padding-top: 30px;
    margin-bottom: 20px;
  }
}

/*responsivo 600px a 800px*/

@media (min-width: 600px) and (max-width: 800px) {
  #servicos {
    height: 850px;
    flex-direction: column;
    margin-top:0%;
  }

  h1 {
    font-size: 60px;
    margin-top: 20px;
  }

  ul {
    margin-bottom: 25px;
    width: 100%;
  }
  ul li {
    font-size: 2rem;
  }
}
</style>
