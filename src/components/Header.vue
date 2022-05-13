<template>
  
  
    <div class="head container d-flex justify-content-between align-items-center">

      <div class="sx">
        <img src="../img/dc-logo.png" alt="Logo">
      </div>
      <div class="dx">
        <ul class="d-flex justify-content-between align-items-center">
          <li>Comics</li>
          <li>Movies</li>
          <li>TV</li>
          <li>GAMES</li>
          <li>Movies</li>
        </ul>
      </div>

    </div>
  
</template>

<script>
export default {
  name: "HeaderNuovo",
}
</script>


<style lang="scss">

.head{
  height: 100px;
}

.head img{
  width: 70%;
}

ul li {
    display: inline;
    text-transform: uppercase;
    font-weight: 500;
    padding: 10px;
    font-size: 12px;
}

</style>
