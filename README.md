<!DOCTYPE html>
<html lang="en">

<head>
    <link rel="stylesheet" href="css/style.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css"
        integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <title>Restoran</title>
</head>

<body>
    <header class="header">
        <a href="#" class="logo">
            <img src="Images/logo.png" alt="logo">
        </a>
        <nav class="navbar">
            <a href="#" class="active">Home</a>
            <a href="#">About</a>
            <a href="#">Menu</a>
            <a href="#">Products</a>
            <a href="#">Review</a>
            <a href="#">Contact</a>
            <a href="#">Blogs</a>
        </nav>
        <div class="buttons">
            <button>
                <i class="fas fa-search"></i>
            </button>
            <button>
                <i class="fas fa-shopping-cart"></i>
            </button>
            <button>
                <i class="fas fa-bars"></i>
            </button>
        </div>
    </header>
    <section class="home">
        <div class="content">
            <h3>ATILLA RESTORAN</h3>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quibusdam ipsum sapiente nostrum officiis omnis
                fugit, ducimus sint ratione optio?</p>
            <a href="#" class="btn">Order Now</a>
        </div>
    </section>
    <section class="menu">
        <h1 class="heading">our <span>menu</span> </h1>
        <div class="box-container">
            <div class="box">
                <div class="box-head">
                    <img src="Images/menu-1.png" alt="menu">
                    <span class="menu-category">PIZZA</span>
                    <h3>6 Mini Pizzas</h3>
                    <div class="price">$104.99 <span>119.99</span>
                    </div>
                    <div class="box-bottom"><a href="#" class="btn">add to cart</a></div>
                </div>
            </div>
            <div class="box">
                <div class="box-head">
                    <img src="Images/menu-2.png" alt="menu">
                    <span class="menu-category">BURGER</span>
                    <h3>5 Mini Burgers</h3>
                    <div class="price">$99.99 <span>109.99</span>
                    </div>
                    <div class="box-bottom"><a href="#" class="btn">add to cart</a></div>
                </div>
            </div>
            <div class="box">
                <div class="box-head">
                    <img src="Images/menu-3.png" alt="menu">
                    <span class="menu-category">PIZZA</span>
                    <h3>2 Mixed Pizzas</h3>
                    <div class="price">$79.99 <span>99.99</span>
                    </div>
                    <div class="box-bottom"><a href="#" class="btn">add to cart</a></div>
                </div>
            </div>
            <div class="box">
                <div class="box-head">
                    <img src="Images/menu-4.png" alt="menu">
                    <span class="menu-category">BURGER</span>
                    <h3>3 Mini Burgers</h3>
                    <div class="price">$119.99 <span>130.99</span>
                    </div>
                    <div class="box-bottom"><a href="#" class="btn">add to cart</a></div>
                </div>
            </div>

    </section>
    <section class="products">
        <h1 class="heading">our <span>products</span> </h1>
        <div class="box-container">

            <!-- BOX 1 -->
            <div class="box">
                <div class="box-head">
                    <span class="title"> Mini Burger </span>
                    <a href="#" class="name">Bacon Burger</a>
                </div>
                <div class="image"><img src="Images/product-1.png" alt="menu"></div>
                <div class="box-bottom">
                    <div class="info">
                        <b class="price">$24.00</b>
                        <span class="amount">110gr / 300cal</span>
                    </div>
                    <div class="product-btn">
                        <a href="#"><i class="fas fa-plus"></i></a>
                    </div>
                </div>
            </div>

            <!-- BOX 2 -->
            <div class="box">
                <div class="box-head">
                    <span class="title"> Mini Burger </span>
                    <a href="#" class="name">Bacon Burger</a>
                </div>
                <div class="image"><img src="Images/product-2.png" alt="menu"></div>
                <div class="box-bottom">
                    <div class="info">
                        <b class="price">$24.00</b>
                        <span class="amount">110gr / 300cal</span>
                    </div>
                    <div class="product-btn">
                        <a href="#"><i class="fas fa-plus"></i></a>
                    </div>
                </div>
            </div>

            <!-- BOX 3 -->
            <div class="box dark-bg">
                <div class="box-head">
                    <span class="title"> Mini Burger </span>
                    <a href="#" class="name">Bacon Burger</a>
                </div>
                <div class="image"><img src="Images/dark-product.jpg" alt="menu"></div>
                <div class="box-bottom">
                    <div class="info">
                        <b class="price">$24.00</b>
                        <span class="amount">110gr / 300cal</span>
                    </div>
                    <div class="product-btn">
                        <a href="#"><i class="fas fa-plus"></i></a>
                    </div>
                </div>
            </div>

        </div> <!-- box-container -->
    </section>
    <section class="about">
        <h1 class="heading">about <span>us</span></h1>
        <div class="row">
            <div class="image">
                <img src="Images/about.jpg" alt="about">
            </div>
            <div class="content">
                <h3>What is the secret our Burgers</h3>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Neque consequuntur saepe assumenda quisquam
                    corporis, error quasi delectus reiciendis! </p>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Neque consequuntur saepe assumenda quisquam
                    corporis, error quasi delectus reiciendis! </p>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Neque consequuntur saepe assumenda quisquam
                    corporis, error quasi delectus reiciendis! </p>
                <a href="#" class="btn">learn more</a>
            </div>
        </div>
    </section>

    <section class="review">
        <h1 class="heading">customer's <span>review</span></h1>
        <div class="box-container">
            <div class="box">
                <img src="Images/quote.png" alt="quote">
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Omnis, aliquam velit delectus tempore
                    facere obcaecati quos, tempora distinctio quia reprehenderit similique nulla. </p>
                <img src="Images/avatar-1.png" alt="user" class="user">
                <h3>Jesica Bengal</h3>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half"></i>
                </div>
            </div>
            <div class="box">
                <img src="Images/quote.png" alt="quote">
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Omnis, aliquam velit delectus tempore
                    facere obcaecati quos, tempora distinctio quia reprehenderit similique nulla. </p>
                <img src="Images/avatar-2.png" alt="user" class="user">
                <h3>Antoni Sargan</h3>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half"></i>
                </div>
            </div>
            <div class="box">
                <img src="Images/quote.png" alt="quote">
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Omnis, aliquam velit delectus tempore
                    facere obcaecati quos, tempora distinctio quia reprehenderit similique nulla. </p>
                <img src="Images/avatar-3.png" alt="user" class="user">
                <h3>Jenna Dark</h3>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half"></i>
                </div>
            </div>
        </div>
    </section>
    <section class="contact">
        <h1 class="heading">contact <span>us</span></h1>
        <div class="row">
            <iframe class="map"
                src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d48658.3099435795!2d49.82609065!3d40.33914325!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x40307e987168b5ed%3A0xbe6e53d65c798d2!2zU2ViYWlsLCBCYWvDvA!5e0!3m2!1str!2saz!4v1745682394189!5m2!1str!2saz"
                loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            <form>
                <h3>get in touch</h3>
                <div class="inputbox">
                    <i class="fas fa-user"></i>
                    <input type="text" placeholder="name">
                </div>
                <div class="inputbox">
                    <i class="fas fa-envelope"></i>
                    <input type="email" placeholder="email">
                </div>
                <div class="inputbox">
                    <i class="fas fa-phone"></i>
                    <input type="number" placeholder="number">

                </div>
                <input type="submit" class="btn" value="contact now">
            </form>
        </div>
    </section>
    <section class="blog">
        <h1 class="heading">our <span>blog</span></h1>
        <div class="box-container">
            <div class="box">
                <div class="image">
                    <img src="Images/blog-1.jpg" alt="blog">
                </div>
                <div class="content">
                    <a href="#" class="title">how to make burgers?</a>
                    <span>by admin / 10st may, 2020</span>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium quod magnam minus cum
                        veniam. </p>
                        <a href="#" class="btn">read more</a>
                </div>
            </div>
            <div class="box">
                <div class="image">
                    <img src="Images/blog-2.jpg" alt="blog">
                </div>
                <div class="content">
                    <a href="#" class="title">how to make burgers?</a>
                    <span>by admin / 10st may, 2020</span>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium quod magnam minus cum
                        veniam. </p>
                        <a href="#" class="btn">read more</a>
                </div>
            </div>
            <div class="box">
                <div class="image">
                    <img src="Images/blog-3.jpg" alt="blog">
                </div>
                <div class="content">
                    <a href="#" class="title">how to make burgers?</a>
                    <span>by admin / 10st may, 2020</span>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium quod magnam minus cum
                        veniam. </p>
                        <a href="#" class="btn">read more</a>
                </div>
            </div>

        </div>
    </section>
    <style> @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600&display=swap');

:root {
    --main-color: #e84242;
    --black-color: #0c0b0b;
    --border: 0.1rem solid rgba(255, 255, 255, 0.4);
}

* {
    font-family: "Poppins", sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    outline: none;
    border: none;
    text-decoration: none;
    text-transform: capitalize;
    transition: 0.2s ease;
}

html {
    font-size: 62.5%;
    overflow-x: hidden;
    scroll-padding-top: 9rem;
    scroll-behavior: smooth;
}

html::-webkit-scrollbar {
    width: 0.8rem;
    background-color: white;
}

html::-webkit-scrollbar-thumb {
    border-radius: 3rem;
    background-color: var(--black-color);
}


.header .logo img {
    height: 10rem;
}

header {
    background-color: white;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 7%;
    margin: 2rem 7%;
    border-radius: 30rem;
    box-shadow: 0px 0px 17px -2px rgba(0, 0, 0, 0.75);
    position: sticky;
    top: 0;
    z-index: 1000;
}

.header .navbar a {
    margin: 0 1rem;
    font-size: 1.6rem;
    color: var(--black-color);
    border-bottom: 0.1rem solid transparent;
}

.header .navbar .active,
.header .navbar a:hover {
    border-color: var(--main-color);
    padding-bottom: 0.5rem;
}

.header .buttons {
    cursor: pointer;
    font-size: 2.5rem;
    margin-left: 2rem;
    background-color: transparent;
}

body {
    background-color: var(--main-color);

}

section {
    padding: 3.5rem 7%;
}

.btn {
    margin-top: 1rem;
    display: inline-block;
    padding: 2rem 3.60rem;
    border-radius: 30rem;
    font-size: 17px;
    color: #fff;
    background-color: black;
    cursor: pointer;
    
   

}
.btn:hover {
    opacity: 0.9;
}

.heading {
    color: white;
    text-transform: uppercase;
    font-size: 4rem;
    margin-bottom: 3.5rem;
    border-bottom: 0.1rem solid #fff;
}

.heading span {
    text-transform: uppercase;
    color: var(--black-color);
}



.home {
    min-height: 100vh;
    display: flex;
    background: url(../Images/home.jpg) no-repeat;
    background-size: cover;
    background-position: center;
    margin-top: -14.5rem;
    display: flex;
    align-items: center;
}

.home .content {
    max-width: 60rem;
}

.home .content h3 {
    font-size: 6rem;
    color: white;

}

.home .content p {
    font-size: 2rem;
    font-weight: 300;
    line-height: 1.8;
    padding: 1rem 0;
    color: #ccc;
}

.menu .box-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(25rem, 1fr));
    gap: 1.5rem;
}

.menu .box-container .box img {
    width: 100%;
    object-fit: cover;
}

.menu .box-container .box {
    padding: 3rem;
    background-color: #fff;
    border-radius: 3rem;
    min-height: 40rem;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: space-between;
}

.menu .box-container .box .menu-category {
    font-size: 1.2rem;
    text-transform: uppercase;
}

.menu .box-container .box h3 {
    font-size: 3rem;
    padding: 1rem 0;

}

.menu .box-container .box .price {
    font-size: 2.5rem;
    padding: 0.5rem 0;
}

.menu .box-container .box .price span {
    text-decoration: line-through;
    font-size: 1.5rem;
    font-weight: 300;
}

.products .box-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(25rem, 1fr));
    gap: 1.5rem;

}

.products .box-container .box {
    text-align: center;
    background-color: #fff;
    position: relative;
    border-radius: 3rem;
    height: 60rem;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    padding: 3rem;
}


.products .box-container .box .box-head {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    position: relative;
    z-index: 10;
}

.products .box-container .box .box-head .title {
    font-size: 1.4rem;

}

.products .box-container .box .box-head .name {
    font-size: 4rem;
    font-weight: bold;
    text-align: start;
    overflow-wrap: anywhere;
}

a {
    color: var(--black-color);
    text-decoration: none;
}

.products .box-container img {
    position: absolute;
    top: 50%;
    left: 50%;
    width: 100%;
    object-fit: cover;
    transform: translate(-50%, -50%);
    border-radius: 3rem;
}

.products .box-container .dark-bg .box-head .name,
.products .box-container .dark-bg .box-head .title {
    color: #fff;
}

.products .box-container .dark-bg img {
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    transform: unset;
}

.products .box-container .box-bottom {
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: relative;
    z-index: 10;
}

.products .box-container .box-bottom .info {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
}

.products .box-container .box-bottom .info .price {
    font-size: 3rem;
}

.products .box-container .box-bottom .info .amount {
    font-size: 1.4rem;
}

.products .box-container .dark-bg .box-bottom .info .price,
.products .box-container .dark-bg .box-bottom .info .amount {
    color: #fff;
}

.products .box-container .box-bottom .product-btn a {
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 50%;
    width: 6.5rem;
    height: 6.5rem;
    border: 0.2rem solid var(--main-color);
}

.products .box-container .box-bottom .product-btn a i {
    font-size: 1.6rem;
    color: var(--main-color);
}

.about .row .image {
    flex: 1 1 45rem;
}

.about .row img {
    width: 100%;
}

.about .row {
    display: flex;
    flex-wrap: wrap;
    column-gap: 2rem;
   
}
.about .row .content {
    flex: 1 1 45rem;
}
.about .row .content h3{
    font-size: 3rem;
    color: #fff;
}
.about .row .content p{
    font-size: 1.6rem;
    padding: 1rem 0;
    color: #ccc;
    line-height: 1.8;

}


.header .buttons button i {
    font-size: 2.5rem; /* iconlari boyudur */
    color: var(--black-color); /* istesen reng de vere bilersen */
}


.review .box-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(25rem, 1fr));
    gap: 1.5rem;
}

.review .box-container .box{
    border: var(--border);
    text-align: center;
    padding: 3rem 2rem;
    background-color: #fff;
    border-radius: 3rem;
}
.review .box-container .box p{
    font-size: 1.5rem;
    line-height: 1.8;
    padding: 2rem 0;
}
.review .box-container .box .user{
    height: 7rem;
    width: 7rem;
    border-radius: 50%;
    object-fit: cover;
}
.review .box-container .box h3{
    padding: 1rem 0;
    font-size: 2rem;
    color: var(--main-color);
}
.review .box-container .box .stars i{
    font-size: 1.5rem;
    color: gold;
}

.contact .row{
    display: flex;
    background-color: var(--black-color);
    flex-wrap: wrap;
    gap: 10rem;
}

.contact .row .map{
    flex: 1 1 45rem;
    width: 100%;
    object-fit: cover;
}

.contact .row form{
    flex: 1 1 45rem;
   text-align: center;
    padding: 5rem 2rem;
}
.contact .row form h3{
text-transform: uppercase;
font-size: 3.5rem;
color: #fff;
}
.contact .row form .inputbox{
    display: flex;
    align-items: center;
    margin: 2rem 0;
    border: var(--border);
}
.contact .row form .inputbox i{
    color: #fff;
    font-size: 2rem;
    padding: 2rem;
}
.contact .row form .inputbox input{
    width: 100%;
    padding: 2rem;
    font-size: 1.7rem;
    color: #fff;
    text-transform: none;
    background: none;
}
.contact .row form .btn{
    color: var(--main-color);
    background-color: #fff;
    font-weight: bold;
}
.blog .box-container{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(30rem, 1fr));
    gap: 1.5rem;
}
.blog .box-container .box{
    background-color: #fff;
    border-radius: 3rem;
}
.blog .box-container .box .image{
    height: 25rem;
    overflow: hidden;
    width: 100%;
    border-top-left-radius: 3rem;
    border-top-right-radius: 3rem;

}
.blog .box-container .box .image img{
    height: 100%;
    width: 100%;
    object-fit: cover;
}
.blog .box-container .box .content{
    padding: 2rem;
} 
.blog .box-container .box:hover .image img{
    transform: scale(1.2);
}
.blog .box-container .box .content span{
    display: block;
    padding-top: 1rem;
    font-size: 2rem;
}
.blog .box-container .box .content .title{
    line-height: 1.5rem;
    font-size: 2.5rem;
}
    </style>


</body>

</html>
