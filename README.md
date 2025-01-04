# RedStore
This is an e-commece website with HTML 5 and CSS 3
also it's a responsive website!

# Indroduction about E-commerce websites
E-commerce is the buying and selling of goods and services over the Internet. It is conducted over computers, tablets, smartphones and other smart devices.
Almost anything can be purchased through E-commerce today.
Ecommerce operates in four market segments, including business-to- business, business-to-consumer, consumer-to-consumer, and consumer-to- business.
A website that allows people to buy and sell physical goods, services and digital products over the internet rather than a brick-and-mortar location.
Through an e-commerce website a business can process orders, accept payments, manage shipping & logistics and provide customer services.

That's all


# Landing page
Here's the landing page!

![image](https://github.com/codewithpapakwame/red-store/blob/d1e75715e0f6a6d1d1efbbb5f7d883c79b476224/screenshot1.jpg)

# Categories page
Here's the categories page!

![image](https://github.com/codewithpapakwame/red-store/blob/38e706a3050ce6d4cdaddef3354d49be51da4837/screenshot2.jpg)

# All products
![image](https://github.com/codewithpapakwame/red-store/blob/38e706a3050ce6d4cdaddef3354d49be51da4837/screenshot3.jpg)
![image](https://github.com/codewithpapakwame/red-store/blob/38e706a3050ce6d4cdaddef3354d49be51da4837/screenshot4.jpg)

#  Banner
Here's the banner page!

![image](https://github.com/codewithpapakwame/red-store/blob/38e706a3050ce6d4cdaddef3354d49be51da4837/screenshot5.jpg)

# Reviews and logos
Here's the reviews and logos page!

![image](https://github.com/codewithpapakwame/red-store/blob/38e706a3050ce6d4cdaddef3354d49be51da4837/screenshot6.jpg)

# Footer
Here's the footer page!

![image](https://github.com/codewithpapakwame/red-store/blob/38e706a3050ce6d4cdaddef3354d49be51da4837/screenshot7.jpg)

# Product Details
Here's the product details page!

![image](https://github.com/codewithpapakwame/red-store/blob/38e706a3050ce6d4cdaddef3354d49be51da4837/screenshot8.jpg)

# Login/Register
Here's the account page!

![image](https://github.com/codewithpapakwame/red-store/blob/38e706a3050ce6d4cdaddef3354d49be51da4837/screenshot9.jpg)

# Cart
Here's the cart page!

![image](https://github.com/codewithpapakwame/red-store/blob/38e706a3050ce6d4cdaddef3354d49be51da4837/screenshot10.jpg)

# Information about github and why it's used
GitHub is a web-based interface that uses Git, the open source version control software that lets multiple people make separate changes to web pages at the same time. As Carpenter notes, because it allows for real-time collaboration, GitHub encourages teams to work together to build and edit their site content.


## My whole code
Here's my whole code
## HTML 5
this is main
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RedStore | Ecommerce Website Design</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
<body>

    <div class="header">
    <div class="container">
        <div class="navbar">
            <div class="logo">
             <a href="index.html"><img src="images/logo.png" width="125px"></a>
            </div>
            <nav>
             <ul id="MenuItems">
                 <li><a href="index.html">Home</a></li>
                 <li><a href="products.html">Products</a></li>
                 <li><a href="">About</a></li>
                 <li><a href="">Contact</a></li>
                 <li><a href="account.html">Account</a></li>
             </ul>
            </nav> 
            <a href="cart.html"><img src="images/cart.png" width="30px" height="30px"></a>
            <img src="images/menu.png" class="menu-icon"
            onclick="menutoggle()">
         </div>
         <div class="row">
            <div class="col-2">
                <h1>Give Your Workout<br>A New Style!</h1>
                <p>Success isn't always about greatness. It's about
                consistency. Consistent<br>hard work gains success. Greatness
                will come.</p>
                    <a href="" class="btn">Explore Now &#8594;</a>
            </div>
            <div class="col-2">
                <img src="images/image1.png">
            </div>
         </div>
    </div>
</div>  

<!--------- featured categories ---------->
    <div class="categories">
        <div class="small-container">
            <div class="row">
                <div class="col-3">
                    <img src="images/category-1.jpg">
                </div>
                <div class="col-3">
                    <img src="images/category-2.jpg">
                </div>
                <div class="col-3">
                    <img src="images/category-3.jpg">
                </div>
            </div>
        </div>
        
    </div>
<!--------- featured products ------------> 
    <div class="small-container">
        <h2 class="title">Featured Products</h2>
        <div class="row">
            <div class="col-4">
                <a href="product-details.html"><img src="images/product-1.jpg"></a>
                <h4>Red Printed T-shirt</h4>
                <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-o"></i>
                </div>
                <p>$50.00</p>
            </div>
            <div class="col-4">
                <img src="images/product-2.jpg">
                <h4>HRX Sports Shoes</h4>
                <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-half-o"></i>
                </div>
                <p>$75.00</p>
            </div>
            <div class="col-4">
                <img src="images/product-3.jpg">
                <h4>HRX Gray Trackpants</h4>
                <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-half-o"></i>
                </div>
                <p>$45.00</p>
            </div>
            <div class="col-4">
                <img src="images/product-4.jpg">
                <h4>Blue Printed T-shirt</h4>
                <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-o"></i>
                </div>
                <p>$55.00</p>
            </div>
        </div>
        <h2 class="title">Latest Products</h2>
        <div class="row">
            <div class="col-4">
                <img src="images/product-5.jpg">
                <h4>Puma Gray Sports Shoes</h4>
                <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-o"></i>
                </div>
                <p>$95.00</p>
            </div>
            <div class="col-4">
                <img src="images/product-6.jpg">
                <h4>Black Printed T-shirt</h4>
                <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-half-o"></i>
                </div>
                <p>$55.00</p>
            </div>
            <div class="col-4">
                <img src="images/product-7.jpg">
                <h4>HRX Set of 3 Socks</h4>
                <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-half-o"></i>
                </div>
                <p>$30.00</p>
            </div>
            <div class="col-4">
                <img src="images/product-8.jpg">
                <h4>Black Fossil Watch</h4>
                <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-o"></i>
                </div>
                <p>$120.00</p>
            </div>
        </div>
        <div class="row">
            <div class="col-4">
                <img src="images/product-9.jpg">
                <h4>Black Sportx Watch</h4>
                <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-o"></i>
                </div>
                <p>$135.00</p>
            </div>
            <div class="col-4">
                <img src="images/product-10.jpg">
                <h4>Black HRX Shoes</h4>
                <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-half-o"></i>
                </div>
                <p>$50.00</p>
            </div>
            <div class="col-4">
                <img src="images/product-11.jpg">
                <h4>Gray Nike Shoes</h4>
                <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-half-o"></i>
                </div>
                <p>$55.00</p>
            </div>
            <div class="col-4">
                <img src="images/product-12.jpg">
                <h4>HRX Black Trackpants</h4>
                <div class="rating">
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star"></i>
                    <i class="fa fa-star-o"></i>
                </div>
                <p>$75.00</p>
            </div>
        </div>
    </div>
<!--------- offer ----------> 
    <div class="offer">
        <div class="small-container">
            <div class="row">
                <div class="col-2">
                    <img src="images/exclusive.png" class="offer-img">
                </div>
                <div class="col-2">
                    <p>Exclusively Available on RedStore</p>
                    <h1>Smart Band 4</h1>
                    <small>The Mi Smart 4 features a 39.9% larger
                    (than Mi Band 3) AMOLED color full-touch display with
                    adjustable brightness, so everything is clear as can 
                    be.</small>
                    <a href="" class="btn">Buy Now &#8594;</a>
                </div>
            </div>
        </div>
    </div>

<!--------- testimonial ---------->   
    <div class="testimonial">
        <div class="small-container">
            <div class="row">
                <div class="col-3">
                    <i class="fa fa-quote-left"></i>
                    <p>Lorem Ipsum is simply dummy text of the printing
                    and typesetting industry. Lorem Ipsum has been the
                    industry's standard dummy text ever</p>
                    <div class="rating">
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star-o"></i>
                    </div>
                    <img src="images/user-1.png">
                    <h3>Sean Parker</h3>
                </div>
                <div class="col-3">
                    <i class="fa fa-quote-left"></i>
                    <p>Lorem Ipsum is simply dummy text of the printing
                    and typesetting industry. Lorem Ipsum has been the
                    industry's standard dummy text ever</p>
                    <div class="rating">
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star-o"></i>
                    </div>
                    <img src="images/user-2.png">
                    <h3>Mike Smith</h3>
                </div>
                <div class="col-3">
                    <i class="fa fa-quote-left"></i>
                    <p>Lorem Ipsum is simply dummy text of the printing
                    and typesetting industry. Lorem Ipsum has been the
                    industry's standard dummy text ever</p>
                    <div class="rating">
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star"></i>
                        <i class="fa fa-star-o"></i>
                    </div>
                    <img src="images/user-3.png">
                    <h3>Mabel Joe</h3>
                </div>
            </div>
        </div>
    </div>

<!-- brands -->
    <div class="brands">
        <div class="small-container">
            <div class="row">
                <div class="col-5">
                    <img src="images/logo-godrej.png">
                </div>
                <div class="col-5">
                    <img src="images/logo-oppo.png">
                </div>
                <div class="col-5">
                    <img src="images/logo-coca-cola.png">
                </div>
                <div class="col-5">
                    <img src="images/logo-paypal.png">
                </div>
                <div class="col-5">
                    <img src="images/logo-philips.png">
                </div>
            </div>
        </div>
    </div>

<!-- footer -->

    <div class="footer">
        <div class="container">
            <div class="row">
                <div class="footer-col-1">
                    <h3>Download Our App</h3>
                    <p>Download App for Android and ios mobile phone.</p>
                    <div class="app-logo">
                        <img src="images/play-store.png">
                        <img src="images/app-store.png">
                    </div>
                </div>
                <div class="footer-col-2">
                    <img src="images/logo-white.png">
                    <p>Our Purpose Is To Sustainably Make the Pleasure and
                    Benefits of Sports Accessible to the Many.</p>
                </div>
                <div class="footer-col-3">
                    <h3>Useful Links</h3>
                    <ul>
                        <li>Coupons</li>
                        <li>Blog Post</li>
                        <li>Return Policy</li>
                        <li>Join Affiliate</li>
                    </ul>
                </div>
                <div class="footer-col-4">
                    <h3>Follow us</h3>
                    <ul>
                        <li>Facebook</li>
                        <li>Twitter</li>
                        <li>Instagram</li>
                        <li>Youtube</li>
                    </ul>
                </div>
            </div>
            <hr>
            <p class="copyright">Copyright 2024 - Papa Kwame or (github account ronaldoisthegoatCR7)</p>
        </div>
    </div>
<!-- js for toggle menu -->
    <script>
        var MenuItems = document.getElementById("MenuItems");

        MenuItems.style.maxHeight = "0px";

        function menutoggle(){
            if(MenuItems.style.maxHeight == "0px")
                {
                    MenuItems.style.maxHeight = "200px"
                }
            else
                {
                    MenuItems.style.maxHeight = "0px"
                }
        }
    </script>

</body>
</html>
```
## CSS 5
```
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body{
    font-family: 'Poppins', sans-serif;
}

.navbar{
    display: flex;
    align-items: center;
    padding: 20px;
}
nav{
    flex: 1;
    text-align: right;
}
nav ul{
    display: inline-block;
    list-style-type: none;
}
nav ul li{
    display: inline-block;
    margin-right: 20px;
}
a{
    text-decoration: none;
    color: #555;
}
p{
    color: #555;
}
.container{
    max-width: 1300px;
    margin: auto;
    padding-left: 25px;
    padding-right: 25px;
}
.row{
    display: flex;
    align-items: center;
    flex-wrap: wrap;
    justify-content: space-around;
}
.col-2{
    flex-basis: 50%;
    min-width: 300px;
}
.col-2 img{
    max-width: 100%;
    padding: 50px 0;
}
.col-2 h1{
    font-size: 50px;
    line-height: 60px;
    margin: 25px 0;
}
.btn{
    display: inline-block;
    background-color: #ff523b;
    color: #fff;
    padding: 8px 30px;
    margin: 30px 0;
    border-radius: 30px;
    transition: background 0.5s;
}

.btn:hover{
    background: #563434;
}

.header{
    background: radial-gradient(#fff,#ffd6d6);
}
.header .row{
    margin-top: 70px;
}
.categories{
    margin: 70px 0;
}
.col-3{
    flex-basis: 30%;
    min-width: 250px;
    margin-bottom: 30px;
}
.col-3 img{
    width: 100%;
}
.small-container{
    max-width: 1080px;
    margin: auto;
    padding-left: 25px;
    padding-right: 25px;
}
.col-4{
    flex-basis: 25%;
    padding: 10px;
    min-width: 200px;
    margin-bottom: 50px;
    transition: transform 0.5s;
}
.col-4 img{
    width: 100%;
}

.title{
    text-align: center;
    margin: 0 auto 80px;
    position: relative;
    line-height: 60px;
    color: #555;
}
.title::after{
    content: '';
    background: #ff523b;
    width: 80px;
    height: 5px;
    border-radius: 5px;
    position: absolute;
    bottom: 0;
    left: 50%;
    transform: translateX(-50%);
}

h4{
    color: #555;
    font-weight: normal;
}
.col-4 p{
    font-size: 14px;
}
.rating .fa{
    color: #ff523b;
}

.col-4:hover{
    transform: translateY(-5px);
}
/* offer */

.offer{
    background: radial-gradient(#fff,#ffd6d6);
    margin-top: 80px;
    padding: 30px 0;
}
.col-2 .offer-img{
    padding: 50px;
}
small{
    color: #555;
}

/* testimonial */

.testimonial{
    padding-top: 100px;
}
.testimonial .col-3{
    text-align: center;
    padding: 40px 20px;
    box-shadow: 0 0 20px 0px rgba(0,0,0,0.1);
    cursor: pointer;
    transition: transform 0.5s;
}
.testimonial .col-3 img{
    width: 50px;
    margin-top: 20px;
    border-radius: 50%;
}
.testimonial .col-3:hover{
    transform: translateY(-10px);
}
.fa.fa-quote-left{
    font-size: 34px;
    color: #ff523b;
}
.col-3 p{
    font-size: 12px;
    margin: 12px 0;
    color: #777;
}

.testimonial .col-3 h3{
    font-weight: 600;
    color: #555;
    font-size: 16px;
}
/* brands */
.brands{
    margin: 100px auto;
}
.col-5{
    width: 160px;
}
.col-5 img{
    width: 100%;
    cursor: pointer;
    filter: grayscale(100%);
}
.col-5 img:hover{
    filter: grayscale(0);
}

/* footer */

.footer{
    background: #000;
    color: #8a8a8a;
    font-size: 14px;
    padding: 60px 0 20px;
}
.footer p{
    color: #8a8a8a;
}
.footer h3{
    color: #fff;
    margin-bottom: 20px;
}
.footer-col-1, .footer-col-2, .footer-col-3, .footer-col-4{
    min-width: 250px;
    margin-bottom: 20px;
}
.footer-col-1{
    flex-basis: 30%;
}
.footer-col-2{
    flex: 1;
    text-align: center;
}
.footer-col-2 img{
    width: 180px;
    margin-bottom: 20px;
}
.footer-col-3, .footer-col-4{
    flex-basis: 12%;
    text-align: center;
}
ul{
    list-style-type: none;
}
.app-logo{
    margin-top: 20px;
}
.app-logo img{
    width: 140px;
}
.footer hr{
    border: none;
    background: #b5b5b5;
    height: 1px;
    margin: 20px 0;
}
.copyright{
    text-align: center;
}

.menu-icon{
    width: 28px;
    margin-left: 20px;
    display: none;
}
/* media query for menu */

@media only screen and (max-width: 800px){

    nav ul{
        position: absolute;
        top: 70px;
        left: 0;
        background: #333;
        width: 100%;
        overflow: hidden;
        transition: max-height 0.5s;
    }
    nav ul li{
        display: block;
        margin-right: 50px;
        margin-top: 10px;
        margin-bottom: 10px;
    }
    nav ul li a{
        color: #fff;
    }
    .menu-icon{
        display: block;
        cursor: pointer;
    }
}
/* all products page */

.row-2{
    justify-content: space-between;
    margin: 100px auto 50px;
}
select{
    border: 1px solid #ff523b;
    padding: 5px;
}
select:focus{
    outline: none;
}
.page-btn{
    margin: 0 auto 80px;
}
.page-btn span{
    display: inline-block;
    border: 1px solid #ff523b;
    margin-left: 10px;
    width: 40px;
    height: 40px;
    text-align: center;
    line-height: 40px;
    cursor: pointer;
}
.page-btn span:hover{
    background: #ff523b;
    color: #fff;
}

/* single product detials */

.single-product{
    margin-top: 80px;
}
.single-product .col-2 img{
    padding: 0;
}
.single-product .col-2{
    padding: 20px;
}
.single-product h4{
    margin: 20px 0;
    font-size: 22px;
    font-weight: bold
}
.single-product select{
    display: block;
    padding: 10px;
    margin-top: 20px;
}
.single-product input{
    width: 50px;
    height: 40px;
    padding-left: 10px;
    font-size: 20px;
    margin-right: 10px;
    border: 1px solid #ff523b;
}
input:focus{
    outline: none;
}
.single-product .fa{
    color: #ff523b;
    margin-left: 10px;
}

.small-img-row{
    display: flex;
    justify-content: space-between;
}
.small-img-col{
    flex-basis: 24%;
    cursor: pointer;
}

/* cart items */

.cart-page{
    margin: 80px auto;
}
table{
    width: 100%;
    border-collapse: collapse;
}
.cart-info{
    display: flex;
    flex-wrap: wrap;
}
th{
    text-align: left;
    padding: 5px;
    color: #fff;
    background: #ff523b;
    font-weight: normal;
}

td{
    padding: 10px 5px;
}
td input{
    width: 40px;
    height: 30px;
    padding: 5px;
}
td a{
    color: #ff523b;
    font-size: 12px;
}
td img{
    width: 80px;
    height: 80px;
    margin-right: 10px;
}
.total-price{
    display: flex;
    justify-content: flex-end;
}

.total-price table{
    border-top: 3px solid #ff523b;
    width: 100%;
    max-width: 400px;
}
td:last-child{
    text-align: right;
}
th:last-child{
    text-align: right;
}

/* a;ldfkfadsladjsfd;akf;aldsf;lkadsjfalsdjkfladskjf;lakdsjfkalsd;jfals;als */

.account-page{
    padding: 50px;
    background: radial-gradient(#fff,#ffd6d6);
}
.form-container{
    background: #fff;
    width: 300px;
    height: 400px;
    position: relative;
    text-align: center;
    padding: 20px 0;
    margin: auto;
    box-shadow: 0 0 20px 0px rgba(0,0,0,0.1);
    overflow: hidden;
}
.form-container span{
    font-weight: bold;
    padding: 0 10px;
    color: #555;
    cursor: pointer;
    width: 100px;
    display: inline-block;
}
.form-btn{
    display: inline-block;
}
.form-container form{
    max-width: 300px;
    padding: 0 20px;
    position: absolute;
    top: 130px;
    transition: transform 1s;
}
form input{
    width: 100%;
    height: 30px;
    margin: 10px 0;
    padding: 0 10px;
    border: 1px solid #ccc;
}
form .btn{
    width: 100%;
    border: none;
    cursor: pointer;
    margin: 10px 0;
}
form .btn:focus{
    outline: none;
}
#LoginForm{
    left: -300px;
}
#RegForm{
    left: 0;
}
form a{
    font-size: 12px;
}
#Indicator{
    width: 100px;
    border: none;
    background: #ff523b;
    height: 3px;
    margin-top: 8px;
    transform: translateX(100px);
    transition:  transform 1s;
}











/* media query for less than 600 screen size */
@media only screen and (max-width: 600px){
    .row{
        text-align: center;
    }
    .col-2, .col-3, .col-4{
        flex-basis: 100%;
    }
    .single-product .row{
        text-align: left;
    }
    .single-product .col-2{
        padding: 20px 0;
    }
    .single-product h1{
        font-size: 26px;
        line-height: 32px;
    }

    .cart-info p{
        display: none;
    }
}
```

# Videos Part 1 to 5
Part 1 = https://www.youtube.com/watch?v=yQimoqo0-7g&list=PLjwm_8O3suyM_2Lo9aAIw3HqjOPor8j9g













Part 2 = https://www.youtube.com/watch?v=ZbnvP_hmxfE&list=PLjwm_8O3suyM_2Lo9aAIw3HqjOPor8j9g&index=3













Part 3 = https://www.youtube.com/watch?v=ENyk_W-Eleo&list=PLjwm_8O3suyM_2Lo9aAIw3HqjOPor8j9g&index=3








Part 4 = https://www.youtube.com/watch?v=oXrlgOEiy6o&list=PLjwm_8O3suyM_2Lo9aAIw3HqjOPor8j9g&index=4










Part 5 = https://www.youtube.com/watch?v=vOXGuNVRGpA&list=PLjwm_8O3suyM_2Lo9aAIw3HqjOPor8j9g&index=5




### Thank you ❤️❤️🫶🏻🫶🏻👋🏾
