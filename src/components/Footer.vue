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
    <div class="container">
      <div class="row justify-content-between">

        <div class="col-2 SxMenu d-flex flex-wrap flex-column">

          <h5 class="title">DC COMICS</h5>
          <ul class="menu">
            <li>Menu</li>
            <li>Menu</li>
            <li>Menu</li>
            <li>Menu</li>
            <li>Menu</li>
          </ul>

          <h5 class="title">DC COMICS</h5>
          <ul class="menu">
            <li>Menu</li>
            <li>Menu</li>
          </ul>

        </div>

        <div class="col SxMenu d-flex flex-wrap flex-column">
          
          <h5 class="title">SHOP</h5>
          <ul class="menu">
            <li>Menu</li>
            <li>Menu</li>
            <li>Menu</li>
            <li>Menu</li>
            <li>Menu</li>
            <li>Menu</li>
            <li>Menu</li>
            <li>Menu</li>
            <li>Menu</li>
            <li>Menu</li>
          </ul>

        </div>

        <div class="col SxMenu d-flex flex-wrap flex-column">
          
          <h5 class="title">SHOP</h5>
          <ul class="menu">
            <li>Menu</li>
            <li>Menu</li>
            <li>Menu</li>
            <li>Menu</li>
            <li>Menu</li>
            <li>Menu</li>
            <li>Menu</li>
            <li>Menu</li>
            <li>Menu</li>
            <li>Menu</li>
          </ul>

        </div>

        <div class="col-6 DxMenu">

        </div>

      </div>
    </div>
  </div>

  <div class="Down d-flex align-items-center">
     <!--FOOTER BASSO-->
    <div class="container d-flex justify-content-between align-items-center">

      <div class="">
        <h4>SIGN-UP</h4>
      </div>

      <div class="">
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
  height: 400px;
  padding: 30px;
}

.menu{
  margin: 0;
}

.SxMenu{
  padding-top: 30px
}

.SxMenu ul li{
   list-style: none;
   color: #7B7B7B;
   font-weight: 400;
}
.SxMenu ul{
   padding: 0;
   padding:10px 0px;
}

.DxMenu{
  background-image: url(@/img/dc-logo-bg.png);
  background-size: cover;
  background-position: right;
  height: 400px;
}

.Down{
  background-color: #303030;
  height: 80px;
}



</style>