<template>
  <div class="customContainer">
    <v-container class="mainContainer">
      <div class="footerContainerAboutUs">
        <h1 >Sobre nos</h1>
            <div class="aboutUsItem">
             <img class="imgIcon" src="../assets/email.svg" alt=""> <span class="headerText">E-mail: </Span>preneonatal@gmail.com
            </div>
            <div class="aboutUsItem">
             <img class="imgIcon" src="../assets/cellphone.svg" alt=""> <span class="headerText">Celular: </span>(55)85992755778
            </div>
            <div class="aboutUsItem">
             <img class="imgIcon" src="../assets/location.svg" alt=""> <span class="headerText">Endereço: </span> Maria Luiza Noronha, 220
            </div>
            

      </div>
      <div class="footerContainerAskus">
        <h1 class="">Pergunte</h1>
        <form class="formStyle" action="">
          <div class="itemForm">
            <input class="nameInput" placeholder="Nome" type="text"/>
            <input class="nameInput" placeholder="Sobrenome" type="text"/>
          </div>
        


           <input placeholder="Email" type="text"/>
       
           <textarea placeholder="Como podemos ajudar" name="" id="" cols="3" rows="3"></textarea>
           <button class="btnStyle">enviar</button>
        </form>
      </div>

    </v-container>
  <div class="right">
                © Preneonatal 2020.  All rights reserved. 
        </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.right{
  font-size: 0.6rem;
}
.headerText{
  font-weight: 550;
}
.imgIcon{
  width: 6%;
}
.itemForm{
  width: 100%;
  display: flex;
  justify-content: space-between;
}
 .customContainer{
     height: 45vh;
     width: 100vw;
     background-color: black;
     color: white;

 }
 .right{
   margin: 0;
   display: flex;
   align-self: flex-end;
 }

 .aboutUsItem{
     font-family: 'Roboto Slab';
     font-size: 0.9rem;
     margin-bottom: 8%;
 }
 .center{
  font-size: 3rem;
  text-align: center;
  font-weight: 300;
  color: white;
}
  .mainContainer{
    display: flex;
    justify-content: space-around;
  }
input[type= text]{
    border: 1px solid gray;
    background-color: #C5C6C7;
    padding: 0.5%;
    margin-bottom: 1%;
}
::placeholder{
  color: black;
  font-family: 'Roboto Slab';
  font-size: 0.8rem;
}

textarea{
    border-color: 4px solid white;
        background-color: #C5C6C7;
    margin-bottom: 5%;
}
.footerContainerAskus{
  display: flex;
  flex-direction: column;
}
.formStyle{
  display: flex;
  flex-direction: column;
}
.nameInput{
  width: 49%;
}
.btnStyle{
  border: 1px solid white;
  
  width: 30%;
  padding: 2%;
  align-self: center;
}
h1{ 
  font-family: 'Roboto Slab';
  font-weight: 300;
  padding: 1%;
}
</style>