<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="style.css">
</head>
<style>
    @import url('https://fonts.googleapis.com/css2?family=Nunito+Sans:ital,opsz,wght@0,6..12,200..1000;1,6..12,200..1000&family=Pacifico&family=Reddit+Mono:wght@200..900&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');


:root{
    --main-color:rgb(7, 252, 7);
    --black:#13131a;
    --bg:rgb(41, 38, 38);
    --border:1rem solid rgba(255,255,255,.3);
}

    
   
  






body{
    background: rgb(246, 244, 244);
}

.head{
    font-family: "Roboto", sans-serif;
   
    background: transparent;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 1.5rem ;
    border-bottom: white;
    position: fixed;
    
    height: 10vh;
    width: 96.6vw;
    color: greenyellow;
   
}

.head .nav a{
    margin: 0 1rem;
    font-size: 1.6rem;
    color:#13131a;
    color: rgb(32, 245, 4);
}

.icons{
    justify-content: space-between;
    letter-spacing: 0.5rem;
    cursor: pointer;
    color: rgb(32, 245, 4);;
   
    
    
    
}
.head .nav a:hover{
    text-shadow: 2px 2px 10px rgb(32, 245, 4);
    filter:grayscale(1);
  transform: scale(1.03);
  

}



.bgimg{
    height: 95vh;
    width:99.4Vw;
   
    background-image:  url('https://res.cloudinary.com/dpbcbnika/image/upload/c_fill,w_1920,h_1080/v1715317004/small-pieces-breads-parsley-garlic-bowl-infused-olive-oil-green-textured-background_23-2148091051_hz18dz_sxpwd7.png');
    margin-bottom: 15%;
    position:absolute;
}
.about-us{
    padding: 50px;
}
.shop-section{
    display: flex;
     flex-wrap: wrap;
       justify-content: space-evenly;
       background-image: url('https://res.cloudinary.com/dpbcbnika/image/upload/v1715315135/istockphoto-165793418-170667a_vmwwhm.jpg');
       height: 70vh;
      
      
   }

  
   .box{
     
     
       height: 400px;
       width: 23%;
       background-color: white;
       align-items: center;
       padding: 20px 0px 15px;
       margin-top: 15px;
       border-radius: 13px;
       
   }
   .box-img{
       height: 300px;
       
       background-size:cover;
       margin-top: 1rem;
       margin-bottom: 1rem;
   }
   .box-content{
       margin-left: 1rem;
       margin-right: 1rem;
   }
   .foot-panel2{
    background-color: rgb(41, 38, 38);
    color:white;
    height: 300px;
    display: flex;
    justify-content: space-evenly;

}
ul a{
    display: block;
    font-size: 0.85rem;
    margin-top: 10px;
}
.foot-panel3{
    background-color: #222f3d;
    color:white;
    border-top: 0.5px solid white;
    height: 70px;
    display: flex;
    justify-content: center;
    align-items: center;


}

.logo1{
    justify-content: space-evenly;
    display: flex;
    flex-direction: row;
    color: greenyellow;
   
    width: 15vw;
}


.foot-panel4{
    background-color: #0f1111;
    color: rgb(3, 250, 24);
    height: 80px;
    mask-clip: text;
}
.pages{
    font-size: 0.7rem;
    text-align: center;
    padding:25px ;
}
.copyright{
    padding-top: 5px;
    font-size: 0.7rem;
    text-align: center;
}
.foot-panel5{
    display: flex;
    justify-content: space-between;
}

</style>
<body>
    
<header class="head" style="position:sticky;background-color:rgb(43, 41, 41);">

    <a href="#" class="">
        <img src="https://res.cloudinary.com/dpbcbnika/image/upload/v1715262108/Fresh-food-logo-design-on-transparent-background-PNG-removebg-preview_vos65j.png" alt="" class="img" height="70px" width="70px" style="margin: 2%;">
    </a>

    <nav class="nav">
        <a href="#Home">Home</a>
        <a href="#About-us">About us</a>
        <a href="#Menu">Menu</a>
        <a href="#Foods">Foods</a>
        <a href="feedback">Feedback</a>
        <a href="#Contact">Contact</a>
    </nav>
      <div class="icons">  
        <i  class="fa-solid fa-magnifying-glass" id="ic"></i>
        <i class="fa-solid fa-cart-shopping" id="ic1"></i>
        <i class="fa-solid fa-bars" class="searchbut" id="ic2"></i>
 
    </div>



</header>
<div>
<div class="bgimg" id="#Menu">
<div style="text-align: left;; padding-top: 10%;padding-left: 3%;word-spacing: 2%;">
    <div style="width: 50vw;height:vh">
        <h1><span style="font-size: 100px;color: greenyellow;text-align: left;margin-bottom: 2%; font-family:system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif">Fresh Food ,</span> </h1>
            <p><span style="font-size: 40px;font-family:system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;"> food shop, or fast food establishment, in which the principal use 
                is production of prepared food for delivery to customers located off the business premises.</span></p>
            
    </div>
  
        
        
    </div>
    
</div>
</div>


<section id="about-us">
    <div class="about-us"style="margin-top: 45%;text-align: center;background-color:rgb(41, 38, 38);; ;color: greenyellow;width: 93.6vw;" id="About-us" >
        <div class="container">
          <div class="row">
            <div class="col-12">
              <h1 class="head-h1" >About<span style="color:rgb(245, 243, 246);"> us</span></h1><hr class="hr">
              <p class="para-p1">Welcome to Fresh Food, where culinary excellence meets warm hospitality. Our story is one of passion, dedication, and a commitment to delivering an exceptional dining experience to our cherished guests.
                Our Journey
                
                At Fresh Food, our journey began with a simple yet profound vision – to create a haven for food enthusiasts, a place where flavors come alive, and memories are made. Established in [Year of Establishment], we embarked on this culinary adventure with the aim of offering a unique blend of delectable cuisine, inviting ambiance, and impeccable service.
                Our Philosophy
                Culinary Excellence</p>
            </div>
          </div>
        </div>
      </div>
</section>

<div class="shop-section" id="Foods" style="width: 99.5VW;">
    <div class="box1 box" style="background-color: rgb(43, 41, 41)">
       <div class="box-content">
         <h2 style="color:rgb(32, 245, 4); ">Idli & Vada</h2>
        
        <div class="box-img" style="background-image: url('https://res.cloudinary.com/dpbcbnika/image/upload/v1715316167/oats-idli_vdefrn.webp')"; ></div>
        <p style="color:rgb(76, 109, 63);"><span style="color:rgb(10, 251, 18);font-size: 20px; ">$9.0</span> ==><span style="color: rgb(237, 164, 128);"> Order Now</span></p>
    </div>
</div>
    <div class="box2 box" style="background-color: rgb(43, 41, 41)">
        <div class="box-content"> 
            <h2  style="color:rgb(32, 245, 4); ">Masala Dosa</h2>
        
            <div class="box-img" style="background-image: url('https://res.cloudinary.com/dpbcbnika/image/upload/v1715316167/wp6734929_e0nuos.jpg')"; ></div>
            <p style="color:rgb(76, 109, 63);"><span style="color:rgb(10, 251, 18);font-size: 20px; ">$12.0</span> ==><span style="color: rgb(237, 164, 128);"> Order Now</span></p>
          
        </div>
   </div>
    <div class="box3 box" style="background-color: rgb(43, 41, 41)">
        <div class="box-content" > 
            <h2  style="color:rgb(32, 245, 4); ">Pannner Biryani</h2>
        
            <div class="box-img" style="background-image: url('https://res.cloudinary.com/dpbcbnika/image/upload/v1715316296/OIP_iudkxs.jpg')"; ></div>
            <p style="color:rgb(76, 109, 63);"><span style="color:rgb(10, 251, 18);font-size: 20px; ">$25.0</span> ==><span style="color: rgb(237, 164, 128);"> Order Now</span></p>
        
    </div>
    
 </div>
 <div class="box4 box" style="background-color: rgb(43, 41, 41)">
    <div class="box-content"> 
        <h2  style="color:rgb(32, 245, 4); ">Roti & Panner Butter masala</h2>
     
     <div class="box-img" style="background-image: url('https://res.cloudinary.com/dpbcbnika/image/upload/v1715316298/2c23a9a24b7b031f5ad01c900a9993d7_kn0wkj.jpg')"; ></div>
     <p style="color:rgb(76, 109, 63);"><span style="color:rgb(10, 251, 18);font-size: 20px; ">$30.0</span> ==><span style="color: rgb(237, 164, 128);"> Order Now</span></p>
 </div>
</div>
<div class="foot" style="width: 100vw; color: rgb(10, 251, 18);;" >
    <div class="shop-section" id="Foods" style="width: 99.5VW;">
        <div class="box1 box" style="background-color: rgb(43, 41, 41)">
           <div class="box-content">
             <h2 style="color:rgb(32, 245, 4); ">Veg Biryani</h2>
            
            <div class="box-img" style="background-image: url('https://res.cloudinary.com/dpbcbnika/image/upload/v1715342277/OIP_1_-_Copy_zw5hwh.jpg')"; ></div>
            <p style="color:rgb(76, 109, 63);"><span style="color:rgb(10, 251, 18);font-size: 20px; ">$32.0</span> ==><span style="color: rgb(237, 164, 128);"> Order Now</span></p>
        </div>
    </div>
        <div class="box2 box" style="background-color: rgb(43, 41, 41)">
            <div class="box-content"> 
                <h2  style="color:rgb(32, 245, 4); ">Mushroom Biryani</h2>
            
                <div class="box-img" style="background-image: url('https://res.cloudinary.com/dpbcbnika/image/upload/v1715342280/50_xoghvb.webp')"; ></div>
                <p style="color:rgb(76, 109, 63);"><span style="color:rgb(10, 251, 18);font-size: 20px; ">$23.0</span> ==><span style="color: rgb(237, 164, 128);"> Order Now</span></p>
              
            </div>
       </div>
        <div class="box3 box" style="background-color: rgb(43, 41, 41)">
            <div class="box-content" > 
                <h2  style="color:rgb(32, 245, 4); ">Hydrebadi Biryani</h2>
            
                <div class="box-img" style="background-image: url('https://res.cloudinary.com/dpbcbnika/image/upload/v1715342277/OIP_2_ysoob5.jpg')"; ></div>
                <p style="color:rgb(76, 109, 63);"><span style="color:rgb(10, 251, 18);font-size: 20px; ">$24.0</span> ==><span style="color: rgb(237, 164, 128);"> Order Now</span></p>
            
        </div>
        
     </div>
     <div class="box4 box" style="background-color: rgb(43, 41, 41)">
        <div class="box-content"> 
            <h2  style="color:rgb(32, 245, 4); ">North Meals</h2>
         
         <div class="box-img" style="background-image: url('https://res.cloudinary.com/dpbcbnika/image/upload/v1715342276/OIP_3_h6rq1q.jpg')"; ></div>
         <p style="color:rgb(76, 109, 63);"><span style="color:rgb(10, 251, 18);font-size: 20px; ">$40.0</span> ==><span style="color: rgb(237, 164, 128);"> Order Now</span></p>
     </div>
    </div>
    <div class="foot" style="width: 100vw; color: rgb(10, 251, 18);;" >
    <footer >
       <div style="height: 20px;">

       </div>
        <div class="foot-panel2" style="color: rgb(10, 251, 18);;">
            <ul>
                <p>Get to know us</p>
                <a>Careers</a>
                <a>Blog</a>
                <a>About fresh food</a>
                <a>investor Relations</a>
                <a>Amazon Devices</a>
                <a>Amazon science</a>
            </ul>
            <ul>
                <p>Get to know us</p>
                <a>Careers</a>
                <a>Blog</a>
                <a>About fresh food</a>
                <a>investor Relations</a>
                <a>fresh food Devices</a>
                <a>fresh food science</a>
            </ul>
            <ul>
                <p>Get to know us</p>
                <a>Careers</a>
                <a>Blog</a>
                <a>About fresh food</a>
                <a>investor Relations</a>
                <a>fresh food Devices</a>
                <a>fresh food science</a>
            </ul>
            <ul>
                <p>Get to know us</p>
                <a>Careers</a>
                <a>Blog</a>
                <a>About fresh food</a>
                <a>investor Relations</a>
                <a>fresh food Devices</a>
                <a>fresh food science</a>
            </ul>
        </div>
        <div class="foot-panel3" id="Contact" >
            <div class="logo1" style="column-gap: 5%;">
              <a href="https://twitter.com/IDFreshFood" style="color: greenyellow;"><i class="fa-brands fa-twitter"></i></a>
                <i class="fa-brands fa-facebook"></i>
                <i class="fa-brands fa-whatsapp"></i>
                <i class="fa-solid fa-phone"></i>
                <i class="fa-brands fa-twitter"></i>
            </div>
        </div>
        <div class="foot-panel4">
            <div class="pages">
                <a>Conditions of use</a>
                <a>Privacy Notice</a>
                <a>Your Ads Privacy ChoicesS</a>
            </div>
            <div class="copyright">
                © 1996-2024, fresh food.com, Inc. or its affiliates
            </div>
        </div>
        </footer>
</div>



<script src="js/script.js"></script>


</body>
</html>
