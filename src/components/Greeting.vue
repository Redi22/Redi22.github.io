<template>
  <v-row justify="center">
    <v-col class="intro">
      <p class="titleText">Who am I?</p>
      <p
        class="normalText"
      >Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur fringilla efficitur quam, nec ornare tortor consequat vel. Sed sollicitudin pulvinar condimentum. Vestibulum tristique mi id dolor pretium, ut finibus ex scelerisque. Ut aliquam tellus eu est vehicula dapibus. Cras sem felis, semper non fringilla sit amet, euismod ut est. Phasellus imperdiet purus facilisis, auctor augue eu, consequat ante. Nulla sit amet tempor felis, ut vulputate neque. Sed et lectus nulla. In enim sem, mattis ultrices interdum eget, convallis at arcu. Suspendisse rhoncus mattis ullamcorper.</p>
    </v-col>
    <v-col class="intro">
      <div class="location">
        <v-row>
          <v-col cols="2">
            <p class="names">Location:</p>
          </v-col>
          <v-col>
            <p class="normalText">Addis Abab , Ethiopia</p>
          </v-col>
        </v-row>
        <v-row>
          <v-col cols="2">
            <p class="names">Email:</p>
          </v-col>
          <v-col>
            <p class="normalText">redidemisse22@gmail.com</p>
          </v-col>
        </v-row>
        <v-row>
          <v-col cols="2">
            <p class="names">Github:</p>
          </v-col>
          <v-col>
            <p class="normalText">Redi22</p>
          </v-col>
        </v-row>
      </div>
    </v-col>
  </v-row>
</template>
<script>
export default {};
</script>
<style>
.titleText {
  font-size: 30pt;
  color: gold;
  margin-left: 30px;
}
.intro {
  margin: 20px;
}
.location {
  margin: 50px;
}
.names {
  color: gold;
}
.normalText {
  color: whitesmoke;
}
</style>