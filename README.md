# amazon-clone-project
In this project, I have used  HTML ,CSS &amp; JAVASCRIPT languages to create this project. This project is clone of amazon website interface.

                                              // amazon clone //

HTML PART :
   
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" contant="IE=edge">
    <meta name="viewport" contant="width=device-width, initial-scale=1.0">
    <title>Amazon</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="navbar">
            <div class="nav-logo border">
                <div class="logo"></div>
            </div>

            <div class="nav-address border">
                <p class="add-first">Deliver to</p>
                <div class="address-icon">
                    <i class="fa-solid fa-location-dot"></i>
                    <p class="add-second">India</p>
                </div>
            </div>

            <div class="nav-search">
                <select class="search-select">
                    <option>All</option>
                </select>
                <input placeholder="Search Amazon" class="search-input">
                <div class="search-icon">
                    <i class="fa-solid fa-magnifying-glass"></i>
                </div>
            </div>

            <div class="nav-signin border">
                <p><span>Hello, Sign in</span></p>
                <p class="nav-second">Account & Lists</p>
            </div>

            <div class="return border">
                <p><span>Returns</span></p>
                <p class="nav-second">& Orders</p>
            </div>

            <div class="nav-cart border">
                <i class="fa-solid fa-cart-plus"></i>
                Cart
            </div>
        </div>

        <div class="panel">
            <div class="panel-all">
                <i class="fa-solid fa-bars"></i>
                All
            </div>
            <div class="panel-ops">
                <p>Today's Deals</p>
                <p>Customer Service</p>
                <p>Registry</p>
                <p>Gift Cards</p>
                <p>Sell</p>
            </div>
            <div class="panel-deals">
                Shop deals in Electronics
            </div>
        </div>
    </header>

    <div class="hero-section">
        <div class="hero-msg">
            <p>You are on amazon.com. You can also shop on Amazon India for millions of product with fast local delivary.  <a>Click here to go to amazon.in</a></p>
        </div>
    </div>

    <div class="shop-section">
        <div class="box">
            <div class="box-content">
                <h2>Cloths</h2>
                <div class="box-img" style="background-image: url('box1_image.jpg');"></div>
                <P>See more</P>
            </div>
        </div>
        <div class="box">
            <div class="box-content">
                <h2>Health & Cersonal Care</h2>
                <div class="box-img" style="background-image: url('box2_image.jpg');"></div>
                <P>See more</P>
            </div>
        </div>
        <div class="box">
            <div class="box-content">
                <h2>Furniture</h2>
                <div class="box-img" style="background-image: url('box3_image.jpg');"></div>
                <P>See more</P>
            </div>
        </div>
        <div class="box">
            <div class="box-content">
                <h2>Electronics</h2>
                <div class="box-img" style="background-image: url('box4_image.jpg');"></div>
                <P>See more</P>
            </div>
        </div>
        <div class="box">
            <div class="box-content">
                <h2>Beauty picks</h2>
                <div class="box-img" style="background-image: url('box5_image.jpg');"></div>
                <P>See more</P>
            </div>
        </div>
        <div class="box">
            <div class="box-content">
                <h2>Pet care</h2>
                <div class="box-img" style="background-image: url('box6_image.jpg');"></div>
                <P>See more</P>
            </div>
        </div>
        <div class="box">
            <div class="box-content">
                <h2>New Arrival</h2>
                <div class="box-img" style="background-image: url('box7_image.jpg');"></div>
                <P>See more</P>
            </div>
        </div>
        <div class="box">
            <div class="box-content">
                <h2>Discover Fasion Trends</h2>
                <div class="box-img" style="background-image: url('box8_image.jpg');"></div>
                <P>See more</P>
            </div>
        </div>
    </div>

    <footer>
        <div class="foot-panel1">
            Back to top
        </div>

        <div class="foot-panel2">
            <ul>
                <p>Get to know us</p>
                <a>Careers</a>
                <a>Blog</a>
                <a>About Amazon</a>
                <a>Invester Relation</a>
                <a>Amazon Devices</a>
                <a>Amazon Science</a>
            </ul>
            <ul>
                <p>Get to know us</p>
                <a>Careers</a>
                <a>Blog</a>
                <a>About Amazon</a>
                <a>Invester Relation</a>
                <a>Amazon Devices</a>
                <a>Amazon Science</a>
            </ul>
            <ul>
                <p>Get to know us</p>
                <a>Careers</a>
                <a>Blog</a>
                <a>About Amazon</a>
                <a>Invester Relation</a>
                <a>Amazon Devices</a>
                <a>Amazon Science</a>
            </ul>
            <ul>
                <p>Get to know us</p>
                <a>Careers</a>
                <a>Blog</a>
                <a>About Amazon</a>
                <a>Invester Relation</a>
                <a>Amazon Devices</a>
                <a>Amazon Science</a>
            </ul>
        </div>

        <div class="foot-panel3">
            <div class="logo"></div>
        </div>

        <div class="foot-panel4">
            <div class="pages">
                <a>Condition of Use</a>
                <a>Privacy Notic</a>
                <a>Your Ads Privacy Choices</a>
            </div>
            <div class="copyright">
                © 1996-2023, Amazon.com, Inc. or its affiliates
            </div>
        </div>
    </footer>
</body>    
</html>

---------------------------------------------------------------------------------------------------------------------------------

CSS PART :

* {
    margin: 0;
    font-family: Arial;
    border: border-box;
}

.navbar {
    height: 60px;
    background-color: #0f1111;
    color: white;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
}

.nav-logo {
    height: 50px;
    width: 100px;
}

.logo {
    background-image: url("amazon_logo.png");
    background-size: cover;
    height: 50px;
    width: 100px;
}

.border {
    border: 1.5px solid transparent;
}

.border:hover {
    border: 1.5px solid white;
}

/** b0x2**/
.add-first {
    color:#cccccc;
    font-size: 0.85rem;
    margin-left: 15px;
}

.add-second {
    font-size: 1rem;
    margin-left: 3px;
}

.address-icon {
    display: flex;
    align-items: center;
}

/** box 3 **/
.nav-search {
   display: flex; 
   justify-content: space-evenly;
   background-color: pink;
   width: 620px;
   height: 40px;
   border-radius: 4px;
}

.search-select {
    background-color: #f3f3f3;
    width: 50px;
    text-align: center;
    border-top-left-radius: 4px;
    border-bottom-left-radius: 4px;
    border: none;
}

.search-input {
    width: 100%;
    font-size: 1rem;
    border: none;
}

.search-icon {
    width: 45px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.2rem;
    background-color: rgb(255, 175, 0);
    border-top-right-radius: 4px;
    border-bottom-right-radius: 4px;
    color: #0f1111; 
}

.nav-search:hover {
    border: 2px solid orange;
}

/** box 4 **/
span {
    font-size: 0.7rem;
}

.nav-second {
    font-size: 0.85rem;
    font-weight: 700;
}

/** box6 **/
.nav-cart i {
    font-size: 35px;
}

.nav-cart {
    font-size: 0.85rem;
    font-weight: 700;
}

/** panel **/
.panel {
    height: 40px;
    background-color: #222f3d;
    display: flex;
    color: white;
    align-items: center;
    justify-content: space-evenly;
}

.panel-ops p {
    display: inline;
    margin-left: 10px;
}

.panel-ops {
    width: 70%;
    font-size: 0.85rem;
}

.panel-deals {
    font-size: 0.9rem;
    font-weight: 700;
}

/** hero section **/
.hero-section {
    background-image: url("hero_image.jpg");
    background-size: cover;
    height: 350px;
    display: flex;
    justify-content: center;
    align-items: flex-end;
}

.hero-msg {
    background-color: white;
    color: black;
    height: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 0.85rem;
    width: 80%;
    margin-bottom: 25px; 
}

.hero-msg a {
    color: #007185;
}

/** shop-section**/
.shop-section {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    background-color: #e2e7e6;
}

.box {
    /*border: 2px solid black;*/
    height: 400px;
    width: 23%;
    background-color: white;
    padding: 20px 0px 15px;
    margin-top: 15px;
}

.box-img {
    height: 300px;
    background-size: cover;
    margin-top: 1rem;
    margin-bottom: 1rem;

}

.box-content {
    margin-left: 1rem;
    margin-right: 1rem;
}

.box-content p {
    color: #007185;
}

/* footer */
footer {
    margin-top: 15px;
}

.foot-panel1 {
    background-color: #37475a;
    color: white;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 0.85rem;
}

.foot-panel2 {
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
    color: #dddddd;
}

.foot-panel3 {
    background-color: #222f3d;
    color: white;
    border-top: 0.5px solid white;
    height: 70px;
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

.foot-panel4 {
    background-color: #0f1111;
    color: white;
    height: 80px;
    font-size: 0.7rem;
    text-align: center;
}

.pages {
    padding-top: 25px;
}

.copyright {
    padding-top: 5px;
}

    -------------------------------------------------THE END-------------------------------------------------------------------
 
