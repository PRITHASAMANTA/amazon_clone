# amazon_clone

//HTML//
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />"
    <link rel="stylesheet" href="style.css">
</head>
<body>
   <header>
    <div class="navbar">
        <div class="nav-logo border">
            <div class="logo"></div>

        </div>
        <div class="nav-address border">
            <p class="add-first">deliver to</p>
                <div class="add-icon">
                
                    <i class="fa-solid fa-location-dot"></i>
                    <p class="add-second">India</p>
            </div>
        </div>
        <div class="nav-search">
            <select class="search-select">
                <option>All</option>
            </select>
            <input placeholder="search Amazon" class="search-input">
            <div class="search-icon">
                <i class="fa-solid fa-magnifying-glass"></i>
            </div>
        </div>

        <div class="nav-signin border">
            <p><span>Hello,sign in</span></p>
            <p class="nav-second">Account & Lists</p>
        </div>

        <div class="nav-return border">
            <p><span>Hello,sign in</span></p>
            <p class="nav-second">& orders</p>
        </div>

        <div class="nav-cart border">
            <i class="fa-solid fa-cart-shopping"></i>
            cart
        </div>
    </div>

    <div class="panel">
        <div class="panel-all">
            <i class="fa-solid fa-bars"></i>
            All
        </div>

        <div class="panel-option">
            <p>Today's Deals</p>
            <p>Coustomer Service</p>
            <p>Registry</p>
            <p>Gift Cards</p>
            <p>Sell</p>

        </div>

        <div class="panel-deals">
            shop deals in Electronics
        </div>
    </div>

   
   </header>

   <div class="hero-section">
    <div class="hero-mess">
        <p> You are on Amazon.You can also shop on Amazon India for millions of products with fast local delivery.<a>click here to go to amazon.in</a></p>
    </div>
   </div>
   <div class="shop-section">
    <div class="box1 box">
       <div class="box-content">
        <h2>Health & personal care</h2>
        <div class="box-img" style="background-image: url('box1_image.jpg');"></div>
        <p>see more</p>
    
       </div>
    </div>
    <div class="box2 box">
        <div class="box-content">
            <h2>Clothes</h2>
            <div class="box-img" style="background-image: url('box2_image.jpg');"></div>
            <p>see more</p>
        </div>
           </div>
    <div class="box3 box"><div class="box-content">
        <h2>Furniture</h2>
        <div class="box-img" style="background-image: url('box3_image.jpg');"></div>
        <p>see more</p>
        </div>
       </div>
    <div class="box4 box"><div class="box-content">
        <h2>Electronics</h2>
        <div class="box-img" style="background-image: url('box4_image.jpg');"></div>
        <p>see more</p>
    
       </div>
   </div>
   <div class="box5 box"><div class="box-content">
    <h2>Beauty picks</h2>
    <div class="box-img" style="background-image: url('box5_image.jpg');"></div>
    <p>see more</p>

   </div>
</div>
<div class="box6 box"><div class="box-content">
    <h2>Pets</h2>
    <div class="box-img" style="background-image: url('box6_image.jpg');"></div>
    <p>see more</p>

   </div>
</div>
<div class="box7 box"><div class="box-content">
    <h2>New arrival in Toys</h2>
    <div class="box-img" style="background-image: url('box7_image.jpg');"></div>
    <p>see more</p>

   </div>
</div>
<div class="box8 box"><div class="box-content">
    <h2>Discover Fashion Tools</h2>
    <div class="box-img" style="background-image: url('box8_image.jpg');"></div>
    <p>see more</p>

   </div>
</div>
</div>
<footer>
    <div class="foot-panel1">
        Back to Top
    </div>
    <div class="foot-panel2">
       <ul>
        <p>Get to Know Us</p>
        <a>About Us </a>
       <a> Careers</a>
        <a>Press Releases</a>
       <a> Amazon Science</a>
       </ul>
       <ul>
        <p>Connect with Us</p>
        <a>Facebook</a>
       <a> Twitter</a>
        <a>Instagram</a>
       </ul>
       <ul>
        <p>Make Money with Us</p>
        <a>Sell on Amazon </a>
       <a> Sell under Amazon Accelerator</a>
        <a>Protect and Build Your Brand</a>
       <a> Amazon Global Selling</a>
       <a>Become an Affiliate</a>
       <a>Fulfilment by Amazon</a>
       <a>Fulfilment by Amazon</a>
       <a>Amazon Pay on Merchants</a>
       </ul>
       <ul>
        <p>Let Us Help You</p>
        <a>COVID-19 and Amazon</a>
       <a>Your Account</a>
        <a>Returns Centre</a>
       <a> 100% Purchase Protection</a>
       <a>Amazon App Download</a>
       <a>Help</a>
       </ul>
    </div>

    <div class="foot-panel3">
        <div class="logo"></div>
    </div>

    <div class="foot-panel4">
        <div class="pages">
            <a>Conditions of Use & Sale</a>
            <a>Privacy Notice</a>
            <a>Interest-Based Ads</a>
        </div>
        <div class="copyright">
            © 1996-2023, Amazon.com, Inc. or its affiliates
        </div>
    </div>
  </footer> 
 
</body>
</html>



//* CSS*//

* {
    margin: 0;
    font-family: Arial;
    border: border-box;
}

.navbar {
    height: 60px;
    background-color: #0f1111;
    color:white;
    display: flex;
    align-items:center;
    justify-content: space-evenly;
}

.nav-logo{
    height: 50px;
    width: 100px;

}
.logo {
    background-image: url("amazon_logo.png");
    background-size: cover;
    height: 50px;
    width: 100%;
}

.border{
    border: 2px solid transparent;
}

.border:hover{
    border: 2px solid white;
}

/** box2/**/

.add-first{
    color:#ccc;
    font-size:0.85rem;
    margin-left: 15px;
}

.add-second {
   
    font-size:1rem;
    margin-left:3px ;
}
.add-icon{
    display:flex;
    align-items:center;
}

/** box 3**/
.nav-search {
    display:flex;
    justify-content: space-evenly;
    background-color: pink;
    width:620px;
    height:40px;
    border-radius: 4px;

}

.search-select {
    background-color: #f3f3f3;
    width:50px;
    text-align: center;
    border-top-left-radius: 4px;
    border-bottom-left-radius: 4px;
    border:none;
}

.search-input {
    width:100%;
    font-size: 1rem;
    border:none;

}

.search-icon {
    width:45px;
    display:flex;
    justify-content: center;
    align-items: center;
    font-size:1.2rem;
    background-color: #febd68;
    border-top-right-radius: 4px;
    border-bottom-right-radius: 4px;
    color:#0f1111;
}

.nav-search:hover {
    border:2px solid orange;
}

/**box4 **/
span {
font-size:0.7rem;

}
.nav-second {
    font-size:0.85rem;
    font-weight: 700px;

}

/**box6**/

.nav-cart i{
font-size:30px;
}

.nav-cart{
    font-size:0.85rem;
    font-weight:700;
}

/** panel**/

.panel {
    height:40px;
    background-color: #222f3d;
    display:flex;
    color:white;
    align-items: center;
    justify-content: space-evenly;

}
.panel-option p {
    display:inline;
    margin-left:15px;

}

.panel-option{
    width:70%;
    font-size:0.85rem;
}
.panel-deals{
font-size: 0.9rem;
font-weight: 700;
}
/** hero section **/
.hero-section{
    background-image: url("hero_image.jpg");
    background-size: cover;
    height: 380px;
    display: flex;
    justify-content: center;
    align-items: flex-end;
}
.hero-mess{
    background-color: white;
    color: black;
    height: 40px;
    display: flex;
    align-items: center;  
    justify-content: center; 
    bottom:25px;
    position:0.85rem;
    width: 80%;
    margin-bottom:25px;
}
.hero-mess a {
    color: #007185;

}

/** shop-sec **/

.shop-section{
    display:flex;
    flex-wrap:wrap;
    justify-content: space-evenly;
    background-color: #e2e7e6;
}
.box{
    border: 2px solid black;
    height:400px;
    width: 23%;
    background-color: white;
    padding:20px 0px 15px;
    margin-top: 15px;

}

.box-img{
    height: 300px;
    background-size: cover;
    margin-top: 1rem;
    margin-bottom: 1rem;
}
.box-content{
    margin-left: 1rem;
    margin-right: 1rem;
    
}

.box-content p{
    
    color:#007185;
}

/** footer**/

footer{
    margin-top: 15px;
}

.foot-panel1 {
    background-color: #37475a;
    color:white;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 0.85rem;
}
.foot-panel2{
    background-color: #222f3d;
    color: white;
    height: 300px;
    display: flex;
    justify-content: space-evenly;

}

ul {
    margin-top: 20px;
}

ul a {
    display: block;
    font-size: 0.85rem;
    margin-top: 10px;
    color: #dddd;
}

.foot-panel3{
    background-color:#222f3d;
    color: white; 
    border-top: 0.5px solid white;
    height: 68px;
    display: flex;
    justify-content: center;
    align-items: center;
}
.logo {
    background-image: url("amazon_logo.png");
    background-size: cover;
    height: 50px;
    width: 100px;
    
}

.foot-panel4{
    background-color:#0f1111;
    color: white; 
    padding: 25px;
    height: 80px;
    text-align: center;
}

.pages{
    font-size: 0.7rem;
   

}
.copyright{
    font-size: 0.7rem;
    
}
