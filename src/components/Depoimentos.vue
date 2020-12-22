<template>
  <div class="customContainer">
    <h1>Depoimentos</h1>
    <div class="depoimentosContainer">
      <div class="depoimento">
     
             <v-avatar class="imgStyle">
          <img  src="../assets/depoimentsOne.png" alt="Miyamoto Fujii" />
        </v-avatar>
  
       
          <span class="personName">Miyamoto Fujii</span>
          <p class="textStyle">“Usei  o sistema para gerenciar as minhas pacientes, e não poderia estar mais satisfeita. A forma de comunicação disponibiza um meio de tirar as duvidas, sem que a gestante saia de casa, evitando assim, extresses desnecessarios.”</p>
      </div>

          <div class="depoimento">
        <v-avatar class="imgStyle">
          <img src="../assets/depoimentsTwo.png" alt="John" />
        </v-avatar>
          <span class="personName">Abigail Silva</span>
          <p class="textStyle"> “A cada dia que passa, mais fico maravilhada com a praticidade do Preneonatal , eu consigo gerenciar todas as minhas pacientes sem precisar de ajuda e tudo isso em poucos minutos.”</p>
      </div>

       <div class="depoimento">
        <v-avatar class="imgStyle">
          <img src="../assets/depoimentsThree.png" alt="John" />
        </v-avatar>
          <span class="personName">Valentina Gomes</span>
          <p class="textStyle">“Fiquei muito satisfeita com o aplicativo, a função de gerenciamente de risco me deixou mais focada na saúde da minha gestação.”</p>
      </div>
    </div>
    <v-container class="socialWrapper">
          <div class="socialContainer">
      <div class="itemSocialBox">
          <v-icon>mdi-facebook</v-icon>
      </div>
      <div class="itemSocialBox">

        <v-icon>mdi-instagram</v-icon>
      </div>
      <div class="itemSocialBox">

          <v-icon>mdi-twitter</v-icon>
      </div>
    </div>
    </v-container>
  
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.customContainer {
  height: 100vh;
  width: 100vw;
  background-color: #806676;
  display: flex;
  flex-direction: column;
  align-content: center;
  
}
.depoimento{
  width: 20%;
  display: flex;
  flex-direction: column;
  padding: 1%;
  align-self: center;
 
}
.depoimentosContainer{

  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  justify-self: center;
  align-self: center;
  height: 70%;
}
.textStyle{
  font-size: 0.8rem;
  color: white;
  text-align: center;


}.personName{
  font-weight: bold;
  color: white;
  align-self: center;
}
.avatarWrapper{
  display: flex;
  width: 100%;
  flex-direction: column;
  justify-self: center;
  align-self: center;
}
.imgStyle{
  align-self: center;
}

.itemSocialBox{
  background-color: white;
  display: inline-block;

      height: 100%;
    
    width: 15%;
    border-radius: 4%;
    display: flex;
    justify-content: center;
}
.socialWrapper{
      height: 10%;
    width: 20%;
}
</style>