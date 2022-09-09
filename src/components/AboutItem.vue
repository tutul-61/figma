<template>
    <div class="category">
        <div class="category-top">
            <p>
                বেছে নিন আপনার পছন্দের ক্যাটাগরি<br>
                আর শুরু  করুন আত্মবিশ্বাসের সাথে
            </p>

        </div>

        <div class="gird-container">

        <div class="grid-item item1">
            <img src="../assets/briefcase 2.png" alt="brief">
            <p>চাকরি প্রস্তুতি</p>
        </div>
        <div class="grid-item item2">
            <img src="../assets/test (1) 2.png" alt="test">
            <p>এক্সাম ব্যাচ</p>
        </div>
        <div class="grid-item item3">
            <img src="../assets/contract 2.png" alt="contact">
            <p>এডমিশন টেস্ট</p>
        </div>
        <div class="grid-item item4">
            <img src="../assets/graduate 2.png" alt="graduate">
            <p>একাডেমিক কোর্সসমূহ</p>
        </div>
        <div class="grid-item item5">
            <img src="../assets/eng 2.png" alt="eng">
            <p>ইংলিশ ল্যাঙ্গুয়েজ</p>
        </div>
        <div class="grid-item item6">
            <img src="../assets/solution 1.png" alt="solution">
            <p>স্কিল ডেভেলপমেন্ট</p>
        </div>
    </div>
     
    </div>
  </template>
  
  <script>
  
  
  export default {
    name: 'AboutItem',
   
  }
  </script>
  
  <style lang="scss">
    .category{
        background:#BAEFFF;
        width: 100%;
        height: 367px;
        .category-top{
            text-align: center;
            font-family: 'Hind Siliguri';
            font-style: normal;
            font-weight: 600;
            font-size: 36px;
            line-height: 147.7%;
        }
        .gird-container{
        display: grid;
        grid-template-columns: auto auto auto auto;
        grid-row-gap:20px;
        margin-left: 50px;
        .grid-item{
            display: flex;
            justify-content: space-evenly;
            align-items: center;
            width: 270px;
            height: 71px;
            border-radius: 10px;
            border: 1px solid white;
          img{
            margin-left:20px;
          }
          p{
            margin-right: 20px;
          }
          &:hover{
            background: white;
          }
        }
    }


        
    }
  
  </style>
  