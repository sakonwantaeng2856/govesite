<template>
  <div class="app pricing" id="pricing">
    <v-container>
      <v-row class="mt-5">
        <v-col cols="12" sm="12">
          <h1 class="table text-center">ตารางเปรียบเทียบแพ็กเกจ</h1>
        </v-col>
      </v-row>

      <!--- Connect --->
      <v-row class="mt-5">
        <v-col cols="4" xs="12">
          <div class="d-flex justify-center">
            <v-card class="rounded-xl" width="400" height="830" elevation="15">
              <v-row>
                <v-col cols="12" class="text-center mt-5">
                  <h3 class="connect">CONNECT</h3>
                  <p class="mt-2">Cloud server 50 Mb</p>
                </v-col>
              </v-row>
              <v-row>
                <v-col cols="2"></v-col>
                <v-col cols="8"><v-divider></v-divider></v-col>
                <v-col cols="2"></v-col>
              </v-row>
              <v-row>
                <v-col class="conandstd" cols="12">
                  <li>เพิ่ม ลบ แก้ไข เนื้อหาเว็บไซต์ได้ด้วยตัวเอง</li>
                  <li>เปลี่ยนภาพ Slide กิจกรรมของหน่วยงาน</li>
                  <li>
                    แสดงหน้าวันสำคัญอัตโนมัติ <br />ตั้งเวลาแสดงผลเนื้อหาได้
                  </li>
                  <li>ระบบประกวดราคา ข่าวประขาสัมพันธ์</li>
                  <li>กระดานข่าว คลังเอกสารราชการ</li>
                  <li>ระบบร้องทุกข์ และสำรวจความคิดเห็น</li>
                  <li>ระบบสถิติผู้เข้าชมเว็บ</li>
                  <li>Theme เว็บไซต์มาตราฐาน</li>
                  <li>แสดง โฆษณา</li>
                  <li>Theme เว็บไซต์มาตราฐาน</li>
                </v-col>
              </v-row>
              <v-row class="pt-9">
                <v-col cols="2"></v-col>
                <v-col cols="8" class="pt-16 mt-8"
                  ><v-divider></v-divider
                ></v-col>
                <v-col cols="2"></v-col>
              </v-row>
              <v-row>
                <v-col class="text-center">
                  <p class="price">1,800 บาท</p>
                  <p>ต่อปี *ราคารวมภาษีมูลค่าเพิ่มแล้ว</p>
                </v-col>
              </v-row>
              <v-row class="pb-10">
                <v-col class="text-center">
                  <v-btn color="success " rounded>ขอใบเสนอราคา </v-btn>
                </v-col>
              </v-row>
            </v-card>
          </div>
        </v-col>
        <!--- Standard --->
        <v-col cols="4" xs="12">
          <div class="d-flex justify-center">
            <v-card class="rounded-xl" width="400" height="830" elevation="15">
              <v-row>
                <v-col cols="12" class="text-center mt-5">
                  <h3>STANDARD</h3>
                  <p class="mt-2">Cloud server 4GB</p>
                </v-col>
              </v-row>
              <v-row>
                <v-col cols="2"></v-col>
                <v-col cols="8"><v-divider></v-divider></v-col>
                <v-col cols="2"></v-col>
              </v-row>
              <v-row>
                <v-col class="conandstd" cols="12">
                  <li>เพิ่ม ลบ แก้ไข เนื้อหาเว็บไซต์ได้ด้วยตัวเอง</li>
                  <li>เปลี่ยนภาพ Slide กิจกรรมของหน่วยงาน</li>
                  <li>
                    แสดงหน้าวันสำคัญอัตโนมัติ <br />ตั้งเวลาแสดงผลเนื้อหาได้
                  </li>
                  <li>Support SEO</li>
                  <li>กระดานข่าว คลังเอกสารราชการ</li>
                  <li>ระบบร้องทุกข์ และสำรวจความคิดเห็น</li>
                  <li>ระบบสถิติผู้เข้าชมเว็บ</li>
                  <li>Theme เว็บไซต์มาตราฐาน</li>
                  <li>ไม่แสดง โฆษณา</li>
                  <li>Theme เว็บไซต์มาตราฐาน</li>
                </v-col>
              </v-row>
              <v-row class="pt-10">
                <v-col cols="2"></v-col>
                <v-col cols="8" class="pt-16 mt-8"
                  ><v-divider></v-divider
                ></v-col>
                <v-col cols="2"></v-col>
              </v-row>
              <v-row>
                <v-col class="text-center">
                  <p class="price">5,300 บาท</p>
                  <p>ต่อปี *ราคารวมภาษีมูลค่าเพิ่มแล้ว</p>
                </v-col>
              </v-row>
              <v-row class="pb-10">
                <v-col class="text-center">
                  <v-btn color="success " rounded>ขอใบเสนอราคา </v-btn>
                </v-col>
              </v-row>
            </v-card>
          </div>
        </v-col>
        <!--- Premium --->
        <v-col cols="4" xs="12">
          <div class="d-flex justify-center">
            <v-card
              class="rounded-xl"
              color="success"
              width="400"
              height="830"
              elevation="15"
            >
              <v-row>
                <v-col cols="12" class="text-center mt-5">
                  <h3 class="premium">PREMIUM</h3>
                  <p class="mt-2">Cloud server 4GB</p>
                </v-col>
              </v-row>
              <v-row>
                <v-col cols="2"></v-col>
                <v-col cols="8"><v-divider></v-divider></v-col>
                <v-col cols="2"></v-col>
              </v-row>
              <v-row>
                <v-col class="pre" cols="12">
                  <li class="premium">จดทะเบียน .com หรือ .go.th</li>
                  <li class="premium">
                    Email @ชื่อเว็บไซค์หน่วยงาน ( 1 Email)
                  </li>
                  <li class="premium">
                    เพิ่ม ลบ แก้ไข เนื้อหาเว็บไซต์ได้ด้วยตัวเอง
                  </li>
                  <li class="premium">เปลี่ยนภาพ Slide กิจกรรมของหน่วยงาน</li>
                  <li class="premium">
                    แสดงหน้าวันสำคัญอัตโนมัติ <br />
                    ตั้งเวลาแสดงผลเนื้อหาได้
                  </li>
                  <li class="premium">Support SEO</li>
                  <li class="premium">ระบบประกวดราคา ข่าวประขาสัมพันธ์</li>
                  <li class="premium">กระดานข่าว คลังเอกสารราชการ</li>
                  <li class="premium">ระบบร้องทุกข์ และสำรวจความคิดเห็น</li>
                  <li class="premium">ระบบสถิติผู้เข้าชมเว็บ</li>
                  <li class="premium">Theme เว็บไซต์มาตราฐาน</li>
                  <li class="premium">
                    ย้ายข้อมูลพื้นฐานจากเว็บไซต์เดิมมายังเว็บไซต์ใหม่ ในครั้งแรก
                  </li>
                  <li class="premium">ไม่แสดงโฆษณา</li>
                </v-col>
              </v-row>
              <v-row class="pt-3">
                <v-col cols="2"></v-col>
                <v-col cols="8 mt-6"><v-divider></v-divider></v-col>
                <v-col cols="2"></v-col>
              </v-row>
              <v-row>
                <v-col class="text-center">
                  <p class="price">7,400 บาท</p>
                  <p>ต่อปี *ราคารวมภาษีมูลค่าเพิ่มแล้ว</p>
                </v-col>
              </v-row>
              <v-row class="pb-10">
                <v-col class="text-center">
                  <v-btn color="white" rounded outlined>ขอใบเสนอราคา </v-btn>
                </v-col>
              </v-row>
            </v-card>
          </div>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {}
</script>

<style>
@import '../assets/pricing.css';
</style>
