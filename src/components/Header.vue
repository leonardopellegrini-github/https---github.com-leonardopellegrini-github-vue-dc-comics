<template>
  
    
    <div class="head container d-flex justify-content-between align-items-center">

      <div class="sx">
        <img src="../img/dc-logo.png" alt="Logo">
      </div>
      <div class="dx">
        <ul class="d-flex justify-content-between align-items-center">
          <li :key="`menu-${index}`" v-for="(Menulink, index) in MenuLinks" :class="Menulink.attivo ">{{Menulink.nome}}</li>
        </ul>
      </div>

    </div>
  
</template>

<script>
export default {
  name: "HeaderNuovo",
  data(){
    return{
      MenuLinks: [
        {
          nome: "Characters",
          link: "#",
          attivo: "",
        },
        {
          nome: "Comics",
          link: "#",
          attivo: "",
        },
        {
          nome: "Movies",
          link: "#",
          attivo: "attivo",
        },
        {
          nome: "TV",
          link: "#",
          attivo: "",
        },
        {
          nome: "Games",
          link: "#",
          attivo: "",
        },
        {
          nome: "Collectibles",
          link: "#",
          attivo: "",
        },
        {
          nome: "Videos",
          link: "#",
          attivo: "",
        },
        {
          nome: "Fans",
          link: "#",
          attivo: "",
        }
      ]
    }
  }
}
</script>


<style scoped lang="scss">

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

.attivo{
  border-bottom: 3px solid blue;
}

</style>
