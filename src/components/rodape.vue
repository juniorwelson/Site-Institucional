<template>
<footer>
    <div class="container">
          
     <div class="redes">
       <div class="titulo"> <h2>Nossas redes</h2></div>
     <a href=""><img src="/img/icons8-instagram.png"></a>   
      <a href=""> <img src="/img/icons8-whatsapp-50.png"></a>  
     </div>


    <div id="infor">
         <p>© 2025 Pleno Bank Benefícios. <span>Todos os direitos reservados</span>.</p> 
         <p> <span>Endereço:</span> Salvador,Bahia.</p>
         <p ><span>E-mail:</span>plenobanksac@gmail.com.</p>
         </div>
    
  <img  id="logo" src="/img/logo (2).png" >     

</div>


</footer>


</template>

<script>
export default {
    name:'rodape'
}
</script>


<style scoped>
footer{
    background-color:rgb(2, 2, 2) ;
    width: 100%;
    height: 250px;
  }

.container{
    display: flex;
align-items: center;
justify-content: space-around;
}
h2{
    font-size: 2rem;
    text-align: center;
    color: white;
    border-left: #fcba02 2px solid;
    padding-left: 10px;
}
p{
    color: #fcba02;
    font-size: 18px;
    line-height: 35px;
}
span{
    color: white;
}

.redes{
  margin-top: 3rem;
  gap: 10px;
    
}

#infor{
    padding: 10px;
    box-shadow: 5px 5px 10px white;
    height: 150px;
}

img{
    width: 90px;
    height: 100px;
}

#logo{
   width: 200px;
    height: 150px;  
}


/* responsivo max 450px */

@media (max-width:450px){
footer{
   
    width: 100%;
    height: 450px;
  }

.container{
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    gap:20px
}
h2{
    font-size: 30px;
    text-align: center;
    color: white;
    
    border-left: #fcba02 2px solid;
    padding-left:5px;
}
p{
    color: #fcba02;
    font-size: 18px;
    line-height:30px;
}
span{
    color: white;
}

.redes{
  margin-top: 2em;
  gap: 5px;
    
}

#infor{
    padding: 10px;
   box-shadow: none;;
    height: 90px;
}

img{
    width: 50px;
    height: 70px;
}

#logo{
   width: 150px;
    height: 110px;  
    margin-top: 10%
}

}

/* responsivo min 450px max 600px*/
@media (min-width: 450px) and (max-width:600px){
    footer{
   
    width: 100%;
    height: 450px;
  }

.container{
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    gap:20px
}
h2{
    font-size: 30px;
    text-align: center;
    color: white;
    
    border-left: #fcba02 2px solid;
    padding-left:5px;
}
p{
    color: #fcba02;
    font-size: 18px;
    line-height:30px;
}
span{
    color: white;
}

.redes{
  margin-top: 2em;
  gap: 5px;
    
}

#infor{
    padding: 10px;
   box-shadow: none;;
    height: 90px;
}

img{
    width: 50px;
    height: 70px;
}

#logo{
   width: 250px;
    height: 130px;  
    margin-top: 10%
}

}

/* responsivo min 600px max 800px*/
@media (min-width: 600px) and (max-width:800px){
    footer{
   
    width: 100%;
    height: 250px;
  }

.container{
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    gap:20px
}
h2{
    font-size: 20px;
    text-align: center;
    color: white;
    
    border-left: #fcba02 2px solid;
    padding-left:5px;
}
p{
    color: #fcba02;
    font-size: 18px;
    line-height:30px;
}
span{
    color: white;
}

.redes{
  margin-top: 2em;
  gap: 5px;
  margin-left: 3%;
    
}

#infor{
    padding: 10px;
   box-shadow: none;;
    height: 90px;
}

img{
    width: 50px;
    height: 70px;
}

#logo{
   width: 150px;
    height: 110px;  
    margin-top: 10%
}

}
</style>