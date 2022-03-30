<template>
  <v-app-bar app elevation="5" elevate-on-scroll class="navbar" id="navbar">
    <div class="container">
      <v-row>
        <v-img
          alt="Vuetify Logo"
          class="shrink"
          contain
          src="@/assets/logo.png"
          transition="scale-transition"
          width="50"
        />

        <ul>
          <li><router-link to="/" class="link">Home</router-link></li>
          <li><router-link to="/" class="link">Location</router-link></li>
          <li><router-link to="/" class="link">About</router-link></li>
          <li><router-link to="/contact" class="link">Contact</router-link></li>
        </ul>
      </v-row>
    </div>
  </v-app-bar>
</template>

<script>
// const navbar = document.getElementById("navbar");

// window.addEventListener("scroll", function () {
//   if (window.scrollY > 50) {
//     navbar.style.background = "transparent !important";
//   } else {
//     navbar.style.background = "transparent";
//   }
// });

export default {};
</script>

<style scoped>
/* .navbar { */
/* background: #d5d7d6 !important; */
/* background: white !important; */
/* } */

.link {
  color: inherit;
  text-decoration: none;
}

ul {
  font-weight: 700;
  font-size: 18px;
  list-style: none;
  display: flex;
  width: 40%;
  justify-content: space-between;
  align-items: center;
}
</style>
