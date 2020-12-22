<template>
<div class="mainContainer">
  <h1 class="center">Funcionalidades</h1>
    <div class="customContainer">
    <v-container class="containerCustom">
       <div class="contentContainer">
         <div class="textContainer">
            <h1>Acompanhe toda a gestação</h1>
            <p class="paragraphStyle">A Preneonatal, garante para as suas gestantes um acompanhamento completo da gestação com um design interativo e de fácil usabilidade, acompanhe semana a semana com dicas diárias, acompanhamento de peso e tamanhos aproximados do bebê</p>
         </div>
         <v-img contain  class="imgContainer" src="../assets/functionality01.png"></v-img>
       </div>
    </v-container>
  </div>
  <div class="customContainer">
    <v-container class="containerCustom">
        <div class="contentContainer">
         <v-img class="imgContainer" src="../assets/functionality02.png"></v-img>
         <div class="textContainer">
            <h1>Tire todas as duvidas</h1>
            <p class="paragraphStyle">Não perca mais a privacidade do seu contato, tenha em um app dedicado a função de chat para tirar dúvidas de suas gestantes.</p>
         </div>
       </div>
    </v-container>
  </div>
  <div class="customContainer">
    <v-container class="containerCustom">
       <div class="contentContainer">
         <div class="textContainer">
            <h1>Tire todas as duvidas</h1>
            <p class="paragraphStyle">A partir dos exames das pacientes seja notificado sobre mudança de risco, facilitando muito a prevenção de diabetes gestacional, anemia e várias outras doenças que necessitam de atenção constante.</p>
         </div>
         <v-img class="imgContainerNotebook" src="../assets/functionality03.png"></v-img>
       </div>
    </v-container>
  </div>
</div>

</template>

<script>
export default {

}
</script>

<style scoped>
.center{
  font-size: 3rem;
  text-align: center;
  font-weight: 300;
}
.paragraphStyle{
  text-align: justify;
}
.mainContainer{
  display: flex;
  flex-direction: column;
  
}
.containerCustom{
  height: inherit;
}
 .customContainer{
     height: 100vh;
     width: 100vw;
     background-color: white;
 }
 .contentContainer{
   width: 100%;
   display: flex;
   justify-content: space-around;
   align-items: center;
 }

 .imgContainer{
   max-width: 20%;

 }
 .imgContainerNotebook{
      max-width: 60%;
 }
 .textContainer{
   width: 50%;
 }
</style>