<template>
  <section id="container">
    <div id="container-filho">
      <div id="filho1" data-aos="fade-right">
        <div id="titulo1"><h2>Vantagens de Limpar Nome</h2></div>
        <div id="msg1">
          <p>
            <span>Acesso a oportunidades:</span> Seja alugar um imóvel, investir
            em um negócio ou até mesmo conseguir determinados empregos, o nome
            limpo abre muitas portas.
          </p>

          <p>
            <span>Tranquilidade financeira:</span> Você pode viver com menos
            preocupações e stress, sabendo que suas contas estão em ordem e sem
            restrições
          </p>
        </div>
      </div>
      <!--fim filho1-->

      <div id="filho2">
        <div id="titulo2"><h2>Desvantagens do Nome Sujo</h2></div>
        <div id="msg2">
          <p>
            <span>Acesso limitado a serviços e produtos: </span>Certas empresas
            podem recusar contratos, como aluguel de imóveis ou compra parcelada
            de bens.
          </p>
          <p>
            <span> Dificuldade para planejar o futuro:</span> Restrições
            financeiras podem atrapalhar planos, como investimentos ou compras
            importantes.
          </p>
        </div>
      </div>
      <!--fim filho2-->

      <div id="filho3" data-aos="fade-left">
        <div id="titulo3"><h2>Por Quê ser Pleno Bank</h2></div>
        <div id="msg3">
          <p>
            Oferecemos acordos adaptados a necessidade do cliente. Contamos com
            uma equipe especializado em atendimento humano. Nossa missão é fazer
            você sorrir novamente. Pleno Bank restaura o seupode de comprar na
            forma da lei. <br />
            <span>APROVEITE ESSA MARAVILHA</span>
          </p>
        </div>
      </div>
      <!--fim filho3-->
    </div>
    <!-- fim container-filho-->
  </section>

  <div id="apresentacao2">
    <div id="caixadaacao">
      <div id="hora">
        <h3>A HORA DE LIMPAR SEU SEU NOME É AGORA</h3>
      </div>

      <div id="ação">
        <h4>CLIQUE AQUI</h4>
        <a href="#"><p id="link">QUERO LIMPAR MEU NOME</p></a>
      </div>
    </div>
    <!--fim da caixadaaçao-->
  </div>
  <!--fim da apresentaçao2-->
</template>

<script>
import AOS from "aos";
import "aos/dist/aos.css";

export default {
  name: "sectiom1",

  mounted() {
    AOS.init();
  },
};
</script>

<style scoped>
@import "animate.css";
#container {
  max-width: 100%;
  background-color: rgb(4, 4, 4);
  height: 700px;
}

#container-filho {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
  width: 100%;
  height: 700px;
}
#titulo1,
#titulo2,
#titulo3 {
  width: 300px;
  height: 80px;
  margin-left: 40px;
  margin-bottom: 30px;
  background-color: #23282a;
  box-shadow: 1px 1px 10px rgb(241, 241, 241);
  border-radius: 10px;
  padding-left: 10px;
}
h2 {
  color: #fce038;
  padding-top: 10px;
  text-align: center;
}
span {
  color: #0e00ac;
  border-left: 4px solid #0e00ac;
   border-bottom: 3px solid #0e00ac;
   border-radius: 10px;
}

p {
  color: rgb(0, 0, 0);
  line-height: 40px;
  font-weight: bold;
}
#msg1,
#msg2,
#msg3 {
  width: 300px;
  height: 400px;
  margin-left: 40px;
  background-color: #fce038;
  padding-left: 10px;
  border-radius: 10px;
  transition: transform 0.3s, box-shadow 0.3s;
}

#msg3 {
  height: 390px;
}

#msg1:hover {
  transform: scale(1.2) translateZ(20px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
  z-index: 10; /* Garante que o card esteja na frente */
  box-shadow: 1px 1px 10px #ffffff;
}
#msg2:hover {
  transform: scale(1.2) translateZ(20px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
  z-index: 20; /* Garante que o card esteja na frente */
  box-shadow: 1px 1px 10px #ffffff;
}

#msg3:hover {
  box-shadow: 1px 1px 10px rgb(241, 241, 241);
  transform: scale(1.2) translateZ(20px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
  z-index: 1; /* Garante que o card esteja na frente */
  box-shadow: 1px 1px 10px #ffffff;
}

#apresentacao2 {
  background-image: url(/public/img/bank-site.png);
  height: 600px;

  background-position: right center; /* Centraliza a imagem */
  background-size: cover;
  position: relative;
}

#caixadaacao {
  position: absolute;
  top: 50%;
  left: 2%;
  width: 400px;
  height: 250px;
}

#hora {
  width: 500px;
  box-shadow: 5px 10px 15px #fcba02;
  height: 100px;
  padding: 5px 3px;
  border-radius: 10%;
}

#ação {
  border-radius: 10%;
  margin-top: 80px;
  width: 500px;
  padding: 5px;
  height: 100px;
  box-shadow: 5px 5px 15px white;
}


h3 {
  color: rgb(252, 250, 250);
  font-weight: bold;
  line-height: 50px;
  font-size: 2em;
  text-align: center;
}

h4 {
  margin-left: 10%;
  text-align: center;
  color: rgb(252, 250, 250);
  font-weight: bold;
  line-height: 30px;
  font-size: 2em;
}

#link {
  padding-top: 10px;
  color: #fcba02;
  font-size: 1.5em;
  text-align: center;
}

#link:hover{
  color: #0818fa;
  transition: 0.5s;
}

/*responsivo 450px*/
@media (max-width: 450px) {
  #container {
    max-width: 100%;
    height: 1200px;
  }

  #container-filho {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    width: 90%;
    height: 700px;
  }
  #titulo1,
  #titulo2,
  #titulo3 {
    width: 200px;
    height: 40px;
    margin-left: 25%;
    margin-bottom: 5%;
    margin-top: 5%;
  }

  h2 {
    padding-top: 0px;
    font-size: 1em;
  }

  p {
    font-size: 16px;
    color: rgb(0, 0, 0);
    line-height: 30px;
    font-weight: bold;
    padding-left: 5%;
    padding-top: 5%;
  }
  #msg1,
  #msg2 {
    width: 100%;
    height: 300px;
    margin-left: 19px;

    background-color: #fce038;
    padding-left: 0px;
    border-radius: 10px;
  }

  #msg3 {
    height: 280px;
    width: 100%;
    margin-left: 19px;
    padding-left: 0px;
    border-radius: 10px;
  }

  [data-aos] {
    transform: none; /* Remove transformações */
  }

  #msg1:hover,
  #msg2:hover,
  #msg3:hover {
    transform: none;
  }
  #apresentacao2 {
    background-image: none;
    background-color: #000000;
    width: 100%;
    height:400px;
    margin-bottom: 0%;
  }


  #caixadaacao {
  position: static;
 
  width:100% ;
  height: 250px;
}

#hora {
  width: 90%;
  box-shadow: 5px 10px 15px #fcba02;
  height: 100px;
  padding: 5px 3px;
  border-radius: 10%;
  margin-left: 5%;
}

#ação {
  border-radius: 10%;
  margin-top: 50px;
  width: 100%;
  padding: 20px;
 
  height: 100px;
  box-shadow: 5px 5px 15px white;
}


h3 {
  color: rgb(252, 250, 250);
  font-weight: bold;
  line-height: 40px;
  font-size: 20px;
  text-align: center;
}

h4 {
  margin-left: 0;
  text-align: center;
  color: rgb(252, 250, 250);
  font-weight: bold;
  line-height: 0;
  font-size:20px;
}

#link {
  padding-top: 20px;
  color: #fcba02;
  font-size:22px;
  text-align: center;
}
}

/*responsivo 450px a 600px*/

@media (min-width: 450px) and (max-width: 600px) {
  #container {
    max-width: 100%;
    height: 1350px;
  }

  #container-filho {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    width: 90%;
    height: 700px;
  }
  #titulo1,
  #titulo2,
  #titulo3 {
    width: 200px;
    height: 60px;
    margin-left: 32%;
    margin-bottom: 5%;
    margin-top: 5%;
  }

  h2 {
    padding-top: 0px;
    font-size: 1.3em;
  }

  p {
    font-size: 19px;
    color: rgb(0, 0, 0);
    line-height: 30px;
    font-weight: bold;
    padding-left: 5%;
    padding-top: 5%;
  }
  #msg1,
  #msg2 {
    width: 100%;
    height: 300px;
    margin-left: 19px;

    background-color: #fce038;
    padding-left: 0px;
    border-radius: 10px;
  }

  #msg3 {
    height: 280px;
    width: 100%;
    margin-left: 19px;
    padding-left: 0px;
    border-radius: 10px;
  }

  [data-aos] {
    transform: none; /* Remove transformações */
  }

  #msg1:hover,
  #msg2:hover,
  #msg3:hover {
    transform: none;
  }

 #apresentacao2 {
    background-image: none;
    background-color: #000000;
    width: 100%;
    height: 390px;
   margin-bottom: 0%;
  }


  #caixadaacao {
  position: static;
 
  width:100% ;
  height: 250px;
}

#hora {
  width: 90%;
  box-shadow: 5px 10px 15px #fcba02;
  height: 100px;
  padding: 5px 3px;
  border-radius: 10%;
  margin-left: 5%;
}

#ação {
  border-radius: 10%;
  margin-top: 50px;
  width: 100%;
  padding: 20px;
 
  height: 100px;
  box-shadow: 5px 5px 15px white;
}


h3 {
  color: rgb(252, 250, 250);
  font-weight: bold;
  line-height: 40px;
  font-size: 20px;
  text-align: center;
}

h4 {
  margin-left: 0;
  text-align: center;
  color: rgb(252, 250, 250);
  font-weight: bold;
  line-height: 0;
  font-size:20px;
}

#link {
  padding-top: 20px;
  color: #fcba02;
  font-size:22px;
  text-align: center;
}
}

/*responsivo 600px  a 800px */
@media (min-width: 600px) and (max-width: 800px) {
  #container {
    max-width: 100%;
    height: 1500px;
  }

  #container-filho {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    width: 90%;
    height: 700px;
  }
  #titulo1,
  #titulo2,
  #titulo3 {
    width: 400px;
    height: 80px;
    margin-left: 21%;
    margin-bottom: 5%;
    margin-top: 5%;
    padding: 5px 5px;
  }

  h2 {
    padding-top: 0px;
    font-size: 2em;
  }

  p {
    font-size: 20px;
    color: rgb(0, 0, 0);
    line-height: 30px;
    font-weight: bold;
    padding-left: 5%;
    padding-top: 5%;
  }
  #msg1,
  #msg2,
  #msg3 {
    width: 100%;
    height: 300px;
    margin-left: 19px;

    background-color: #fce038;
    padding-left: 0px;
    border-radius: 10px;
  }

  [data-aos] {
    transform: none; /* Remove transformações */
  }

  #msg1:hover,
  #msg2:hover,
  #msg3:hover {
    transform: none;
  }
  #apresentacao2 {
    background-image: none;
    background-color: #000000;
    width: 100%;
    height: 300px;
    margin-bottom: 0%;
  }


  #caixadaacao {
  position: static;
 
  width:100% ;
  height: 250px;
}

#hora {
  width: 90%;
  box-shadow: 5px 10px 15px #fcba02;
  height: 100px;
  padding: 5px 3px;
  border-radius: 10%;
  margin-left: 5%;
}

#ação {
  border-radius: 10%;
  margin-top: 50px;
  width: 100%;
  padding: 20px;
 
  height: 100px;
  box-shadow: 5px 5px 15px white;
}


h3 {
  color: rgb(252, 250, 250);
  font-weight: bold;
  line-height: 40px;
  font-size: 30px;
  text-align: center;
}

h4 {
  margin-left: 0;
  text-align: center;
  color: rgb(252, 250, 250);
  font-weight: bold;
  line-height: 0;
  font-size:30px;
}

#link {
  padding-top: 20px;
  color: #fcba02;
  font-size:35px;
  text-align: center;
}
}
</style>
