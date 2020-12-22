<template>
    <v-container class="customContainer">
          <v-container class="contentContainer">
              
          <div class="imagesContainer">

          <v-img class="customImg" src="../assets/app-hero-side.png" max-height="auto" max-width="20%"></v-img>
          <v-img src="../assets/app-hero-front.png" max-height="100%" max-width="25%"></v-img>
          </div>
          <div class="headerContent">

                <h1 class="headerText">Suas gestantes seguras e orientadas</h1>
                <p class="mainText">Uma nova forma de comunicação entre você e suas pacientes. Procuramos uma maior interação entre medicos e gestantes, deixando ambos infomados.</p>
                <v-img class="btnGetItOn" src="../assets/getiton-app.png" ></v-img>
          </div>
           


      
       
      
          </v-container>
        
    </v-container>
</template>

<script>
export default {

}
</script>

<style scoped>
 .customContainer{
    height: 100vh;
    width: 100vw;
    background-size: 100% 100%;
    background-repeat: no-repeat;
    background-blend-mode: color;
    background-image: url('../assets/background-hero.png') ;
    min-width: 100%;     
      margin: 0 auto;
   padding: 0;


    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;

 }
 .customContainer::before{
   content: "";
   width: 100%;
   height: inherit;
   position: absolute;
   background: black;
   opacity: 0.2;
 }
 .imgContainer{
   display: flex;
  
 }
 .customImg{
   margin-right: 5%;
 }
 .customInnerContainer{
   display: flex;
   flex-direction: row;
 }
 .contentContainer{

      display: flex;
   flex-direction: row;
   justify-content: center;
   align-content: center;
 }
 .imagesContainer{
   width: 50%;
   display: flex;
   flex-direction: row;
   justify-content: center;
   align-items: center;
 }
 .headerContent{
   width: 50%;
   display: flex;
   flex-direction: column;
   justify-content: center;
   align-items: center;

 }

 .btnGetItOn{
   flex: 0 1 auto;
   cursor: pointer;
 }

 .headerText{
   color: white;
   font-weight: 100;
   font-size: 2.5rem;
  filter: brightness(100%);
  text-align: justify;
  align-self: flex-start;
 }
 .mainText{
   color: white;
   text-align: justify;
   font-family: 'Open Sans';
     filter: brightness(95%);

     font-size: 0.9rem;
         margin-left: 0.2%;
    margin-top: 2%;
    margin-bottom: 4%;

 }

</style>