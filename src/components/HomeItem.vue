<template>
    <div class="item">
        <div class="item-left">
            <p class="inner1">
                বেসিক থেকে শুরু হোক <br>
                শেখার নতুন জার্নি 
            </p>


            <p class="inner2">
                নতুন কিছু শিখতে চান? বেসিক থেকে শুরু করুন এবং এডভান্সড <br>
                লেভেলের দক্ষতা অর্জন করুন, সফলতা আসবেই ইনশাল্লাহ। 
            </p>
            <div class="item-left-child">
               <img src="../assets/goplaystore.png" alt="">
               <p>অ্যাপটি ডাউনলোড করো </p>

            </div>

        </div>
        <div class="item-right">

        </div>
        <div>
            <img src="../assets/73243-happy-students-studying 1.png" alt="student">
        </div>

      
    </div>
  </template>
  
  <script>
  
  
  
  export default {
    name: 'HomeItem',
 
  }
  </script>
  
  <style lang="scss">
    .item{

        display: flex;
        justify-content: space-around;
        align-items: center;
    }

.item-left{
    .inner1{
        display: flex;
        align-items: center;
        box-sizing: border-box;
        padding: 33px;
        width: 300px;
        height: 100px;
        margin-left: 50px;
        
        color:#0086AE;
        &:hover{
            color: white;
            background: #0086AE;
            border: 1px solid black;
        }
    }
    .inner2{
        display:flex;
        margin-left:50px;
        margin-top:20px;
        
    }
}




.item-left-child{
    display: flex;
    align-items: center;
    width: 300px;
    height: 55px;
    border: 1px solid  #0086AE;
    border-radius: 80px;
    margin-left: 50px;
    img{
        display: flex;
        justify-content: space-around;
        align-items: center;
        padding: 35px;
        width: 50px;
        height: 50px;
    }
    &:hover{
        color: white;
        background-color:#0086AE;
    }
}
  
  </style>
  