<template>
    <div class="nav">
        <div class="box6">
            <img src='../assets/image.png' alt="image">
            <p>Tutor<br>Academia</p>

        </div>
        <div class="box7">
            <ul>
                <li>হোম</li>
                <li>কোর্স</li>
                <li>প্রশ্নব্যাংক</li>
                <li>বইসমূহ</li>
                <li>নোটিশ</li>
            </ul>
            

        </div>
        <div class="box8">
            <img src="../assets/shopping.png" alt="shop">
            <button class="btn">Register/Login</button>


        </div>
    </div>
  </template>
  
  <script>

  export default {
    name: 'NavBar',
    
  }
  </script>
  
  <style lang="scss">
    .nav{
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 100%;
        height: auto;
        background-color: #FFFFFF;
        border: 1px solid aqua;
        .box6{
            display: flex;
            align-items: center;
        }
        .box7{
            ul{
                display: flex;
                align-items: center;
                list-style-type: none;
                li{
                    padding: 10px;
                }
            }
        }
        .box8{
            display: flex;
            align-items: center;
            img{
                padding: 20px;
            }
            .btn{
                margin:20px;
                border-radius: 10px;
                &:hover{
                    color: white;
                    background:#0086AE ;
                }
            }


        }

    }
  
  </style>