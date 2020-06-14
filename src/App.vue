<template>
  <v-app dark>
    <div class="back">
      <v-navigation-drawer app dark permanent>
        <v-list>
          <v-list-item class="px-2"></v-list-item>

          <v-list-item link>
            <v-list-item-content>
              <v-list-item-title class="title">REDIET DEMISSE</v-list-item-title>
              <v-list-item-subtitle>redidemisse22@gmail.com</v-list-item-subtitle>
            </v-list-item-content>
          </v-list-item>
        </v-list>

        <v-list nav>
          <v-list-item link>
            <v-list-item-icon>
              <v-icon>mdi-folder</v-icon>
            </v-list-item-icon>
            <v-list-item-title>My Files</v-list-item-title>
          </v-list-item>
          <v-list-item link class="navBar">
            <v-list-item-icon>
              <v-icon>mdi-account-multiple</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Shared with me</v-list-item-title>
          </v-list-item>
          <v-list-item link class="navBar">
            <v-list-item-icon>
              <v-icon>mdi-star</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Starred</v-list-item-title>
          </v-list-item>
          <v-list-item link class="navBar">
            <v-list-item-icon>
              <v-icon>mdi-star</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Starred</v-list-item-title>
          </v-list-item>
          <v-list-item link class="navBar">
            <v-list-item-icon>
              <v-icon>mdi-star</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Starred</v-list-item-title>
          </v-list-item>
        </v-list>
      </v-navigation-drawer>
      <v-content>
        <p class="name">REDIET DEMISSE</p>
        <p class="greet">FRONT-END DEVELOPER</p>
        <Greeting />

        <Skills />
      </v-content>
    </div>
  </v-app>
</template>

<script>
import Greeting from "@/components/Greeting.vue";
import Skills from "@/components/Skills.vue";

export default {
  name: "App",
  components: {
    Greeting,
    Skills
  },
  data: () => ({
    //
  })
};
</script>
<style lang="css">
.back {
  background: url("./assets/hero.png");
  background-size: contain;
}
.greet {
  font-size: 70pt;
  color: goldenrod;
  margin-left: 30px;
  margin-top: -45px;
}
.name {
  color: whitesmoke;
  font-size: 40pt;
  margin-left: 640px;
  margin-top: 450px;
}
.navBar {
  margin-top: 40px;
}
</style>
