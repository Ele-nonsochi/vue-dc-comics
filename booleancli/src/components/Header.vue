<template>
<div class="nav-bar">
     <img alt="Vue logo" src="../assets/img/dc-logo.png">
     <ul>
         <li class="navbar-choice" v-for="(item, i) in navbarChoice" :key="i">
          <a>{{ item.title }}</a>
         </li>
     </ul>

</div>
</template>

<script>
export default{
    name: "Header",

     data() {
    return {
      navbarChoice: [
        {
          title: "CHARACTERS",
          href: "#",
        },
        {
          title: "COMICS",
          href: "#prodotti",
        },
        {
          title: "MOVIES",
          href: "#chi_siamo",
        },
        {
          title: "TV",
          href: "#contatti",
        },
        {
          title: "GAMES",
          href: "#contatti",
        },
        {
          title: "COLLECTIBLES",
          href: "#contatti",
        },
        {
          title: "VIDEO",
          href: "#contatti",
        },
        {
          title: "FANS",
          href: "#contatti",
        },
        {
          title: "NEWS",
          href: "#contatti",
        },
         {
          title: "SHOP",
          href: "#contatti",
        },
      ],
    
    };
}
}

</script>

<style lang="scss">
  
</style>