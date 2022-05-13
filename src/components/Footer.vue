<template>
  
<div class="footer">
  <div class="Up d-flex align-items-center">
    <!-- BLOCCO ICONE-->
    <div class="container d-flex align-items-center justify-content-around">
      <ul class="menu">
            <li><img src="@/img/buy-comics-digital-comics.png" alt="1"> DIGITAL COMICS</li>
            <li><img src="@/img/buy-comics-merchandise.png" alt="2"> DIGITAL COMICS</li>
            <li><img src="@/img/buy-comics-shop-locator.png" alt="3"> DIGITAL COMICS</li>
            <li><img src="@/img/buy-comics-subscriptions.png" alt="4"> DIGITAL COMICS</li>
            <li><img src="@/img/buy-dc-power-visa.svg" alt="5">DIGITAL COMICS</li>
          </ul>
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
        <a id="signUP" href="#">SIGN-UP NOW!</a>
      </div>

      <div class="dxDown d-flex flex-row align-items-center">
        <h5>FOLLOW US</h5>
      
            <img src="@/img/footer-facebook.png" alt="">
            <img src="@/img/footer-periscope.png" alt="">
            <img src="@/img/footer-pinterest.png" alt="">
            <img src="@/img/footer-twitter.png" alt="">
            <img src="@/img/footer-youtube.png" alt="">
        
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

//BLOCCO ICONE---------

.Up{
  background-color: #0282F9;
  height: 100px;
}

.Up ul li, .Down ul li{
  list-style: none;
  display: inline;
  font-size: 16px;
}

.Up img{
  height: 75px;
  
  padding: 20px;
}

//BLOCCO MENU FOOTER---------

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

//FOOTER BASSO---------
.Down{
  background-color: #303030;
  height: 80px;
}

#signUP{
  color: white;
  border: 3px solid #0282F9;
  padding: 10px;
}

.Down h5{
  color: #0282F9;
  font-weight: 500;
}

.dxDown img{
  padding: 5px
}

.dxDown h5{
  margin: 0;
}

</style>