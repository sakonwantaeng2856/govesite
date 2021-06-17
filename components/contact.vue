<template>
  <v-row id="contact" class="green darken-4 contact">
    <v-col class="content mt-8 mb-12">
      <v-card class="mx-auto" width="1000">
        <v-container>
          <v-card-text id="tablecon" class="tablecon">
            <h1 class="head mb-8 black--text">ส่งข้อความถึงเรา</h1>
            <v-text-field
              class="text10"
              label="ชื่อ-นามสกุล"
              outlined
            ></v-text-field>
            <v-text-field class="text10" label="Email" outlined></v-text-field>
            <v-textarea
              class="text12"
              height="220"
              outlined
              name="input-7-4"
              label="ข้อความของคุณ.."
            ></v-textarea>
            <v-btn class="success">Register</v-btn>
          </v-card-text>
        </v-container>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'Contact',
}
</script>

<style>
@import '../assets/contact.css';
</style>
