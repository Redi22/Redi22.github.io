<template>
  <div>
    <v-row justify="center">
      <h1 class="yellow--text mx-12">EDUCATION & SKILLS</h1>
    </v-row>
    <v-row class="ma-12">
      <v-col cols="6">
        <h3 title class="yellow--text">Web Develpment</h3>
        <v-row justify="center">
          <v-col cols="3">
            <v-card-text class="white--text">HTML / CSS</v-card-text>
          </v-col>
          <v-col>
            <v-rating
              :value="rate"
              readonly
              color="primary"
              empty-icon="mdi-circle-outline"
              full-icon="mdi-circle"
              size="20"
              half-icon="mdi-circle-half-full"
            ></v-rating>
          </v-col>
        </v-row>
        <v-row justify="center">
          <v-col cols="3">
            <v-card-text class="white--text">JS</v-card-text>
          </v-col>
          <v-col>
            <v-rating
              :value="rate"
              readonly
              size="20"
              color="primary"
              empty-icon="mdi-circle-outline"
              full-icon="mdi-circle"
              half-icon="mdi-circle-half-full"
            ></v-rating>
          </v-col>
        </v-row>
        <v-row justify="center">
          <v-col cols="3">
            <v-card-text class="white--text">VUE JS</v-card-text>
          </v-col>
          <v-col>
            <v-rating
              :value="rate"
              size="20"
              readonly
              color="primary"
              empty-icon="mdi-circle-outline"
              full-icon="mdi-circle"
              half-icon="mdi-circle-half-full"
            ></v-rating>
          </v-col>
        </v-row>
        <h3 title class="yellow--text mt-12">Mobie App Develpment</h3>

        <v-row justify="center">
          <v-col cols="3">
            <v-card-text class="white--text">VUE JS</v-card-text>
          </v-col>
          <v-col>
            <v-rating
              :value="rate"
              size="20"
              readonly
              color="primary"
              empty-icon="mdi-circle-outline"
              full-icon="mdi-circle"
              half-icon="mdi-circle-half-full"
            ></v-rating>
          </v-col>
        </v-row>
        <h3 title class="yellow--text mt-12">Desktop App Develpment</h3>

        <v-row justify="center">
          <v-col cols="3">
            <v-card-text class="white--text">VUE JS</v-card-text>
          </v-col>
          <v-col>
            <v-rating
              :value="rate"
              size="20"
              readonly
              color="primary"
              empty-icon="mdi-circle-outline"
              full-icon="mdi-circle"
              half-icon="mdi-circle-half-full"
            ></v-rating>
          </v-col>
        </v-row>
      </v-col>

      <v-col cols="6">
        <v-row>
          <v-divider class="yellow" vertical></v-divider>
          <br />
          <p title class="mx-2 white--text">Studying My Bachelor at</p>
          <h3 class="yellow--text">Addis Ababa Scince and Technology Universtity</h3>
        </v-row>
        <v-list-item link href="http://www.aastu.edu.et" target="_blank">
          <v-icon class="yellow--text">mdi-school</v-icon>
          <v-list-item-title class="white--text mx-2">aastu.edu.et</v-list-item-title>
        </v-list-item>
        <v-spacer />
        <h3 title class="yellow--text mt-12">Soft Skills</h3>

        <v-row justify="center">
          <v-col cols="3">
            <v-card-text class="white--text">VUE JS</v-card-text>
          </v-col>
          <v-col>
            <v-rating
              :value="rate"
              size="20"
              readonly
              color="primary"
              empty-icon="mdi-circle-outline"
              full-icon="mdi-circle"
              half-icon="mdi-circle-half-full"
            ></v-rating>
          </v-col>
        </v-row>
        <v-row justify="center">
          <v-col cols="3">
            <v-card-text class="white--text">VUE JS</v-card-text>
          </v-col>
          <v-col>
            <v-rating
              :value="rate"
              size="20"
              readonly
              color="primary"
              empty-icon="mdi-circle-outline"
              full-icon="mdi-circle"
              half-icon="mdi-circle-half-full"
            ></v-rating>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
  </div>
</template>
<style scooped>
.titleText {
  font-size: 10pt;
  color: gold;
  margin-left: 30px;
}
</style>
<script>
export default {
  data() {
    return {
      rate: 2
    };
  }
};
</script>