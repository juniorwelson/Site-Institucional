<template>
    <header class="nav-container">
        <div id="logo">
            <router-link to="/" id="logos">PLENO BANK</router-link>
        </div>
     <nav id="nav">
    <router-link class="link" to="/">Home</router-link> 

     <router-link class="link" to="/Serviços">Serviços</router-link>
  </nav>
  <div id="botao">
    <img src="/img/menusuperior.png" alt="botao-menu" @click="menu">
  </div>
  </header>
</template>

<script>
export default {
    name:'navbar',
  methods: {
  menu() {
    let Nav = document.querySelector('#nav');
    let botao = document.querySelector('#botao');

    botao.addEventListener('click', function() {
      if (Nav.style.display === 'flex') {
        Nav.style.display = 'none';
      } else {
        Nav.style.display = 'flex';
      }
    });
    },

},
mounted() {
  this.menu();
 
 
}}



</script>







<style scoped>



.nav-container{
    background-color: #fce038;
   display: flex;
   justify-content: space-around;
   align-items: center;
   height: 5vh;
position: fixed;
z-index: 1;
 width: 100%;
}

.link{
    font-weight: bold;
  
    margin-left: 5rem;
    color: #fefefe;
    padding: 5px 3px;
    transition: 0.5s;
    text-decoration: none;
}
.link:hover{
      border-left: 2px solid white;
    color: #0411fd;
}


#botao {
    display: none;
}

 
#logos{
    text-decoration: none;
    color: #ffffff;
  font-weight: bold;
  font-size: 24px;
  letter-spacing: 4px;
 }
 /*  responsivo  450px  */

 
@media (max-width:450px){

 #logos{
    text-decoration: none;
    color: #ffffff;
    }
.nav-container{
width: 100%;
  height: 50px;
}  
    #botao{
      width: 3rem;
      height:50px;
    display: block;
    transition: 0.5s;
    }
  #botao:hover{
    background-color: white;
    border: 2px solid #fcba02;
  
  }   

#nav{

 z-index: 1;
    position: absolute;
    top: 50rem;
    right: 0;
    width: 100vw;
    height: 80vh;
    display:none;
    flex-direction: column;
    align-items: center;
    justify-content: space-around;


}

.link{
    text-align: center;
    margin-left: 0;
     font-size: 10px;
     width: 6rem;
     transition: 0.5s;
     color: #030bff;
     font-size: 20px;
}

.link:hover{

text-decoration: underline;
border-radius: 10px;
color: #222
}

}


 @media  (max-width:800px) {
  

 

 #logos{
    text-decoration: none;
    color: #fdfcf9;
    }
.nav-container{
 
  height: 50px;
}  
    #botao{
      width: 3rem;
      height:50px;
    display: block;
    transition: 0.5s;
    }
  #botao:hover{
    background-color: white;
    border: 2px solid #fcba02;
    border-top-left-radius: 10px;
  }   

#nav{
 z-index: 1;
    position: absolute;
    top: 5vh;
    right: 0;
    width: 30vw;
    height: 25vh;
    display:none;
    flex-direction: column;
    align-items: center;
    justify-content: space-around;


}

.link{
    text-align: center;
    margin-left: 0;
     color: #fcba02;
     width: 6rem;
     transition: 0.5s;
}

.link:hover{
background-color:#fcba02 ;
text-decoration: underline;
border-radius: 10px;
color: #222
}


 }





        
    
       
    

</style>
