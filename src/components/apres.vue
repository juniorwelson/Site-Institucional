<template>
   <main id="principal">
   
    <div id="texto">
        <h1 id="texto1">Nome Sujo? </h1>
        <h2 id="texto2">Te Incomoda,Não é Mesmo? <br>Nós te Damos a Solução  <br>de forma:</h2>
       <ul>
        <li>FÁCIL</li>
        <li>PRÁTICO</li>
        <li>SIMPLES</li>
        <li> <span id="span">100% SEGURO</span></li>
       </ul>
    </div>  
   </main>
   
</template>

<script>
export default{
    name: 'apres'
}

</script>


<style scoped>
#texto{
    display: block;
    margin-left: 3rem;
   
    position: absolute;
    top:50px;
}

#texto1{

    box-shadow: 10px 10px 20px rgba(0, 0, 0, 0.2);
         text-shadow: 3px 3px 10px   rgba(0, 0, 0, 0.553);
    background-color: rgba(255, 255, 255, 0.129);
    padding: 4px;
    margin-top: 40px;
    font-size: 5rem;
    color: #fcba02;
    letter-spacing: 2px;
    text-transform: uppercase;
}

#texto2{
     text-shadow: 3px 3px 10px   rgba(0, 0, 0, 0.825);
 margin-top: 20px;
 color: rgb(238, 234, 234);
font-family:Verdana, Geneva, Tahoma, sans-serif;
  font-size: 2rem; 
  letter-spacing: 2px; 

}

ul{
 margin-top: 25px;
}

li{

 box-shadow: 0px 3px 10px   rgba(244, 237, 237, 0.359);
width: 255px;
color: #fcba02;
font-size:2rem ;
padding-left: 5px;
font-weight: bold;
line-height: 50px;
 margin-left:15px ;
}



#principal{
   
    width: 100%;
    height: 90vh;
    background-image: url(/public//img/tired-femalel.jpg  );
position: relative;
    background-size: 100%  100%;
}


/*responsivo 450px*/
@media(max-width: 450px){
   #texto{
    display: block;
    position: absolute;
    top:50px;
}

#texto1{  
    width: 260px;
    font-size: 2rem;
    letter-spacing: 2px;

    
}
 #texto2{
  font-size: 18px; 
  letter-spacing: 2px; 
  text-transform: uppercase;
}

ul li{
    font-size: 1.5em;
color: #fcba02;
line-height: 40px;
 margin-left:15px;
}   
}


/*responsivo 450px/600px*/
@media(min-width: 450px) and (max-width:600px){

 #texto{
    display: block;
    position: absolute;
    top:50px;
}
#span{
    color: #fcba02;
}
#texto1{
    margin-left: 20px;
     width: 260px;
    font-size: 2rem;
    color: #fcba02;
    letter-spacing: 2px;
    
}
 #texto2{
  font-size: 25px; 
  letter-spacing: 2px; 
 
}
ul{
    margin-left: 15px;
}

li{
    
  color: #fcba02; 
font-size:1.5rem ;
font-weight: bold;
line-height: 40px;
 margin-left:15px;
}   



}/* FIMresponsivo 600px/850px*/

/*responsivo 600px/850px*/
@media(min-width: 600px) and (max-width:850px){
   #texto{
    display: block;
    position: absolute;
    top:50px;
}
#span{
    color: #fcba02;
}
#texto1{
    margin-left: 20px;
     width: 375px;
    font-size: 3rem;
    color: #fcba02;
    letter-spacing: 2px;
    
}
 #texto2{
  font-size: 25px; 
  letter-spacing: 2px; 
  text-transform: uppercase;
}
ul{
    margin-left: 25px;
}

li{
    
    color:white;
font-size:1.5rem ;
font-weight: bold;
line-height: 40px;
 margin-left:15px;
}   
}



</style>