<template>
  <div id="first-container">
    <img src="/img/logo2.png" alt="logo da empresa" />

    <div id="sobre">
      <h1 id="first-title" class="animate__animated animate__backInLeft">
        Sobre Nós
      </h1>
      <p class="animate__animated animate__backInRight">
        Nós acreditamos que o bem-estar financeiro é para todo mundo! Desde
        2015, a Pleno Bank benefícios já recuperou mais de meio bilhão de reais
        em renegociação de dívidas. Isso só foi possível porque nunca deixamos
        de acolher o nosso consumidor.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "serviços1",
};
</script>

<style scoped>
@import "animate.css";
#first-container {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  gap: 70px;
  height: 600px;
  background-color: rgb(4, 4, 4);
  overflow: hidden;
}

#first-title {
  font-size: 60px;
  font-weight: bold;
  width: 400px;
  text-align: center;
  border-radius: 20px;
  background-color: #23282a;
  box-shadow: 1px 1px 10px rgb(241, 241, 241);
  border-radius: 10px;
  color: #fcba02;
}

p {
  font-size: 30px;
  line-height: 50px;
  margin-top: 30px;
  color: white;
}
img{
  width: 400px;
  height: 500px;
}


/*responsivo max 450px*/
@media (max-width: 450px) {
  #first-container {
    flex-direction: column;
    gap: 40px;
    height: 1000px;
  }

  #first-title {
    font-size: 30px;
    width: 200px;
    margin-left: 23%;
    animation: none;
  }
  p {
    font-size: 18px;
    margin-left: 10px;
    animation: none;
  }
  img {
    margin-top: 40px;
    width: 100%;
    height: 400px;
  }
}



/*responsivo min 450px max 600px*/

@media (min-width: 450px) and (max-width:600px){
  #first-container {
    flex-direction: column;
    gap: 40px;
    height: 1000px;
  }

  #first-title {
    font-size: 30px;
    width: 200px;
    margin-left: 23%;
    animation: none;
  }
  p {
    font-size: 18px;
    margin-left: 10px;
    animation: none;
  }
  img {
    margin-top: 40px;
    width: 100%;
    height: 400px;
  }
}

@media (min-width: 600px) and (max-width:800px){
  #first-container {
    flex-direction: column;
    gap: 40px;
    height: 1000px;
  }

  #first-title {
    font-size: 30px;
    width: 200px;
    margin-left: 30%;
    animation: none;
  }
  p {
    font-size: 25px;
    margin-left: 10px;
    animation: none;
  }
  img {
    margin-top: 40px;
    width: 100%;
    height: 400px;
  }
}
</style>
