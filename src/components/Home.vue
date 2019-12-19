<template>
    <div class="home">
        <div class="yellow"></div>
        <img class="food" src="../assets/food-logo.svg">
            <nav class="head">
                <span class="left">
                    <img src="../assets/efi.svg">
                </span>
                <span class="right">
                    <span class="link_wrapper">
                        <a class="link" href="#">HOME</a>
                    </span>
                    <span class="link_wrapper">
                        <a class="link" href="#">ABOUT US</a>
                    </span>
                    <span class="link_wrapper">
                        <a class="link" href="#">SERVICES</a>
                    </span>
                    <span class="link_wrapper">
                        <a class="link" href="#">DELIVERY</a>
                    </span>
                    <span class="link_wrapper">
                        <a class="link" href="#">CONTACT US</a>
                    </span>
                </span>
                <span class="carrier">
                    <img  src="../assets/blue.svg">
                </span>
            </nav>
            <div class="wrapper">
                <div class="left-side">
                    <img class="leaf" src="../assets/cropped-leaf.svg">
                    <p class="yummy">YUMMY</p>
                    <p class="breakfast">BREAKFAST!</p>
                    <p class="order">ORDER BREAKFAST THE EASY WAY YUMMY BREAKFAST (25% OFFER)</p>
                    <button class="big-btn">
                        <img src="../assets/cart.svg">
                        <a class="text">ORDER NOW</a>
                    </button>
                    <ul class="list1">
                        <li><button class="btn1"></button></li>    
                        <li><button class="btn2"></button></li>
                        <li><button class="btn3"></button></li>
                        <li><button class="btn4"></button></li>
                        <li><img class="arrow" src="../assets/arrow.svg"></li>
                    </ul>
                </div>
                <div class="right-side">
                    <img class="food-image" src="../assets/food-image.svg">
                    <p class="copy-right"> &copy; 2019 All Right Reserved by <b>Abdullah Sajol</b></p>
                    <ul class="list2">
                        <li>
                            <a href="#"><img class="facebook" src="../assets/facebook.svg"></a>
                        </li>
                        <li>
                            <a href="#"><img class="instagram" src="../assets/instagram.svg"></a>
                        </li>
                        <li>
                            <a href="#"><img class="twitter" src="../assets/twitter.svg"></a>
                        </li>
                    </ul>
                </div>
            </div>
    </div>
 </template>

<script>
export default {
    name:"Home"
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css?family=Oswald&display=swap');
.home {
    font-family: 'Oswald', sans-serif;
    width: 100vw;
    height: 100vh;
    background: #FEF6E7;
    overflow: hidden;
    }
.food {
    z-index: -3;
    margin-top: -40px;
}
.yellow {
    position: relative;
}
.yellow::after {
    content: url("../assets/yellow.svg");
    position: absolute;
    right: 0;
    top:0;
}
.carrier {
    margin-right: 50px;
    z-index: 1;
}
.right {
    margin-left: 340px;
    padding-top: 20px;
    z-index: 999;
}
.left {
    padding-left: 30px;
}
.head {
    display: flex;
    justify-content: space-between;
    margin-top: -170px;
}
.link_wrapper {
    padding-left: 30px;
}
.link:hover {
    color:rgb(235, 186, 96);
    cursor: pointer;
}
.link {
    color:#2C3C27;
    text-decoration: none;
}
a {
    cursor: pointer;
}
.wrapper {
    display: flex;
    margin: 50px 0px 0px 230px;
}
.leaf {
    padding-left: 320px;
    margin-top: -20px;
}
.yummy {
    font-weight: bold;
    font-size: 120px;
    text-shadow: -2px 0 black, 0 2px black,
    2px 0 black, 0 -2px black;
    color: #FEF6E7;
    margin-top: -40px; 
}
.breakfast {
    font-weight: bold;
    font-size: 105px;
    color: #23331E;
    margin-top: -160px;
}
.order {
    font-weight: 600;
    font-size: 16px;
    line-height: 30px;
    letter-spacing: 0.02em;
    color: #263621;
    opacity: 0.75;
    margin-top: -105px;
}
.big-btn {
    width: 200px;
    height: 70px;
    background: #00AA51;
    border-radius: 35px;
    border-radius: 35px;
    margin-top: 20px;
}
.text {
    font-weight: 600;
    font-size: 16px;
    line-height: 17px;
    letter-spacing: 0.03em;
    color: #FFFFFF;
    padding-left:10px;
}
.right-side {
    z-index: 1;
}
.food-image {
    margin:-300px 0px 0px -330px;
}
.copy-right {
    font-weight: normal;
    font-size: 14px;
    letter-spacing: 0.02em;
    color: #918A4C;
    margin: -140px 0px 0px 450px;
}
.arrow {
    margin: 250px 0px 0px 0px;
}
.list1 {
    margin: -230px 0px 0px -190px;
}
.list2 {
    margin: -250px 0px 0px 630px;
}
.list1 li{
    list-style-type: none;
    line-height: 15px;
}
.list2 li{
    list-style-type: none;
    line-height: 50px;
}
b{
    color: rgb(112, 105, 37);
}
.btn1 {
    width: 35px;
     height: 1px;
     background: #00AA51;
}
.btn2 {
    width: 20px;
    height: 1px;
    background: #1C1B21;
    opacity: 0.25;
}
.btn3 {
    width: 20px;
    height: 1px;
    background: #1C1B21;
    opacity: 0.25;
}
.btn4 {
    width: 20px;
    height:1px;
    background: #1C1B21;
    opacity: 0.25;
}
</style>