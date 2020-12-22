<template>
  <div class="customAppBar">
    <v-img
      class="customLogo"
      max-width="10%"
      src="../assets/logo-project.png"
    ></v-img>
    <div class="loginButton">
      <span>Entrar</span>
      <v-icon color="white">mdi-login</v-icon>
    </div>
  </div>
</template>

<script>
export default {
  // The App bar need to stay without color until pass the hero component, after that the appbar will be fiiled in with the pink color
  // The container need to be fitted into the viewport of the user
};
</script>

<style >
.customAppBar {
  position: fixed;
  width: 100%;
  background-color: #f8c9d3;
  z-index: 50;
  display: flex;
  flex-direction: row;
  justify-content: center;
  
  padding: 0.3%;
}

.loginButton {
  display: flex;
  color: white;
  justify-self: flex-end;
  cursor: pointer;
}
</style>