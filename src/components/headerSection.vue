<template>
  <div class="header">
     <div class="container">
<!--  Available credit -->
  <div class="float-right pt-4">Available Credit:3,21,457
    <!-- <b-nav-item-dropdown text="" right>
    </b-nav-item-dropdown> -->
  <button class="btn btn-secondary dropdown-toggle float-right" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
    </button>

    
       </div>
     </div>    


     <!-- logo -->
      <img src="@/assets/login-logo.png" alt="login-logo" class = "logo">
  </div>
</template>

<script>
export default {};
</script>

<style scoped lang="scss">
.header {
  background: white;
  justify-content: center;
}
.logo {
  padding-top: 10px;
  padding-bottom: 10px;
  max-width: 150px;
  display: block;
  margin-left: auto;
  margin-right: auto;

  float: center;
  margin: center;
  max-width: 250px;
  padding-left: 125px;
}
.btn-secondary {
  color: black;
  background-color: transparent;
  border-color: transparent;
  padding-top: 2px;
}
</style>
