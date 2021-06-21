<template>
  <v-card class="mx-auto mt-4 mb-16" style="width: 500px; height: 640px">
    <div class="content mt-4 mr-4 ml-4 mb-4">
      <div class="menu-list">
        <v-row
          ><v-col class="text-left mt-6 mb-16">
            <a
              href="/"
              class="text-decoration-none black--text mr-2 ml-2 grey--text"
              ><span class="bi-arrow-left mx-1"> กลับหน้าหลัก </span>
            </a></v-col
          ><v-col class="text-right mt-6 mb-16">
            <p class="grey--text">
              ยังไม่บัญชีผู้ใช้ ?
              <a
                href="/register"
                class="text-decoration-none black--text mr-2 ml-2"
              >
                <b>สมัครสมาชิก</b>
              </a>
            </p>
          </v-col></v-row
        >
      </div>
      <div class="ml-3 mr-5">
        <div class="card-body login-card-body">
          <h1 class="login-box-msg mb-3">เข้าสู่ระบบ</h1>
          <p class="login-box-msg grey--text">
            เข้าสู่ระบบเพื่อใช้งานระบบเว็บไซต์หน่วยงานสำเร็จรูป
          </p>
        </div>

        <v-text-field
          outlined
          type="email"
          class="form-control"
          placeholder="Username"
        />

        <v-text-field
          outlined
          type="password"
          class="form-control"
          placeholder="Password"
        />

        <input type="checkbox" id="remember" />
        <label for="remember"> จดจำฉัน </label>

        <v-btn
          to="#"
          color="green darken-4"
          class="white--text mb-4 mt-4 mr-2"
          style="width: 100%"
        >
          เข้าสู่ระบบ
        </v-btn>
        <a href="/" class="text-decoration-none black--text">
          <p class="grey--text text-center">ลืมรหัสผ่าน?</p>
        </a>
      </div>
    </div>
  </v-card>
</template>

<script>
export default {
  name: 'login',
}
</script>
