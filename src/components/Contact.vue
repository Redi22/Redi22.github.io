<template>
  <v-row justify="center">
    <v-card color="#222222" dark width="45%" class="pa-4">
      <h2 class="mx-5">Want to Talk?</h2>
      <v-form class="ma-6">
        <v-text-field class="primary--text" outlined dense label="Email" v-model="email"></v-text-field>
        <v-text-field class="primary--text" outlined dense label="Name" v-model="name"></v-text-field>
        <v-text-field class="primary--text" outlined dense label="Subject" v-model="subject"></v-text-field>
        <v-textarea class="primary--text" outlined label="Message" v-model="message"></v-textarea>
        <v-row justify="center">
          <v-btn class="primary black--text">Send</v-btn>
        </v-row>
      </v-form>
    </v-card>
  </v-row>
</template>
<script>
export default {
  data() {
    return {
      email: ""
    };
  }
};
</script>