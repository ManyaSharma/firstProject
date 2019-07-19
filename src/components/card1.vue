<template>
<div class="container">

<div class="row">
<div class="col-md-6"> 
<div class="card-body">
<div class="title">
<div class="image-one">
<img src="../assets/casiono-btn.png" alt="Card Image" class="img-loading">
</div>

<div class="button-one">
    <!-- <button class="button"> CASINO </button> -->
<button type="button" class="btn btn-primary btn-lg mt-3 btn-look"> CASINO </button>
</div>

</div>
</div>
</div>


<div class="col-md-6">
<div class="card-body">
<div class="title">
<div class="image-two">
<img src="../assets/sportbook-btn.png" alt="Card Image" class="img-loading">
</div>

<div class="button-two"> 
    <!-- <button class="button"> SPORTSBOOK </button> -->
<button type="button" class="btn btn-primary btn-lg mt-3 btn-look"> SPORTSBOOK </button>

</div>

</div>
</div>
</div>
</div>
</div>
</template>
<script>
export default {};
</script>

<style lang="scss" scoped>
.title {
  background: black;
  justify-content: center;
  align-items: center;
  width: 75%;
  padding: 36px;
}

.btn-look {
  background-color: #967007;
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
  width: 100%;
  border-radius: 0px;
}
.img-loading {
  width: 100%;
}
</style>
