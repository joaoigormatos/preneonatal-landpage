<template>
    <div class="customAppBar">
       <v-img class="customLogo" max-width="10%" src="../assets/logo-project.png"></v-img>
       <button class="loginButton">

       <span >Entrar</span>
       <v-icon color="white">mdi-login</v-icon>
       </button>
    </div>
</template>

<script>
export default {
    // The App bar need to stay without color until pass the hero component, after that the appbar will be fiiled in with the pink color
    // The container need to be fitted into the viewport of the user
}
</script>

<style >
    .customAppBar{
        position: fixed;
        width: 100%;
        color: red;
        z-index: 50;
        display: flex;
        flex-direction: row;
        justify-content: center;
    }
   .customLogo{

   }
   .loginButton{
       color: white;
       align-self: flex-end;
   }

</style>