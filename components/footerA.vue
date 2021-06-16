<template>
  <footer class="footer-distributed">
    <div class="tit1 col-6">
      <p>
        ห้างหุ้นส่วนจำกัด ไอซีที อินทิเกรเตอร์ 299/139 หมู่บ้านกาญจน์กนกวิลล์
      </p>
      <p>10 หมู่ที่ 6 ต.สันผักหวาน อ.หางดง จ.เชียงใหม่ 50230</p>
      <hr width="180%" />
    </div>
    <div class="footer-left">
      <div class="tit">
        <h3>ติดต่อเรา</h3>
      </div>
      <p class="footer-company-name">
        © Government, Inc. 2021. Web Content Mangement System
      </p>
    </div>

    <div class="footer-right">
      <div class="data">
        <p>
          <i
            class="fas fa-phone-square-alt fa-2x"
            style="vertical-align: middle"
          ></i
          >&ensp;06-5265-9288
        </p>
        <p>
          <i class="far fa-envelope fa-2x" style="vertical-align: middle"></i
          >&ensp;ictintegrator.co@gmail.com
        </p>
        <p>
          <i class="fab fa-line fa-2x" style="vertical-align: middle"></i>&ensp;
          LineID : @icti
        </p>
      </div>
      <div class="btn-1">
        <div class="btn5">
          <button type="button" class="btn3 btn-success" @click="goregister">
            สมัครใช้งาน
          </button>
        </div>
        <div class="btn6">
          <button
            type="button"
            class="btn4 btn-whith text-color-black"
            @click="gologin"
          >
            เข้าสู่ระบบ
          </button>
        </div>
      </div>

      <div class="follow">
        Follow us:&ensp;<a
          href="https://www.facebook.com/Spider-Gov-552060354858001/?ref=page_internal"
          target="https://www.facebook.com/Spider-Gov-552060354858001/?ref=page_internal"
          ><i
            class="fab fa-facebook-square fa-2x"
            style="vertical-align: middle"
          ></i
        ></a>
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  name: 'HelloWorld',
  methods: {
    gologin() {
      this.$router.push({ path: '/login' })
    },
    goregister() {
      this.$router.push({ path: '/register' })
    },
  },
}
</script>

<style>
@import '../assets/footerA.css';
</style>
