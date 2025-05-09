<template>
    <div class="logo">

        <img src="img/spc-removebg-preview.png" alt="logo do spc">
        <img src="/img/serasa.png" alt="logo do serasa">
    </div>

    <div class="titulo">

            <h2>Esses  Nomes te Assustam?<br> <span>Sim né</span></h2>
            <h3>Mas Nós Te Damos A Solução</h3>
        </div>
</template>


<script>
export default {
    nome: 'logo'
}
</script>

<style scoped>
.logo{
    width: 100%;
    height: 400px;
display: flex;
gap: 20px;
justify-content: center;
align-items: center;
}

img{
width: 400px;
width: 500px;

}
 span{
    color: rgb(254, 254, 254);
 }

.titulo{
    width: 1000px;
    margin-bottom: 2%;
    margin-left: 18%;
   background-color: #030303;
    padding: 10px;
    border-radius: 20%;
    border: 3px  #fcba02;
}

h2,h3{  
    text-align: center;
    color: #fcba02;
    margin-left: 10%;
    line-height: 60px;
    font-size: 3em;
    font-weight: bold;
}
h3{
    color: rgb(255, 254, 254);
}



/* responsivo max 450px */
@media (max-width:450px){
    .logo{
        display: flex;
    width: 100%;
    height: 600px;
 flex-direction: column;
gap: 0;

}

img{
width: 300px;
height: 300px;

}
 

.titulo{
    width: 100%;
    margin-bottom: 2%;
    margin-left: 0%;
   height: 2%;
    padding: 5px;
    border-radius: 0;
    
}

h2,h3{  
   text-align: center;
    margin-left: 0;
    line-height: 35px;
    font-size: 35px;
    font-weight: bold;
}

}

/* responsivo min 450px max 600px*/
@media (min-width: 450px) and (max-width:600px){
       .logo{
        display: flex;
    width: 100%;
    height: 600px;
 flex-direction: column;
gap: 0;

}

img{
width: 400px;
height: 400px;

}
 

.titulo{
    width: 100%;
    margin-bottom: 2%;
    margin-left: 0%;
   height: 150px;
    padding: 5px;
    border-radius: 0;
    
}

h2,h3{  
   text-align: center;
    margin-left: 0;
    line-height: 35px;
    font-size: 35px;
    font-weight: bold;
  
}
}


/* responsivo min 600px max 800px*/
@media (min-width: 600px) and (max-width:800px){
       .logo{
        display: flex;
    width: 100%;
    height: 600px;
 flex-direction: column;
gap: 0;

}

img{
width: 400px;
height: 400px;

}
 

.titulo{
    width: 100%;
    margin-bottom: 2%;
    margin-left: 0%;
   height: 150px;
    padding: 5px;
    border-radius: 0;
    
}

h2,h3{  
   text-align: center;
    margin-left: 0;
    line-height: 35px;
    font-size: 35px;
    font-weight: bold;
  
}
}
</style>