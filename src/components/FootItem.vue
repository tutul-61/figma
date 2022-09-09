<template>
    <div class="footer-section">
    <div class="footer">
        <div class="footer-left">
            <div class="footer-lchild">
            <img src="../assets/image.png" alt="">
            <p>Tutor<br>Academia</p>
        </div>
            <p>আমাদের মোবাইল অ্যাপ ডাউনলোড করুন</p>
            <img src="../assets/image 1.png" alt="">

        </div>
        <div class="footer-lb">
            <p>প্রতিষ্ঠান</p>
            <p>আমাদের সম্পর্কে</p>
            <p>যোগাযোগ</p>
            <p>নোটিশ</p>

        </div>
        <div class="footer-rb">
            <p>লিঙ্ক</p>
            <p>নীতিমালা</p>
            <p>প্রাইভেসি পলিসি</p>
            <p>রিফান্ড নীতিমালা</p>

        </div>
        <div class="footer-right">
            <p>প্রশ্ন জানার থাকলে</p>
            <div class="foter-rightflex">
                <p>26/Ga, Golapjan Road, Mymensingh</p>
            </div>
            <div class="foter-rightflex1">
                <p>01920 412346 (for course)<br>01726 111007 (for book)</p>
            </div>
            <div class="foter-rightflex2">
                <p>Support@tutoracademia.com</p>
            </div>

        </div>
     
    </div>
    <div class="draw-line">
        <p>স্বত্ব © Tutor Academia কতৃক সর্বস্বত্ব সংরক্ষিত. ডেভেলপার Nextive Solution</p>
    </div>
    </div>
  </template>
  
  <script>
  
  export default {
    name: 'FootItem',
    
  }
  </script>
  
  <style lang="scss">
    .footer-section{
        width:100%;
        height:282px;
        border: 1px solid cyan;
        background: #F8FBFF;
        

    
    .footer{
        display: flex;
        justify-content: space-around;
        align-items: center;
    }
    .footer-lchild{
        display: flex;
        align-items:center;
        p{
            margin-left:15px;
        }
    }
      .draw-line{  
        width:60%;
        height:0px;
        margin-left:200px ;
        border: 1px solid cyan;
        background: #F8FBFF;
        p{
            margin-left: 100px;
        }
      }
}
  
  </style>
  