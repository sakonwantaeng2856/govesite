<template>
  <div>
    <v-app-bar fixed flat color="white">
      <v-col cols="4">
        <img
          width="300"
          height="55"
          src="../assets/logo/Logo-newgovesite.gif"
        />
      </v-col>
      <v-col cols="4" class="text-center">
        <a href="#spot" class="ml-5 nuxt-link-active">คุณสมบัติ</a>
        <a href="#pricing" class="ml-5 nuxt-link-active">แพคเกจ</a>
        <a href="#contact" class="ml-5 nuxt-link-active">ติดต่อเรา</a>
      </v-col>
      <v-col cols="4">
        <div class="float-right">
          <NuxtLink to="/login" class="mr-5">เข้าสู่ระบบ</NuxtLink> |
          &ensp;&ensp;
          <v-btn to="/register" class="green" color="success"
            >สมัครใช้งาน</v-btn
          >
        </div>
      </v-col>
    </v-app-bar>
  </div>
</template>

<script>
export default {}
</script>

<style>
@import '../assets/navbar.css';
</style>
