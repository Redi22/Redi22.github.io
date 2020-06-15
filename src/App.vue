<template>
  <v-app dark app>
    <div class="back">
      <v-navigation-drawer color="#000" app permanent>
        <v-list class="white--text">
          <v-list-item class="px-2"></v-list-item>

          <div class="px-2">
            <v-img class="mx-12" src="./assets/Final LOGO.png"></v-img>
            <v-list-item-title class="title">REDIET DEMISSE</v-list-item-title>
            <v-list-item-subtitle>redidemisse22@gmail.com</v-list-item-subtitle>
          </div>
        </v-list>

        <v-list nav>
          <v-list-item link>
            <!-- <v-list-item-icon>
              <v-icon>mdi-folder</v-icon>
            </v-list-item-icon>-->
            <v-list-item-title class="white--text">About Me</v-list-item-title>
          </v-list-item>
          <v-list-item link class="navBar">
            <!-- <v-list-item-icon>
              <v-icon>mdi-account-multiple</v-icon>
            </v-list-item-icon>-->
            <v-list-item-title class="white--text">Projects</v-list-item-title>
          </v-list-item>
          <v-list-item link class="navBar">
            <!-- <v-list-item-icon>
              <v-icon>mdi-star</v-icon>
            </v-list-item-icon>-->
            <v-list-item-title class="white--text">Skills and Education</v-list-item-title>
          </v-list-item>
          <v-list-item link class="navBar">
            <!-- <v-list-item-icon>
              <v-icon>mdi-star</v-icon>
            </v-list-item-icon>-->
            <v-list-item-title class="white--text">Contacts</v-list-item-title>
          </v-list-item>
          <div class="navBar">
            <v-row justify="space-between" class="mx-12">
              <v-btn icon link class="white--text" href="https://twitter.com/DemisseRediet">
                <v-icon>mdi-twitter</v-icon>
              </v-btn>
              <v-btn icon link class="white--text" href="http://github.com/Redi22">
                <v-icon link class="white--text" href="http://github.com/Redi22">mdi-github</v-icon>
              </v-btn>
              <v-btn icon link class="white--text" href="http://github.com/Redi22">
                <v-icon link class="white--text">mdi-linkedin</v-icon>
              </v-btn>
            </v-row>
          </div>
        </v-list>
      </v-navigation-drawer>
      <v-content app>
        <p class="name">REDIET DEMISSE</p>
        <p class="greet">FRONT-END DEVELOPER</p>
        <Greeting />
        <Skills />
        <Education />
        <Contact />
      </v-content>
    </div>
  </v-app>
</template>

<script>
import Greeting from "@/components/Greeting.vue";
import Skills from "@/components/Skills.vue";
import Education from "@/components/Education.vue";
import Contact from "@/components/Contact.vue";

export default {
  name: "App",
  components: {
    Greeting,
    Skills,
    Contact,
    Education
  },
  data: () => ({
    //
  })
};
</script>
<style lang="css">
.v-list-item__content {
  justify-content: center;
  text-align: left;
  display: grid;
}
.back {
  background-image: url("./assets/hero.png"), url("./assets/image.png"),
    url("./assets/image - Copy.png");
  background-size: contain, 100%, 70%;
  background-color: #242525;
  background-origin: content-box;
  background-repeat: no-repeat, no-repeat;
  background-position: top center, center center, bottom right;
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
.titleText {
  font-size: 30pt;
  color: gold;
  margin-left: 30px;
}
.navBar {
  margin-top: 20px;
}
.navMain {
  background-color: #111111;
}
</style>
