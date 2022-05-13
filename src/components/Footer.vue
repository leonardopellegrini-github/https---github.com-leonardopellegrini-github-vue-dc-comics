<template>
  
<div class="footer">
  <div class="Up d-flex align-items-center">
    <!-- BLOCCO ICONE-->
    <div class="container align-items-center justify-content-center">
      icone
    </div>
  </div>

  <div class="Mid d-flex align-items-center">
    <!-- BLOCCO MENU FOOTER-->
    <div class="footer container">
      <div class="col-2 SxMenu">

      </div>
      <div class="col-6 DxMenu">

      </div>
    </div>
  </div>

  <div class="Down d-flex align-items-center">
     <!--FOOTER BASSO-->
    <div class="container d-flex justify-content-between align-items-center">

      <div class="sx">
        <h4>SIGN-UP</h4>
      </div>

      <div class="dx">
        <h4>FOLLOW US</h4>
      </div>

    </div>
  </div>

</div> 
  

</template>

<script>
export default {
  name: "FooterNuovo",
}
</script>


<style scoped lang="scss">

.footer{
  color: white;
}

.Up{
  background-color: #0282F9;
  height: 100px;
}

.Mid{
  background-image: url(@/img/footer-bg.jpg);
  height: 100px;
}

.SxMenu{
  background-color: red;
  height: 10px;
}

.DxMenu{
  background-color: blue;
  height: 10px;
}

.Down{
  background-color: #303030;
  height: 80px;
}



</style>