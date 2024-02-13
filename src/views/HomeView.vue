<script setup>
import { toast } from 'vue3-toastify';
import 'vue3-toastify/dist/index.css';

toast.info("ยินดีต้อนรับเข้าWebtoon", {
  autoClose: 1500,
  position:toast.POSITION.TOP_CENTER
})

const notify = () => {
  toast.success("ยินดีต้อนรับเข้าWebtoon", {
    autoClose: 1500,
    position: toast.POSITION.TOP_CENTER
  })
  return notify
}

</script>

<template>
  <div class="container my-5">
    <div class="card shadow" style="width: 20rem;">
      <div class="card-header p-0">
        <img src="https://i.pinimg.com/564x/02/47/56/024756ff60e7b367882f1c5b3d9167eb.jpg" class="card-img-top"
          alt="img">
         
      </div>
      <div class="card-body">
        <h5 class="card-title">Webtoon</h5>
        <p class="card-text">Webtoon (เว็บตูน) แอปพลิเคชันสำหรับอ่านนิยายหรือการ์ตูนหลากหลายรูปแบบ เริ่มต้นให้บริการในประเทศเกาหลี เมื่อปี พ.ศ.2557 และเป็นที่รู้จักในชื่อ LINE Webtoon หรือไลน์ เว็บตูน ปัจจุบันมียอดผู้อ่านและผู้ใช้งานหลักสิบล้านคน ส่งผลให้มีการขยายกิจการให้บริการในต่างประเทศร่วมด้วย</p>
        <a href="http://localhost:5173/wonders" class="btn btn-primary" style="background: #39ad6f" @click="notify">Read...</a>
      </div>
    </div>
  </div>
</template>




