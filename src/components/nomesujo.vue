<template>
    
<sectiom id="container">
   <div class="titulos"><h1>O Que É Nome Negativado</h1></div> 
    <div id="texto">
       <p>Refere-se a uma situação em que uma pessoa tem seu nome registrado em cadastros de <strong>inadimplentes</strong>, como o SPC (Serviço de Proteção ao Crédito) ou o Serasa. Isso ocorre quando há dívidas em aberto que não foram pagas no prazo acordado, como contas de cartão de crédito, financiamentos, empréstimos ou outras obrigações financeiras.</p> 
   
       <div class="titulos"><h2>Consequências</h2></div> 
        <ol>
            <li><strong>Dificuldade em obter crédito</strong>: Instituições financeiras e lojas podem negar a concessão de empréstimos, financiamentos e crediários.

</li>
            <li><strong>Juros mais altos</strong>: Caso consiga obter crédito, as taxas de juros podem ser bem mais elevadas devido ao risco associado.</li>

            <li><strong>Restrição para abrir conta bancária:</strong>Alguns bancos podem recusar a abertura de contas correntes ou a concessão de cartões de crédito.

</li>
            <li><strong>Impedimento para alugar imóveis:</strong>: Proprietários e imobiliárias geralmente verificam a situação do inquilino antes de aprovar o aluguel.</li>
            <li><strong>Impacto na reputação:</strong>Ter o nome negativado pode afetar a confiança e a credibilidade perante fornecedores, parceiros comerciais e até mesmo empregadores.</li>
        </ol>



    </div>
</sectiom>

</template>



<script>
export default {
   name:'nomesujo' 
}
</script>

<style scoped>
#container{
 width: 100%; 
 
 background-color: rgb(0, 0, 0);

} 
.titulos{
    margin-top:40px ;
    margin-left: 50px;
     width: 95%;
}

h1{
    text-align: center;
    font-size: 3rem;
    font-weight: bold;
  border-left:5px solid #fcba02 ;
    border-bottom:5px solid #fcba02 ;
    border-radius: 10px;
    width: 750px;
    
    color: #fcba02;
    
}

#texto{
    width: 100%;
    margin-top: 0px;
    padding-left: 10px;
    margin-top: 10px;
    
    
}

P{
    font-size: 1.5rem;
    line-height: 30px;  
    color: rgb(0, 0, 0); 
}

h2{
    text-align: center;
    font-size: 3rem;
    border-left:5px solid #fcba02 ;
    border-bottom:5px solid #fcba02 ;
    border-radius: 10px;
    padding-left: 5px;
    font-weight: bold;
    color: #fcba02;
  width: 400px;
    margin-top: 30px;
}

ol{
  
    margin-left: 18px;
    margin-top: 30px;
    
}

li{
   color: rgb(0, 0, 0);
    font-size: 1.5rem;
    line-height: 45px;
    list-style: none; 
    
   
}  

strong{
    border-left: #fcba02 4px solid;
        border-bottom: #fcba02 4px solid;
    padding-left: 5px;
}



/*resposivo max 450px*/
 @media (max-width:450px){
.titulos{
    margin-top:40px ;
    font-size: 30px;
    margin-left: 0px;
}

h1{
    font-size: 1.5rem;
    width: 350px;
}

P{
    font-size: 18px;
    line-height: 50px;   
}

h2{
    font-size: 30px;
    padding-left: 5px;
  width: 300px;
    margin-top: 20px;
}


li{
   width: 100%;
    font-size: 18px;
    line-height: 35px;
}

 }

 @media (min-width: 450px) and (max-width: 600px){
    .titulos{
    margin-top:40px ;
    font-size: 30px;
    margin-left: 0px;
}

h1{
    font-size: 2rem;
    width: 500px;
}

P{
    font-size: 1rem;
    line-height: 50px;   
}

h2{
    font-size: 2rem;
    padding-left: 5px;
  width: 300px;
    margin-top: 20px;
}


li{
   width: 100%;
    font-size: 20px;
    line-height: 25px;
}

 }

 @media (min-width: 600px) and (max-width: 800px){
     .titulos{
    margin-top:40px ;
    font-size: 30px;
    margin-left: 0px;
}

h1{
    font-size: 2rem;
    width: 500px;
}

P{
    font-size: 1.5rem;
    line-height: 50px;   
}

h2{
    font-size: 2rem;
    padding-left: 5px;
  width: 300px;
    margin-top: 20px;
}


li{
   width: 100%;
   padding-left: 10px;
    font-size: 25px;
    line-height: 35px;
}
 }
</style>