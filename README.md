# webtest
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Band</title>
    <link rel="icon" type="image/x-icon" href="./assets/css/img/heo.png">
    <link rel="stylesheet"  href="./assets/css/style.css">
    <link rel="stylesheet"  href="./assets/themify-icons-font (1)/themify-icons/themify-icons.css">
  <style>
    /* Reset CSS */
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
html {
    scroll-behavior: smooth;
    font-family: Arial, Helvetica, sans-serif;
}
/*  PC >= 1024
    Tablet >=740  <1024
    Mobile <740    
*/

@media (min-width:1024px) {


}

@media (max-width:1024px) and (min-width:740px){


}

@media (max-width:740px)









/*
1 từ ngoài vào trong
2 từ trên xuống dưới
3 từ tổng quan đến chi tiết 
*/

/*
1. vị trí
2. kích thước  (width, height)
3. màu sắc 
4. kiểu dáng (kiểu chữ, hình tròn vv) 
*/

/* class dùng chung */
.clear {
    clear: both;
}
.text-center {
    text-align: center !important;
}
.text-white {
    color: #fff !important;
}
.mt-8 {
    margin-top: 8px !important;
}
.mt-16 {
    margin-top: 16px !important;
}

.row {
    margin-left: -8px;
    margin-right: -8px;
}
.col {
    float: left;
    padding-left:8px;
    padding-right:8px;
}

.col-third {
    width: 33.33333%;
}
.col-full {
    width: 100%;
}

.col-half {
    width: 50%;
}
.btn {
    text-decoration: none;
    background-color: #000;
    color: #fff;
    padding: 11px 16px;
    margin-bottom: 8px;
    display: inline-block;
}
.btn:hover {
    background-color: #ccc;
    color: #000;
    cursor: pointer;

}
.pull-right {
    float: right;
}

/* main */
#main {

}
#header {
    height: 46px;
    background-color: #000;
    position:fixed;
    top:0;
    left:0;
    right:0;
    z-index: 1;
}
#nav {
    display: inline-block;
}
#nav, .subnav {
    list-style-type: none;
}

#subnav > li > a {
    display: block;
}       


#nav li {
    display: inline-block;
    position: relative;
}

#nav > li > a {
    color: #fff;
    text-transform: uppercase;
}
#nav li a {
    
    text-decoration: none;
    line-height: 46px;
    padding: 0px 24px;
    display: block;
}
#nav li:hover .subnav {
    display: block;
}

#nav >li:hover >a,
#nav .subnav li:hover {
    color: #000;
    background-color: #ccc;
    display: inline-block;
}
#nav .subnav {
    display: none; 
    min-width: 160px;
    top: 100%;
    left: 0;
    position:absolute;
    background-color: #fff;
    box-shadow: 0 0 10px rgba(77, 37, 37, 0.3);
}
#nav .subnav a {
    color:#000;
    padding: 0 12px;
    line-height: 38px;   
}
#nav li a .nav-icon{
    font-size: 16px;
}
#header .search-icon{
    color: #fff;
    font-size: 24px;   
    line-height: 46px;
    padding: 0 21px ;
    
}
#header .search-b{
    float: right;
    cursor: pointer;
}
#header .search-b:hover{
    background-color: #f44336;
    
}



#slider {
    position: relative;
    padding-top: 50%;
    margin-top: 46px;
    background: url('./img/slider1.jpg') top center / cover no-repeat
}
#slider .text-content{
    position: absolute;
    bottom: 48px;
    color:#fff;
    left: 50%;
    transform: translateX(-50%);
    text-align: center;
    /* width : 100%; */
}

#slider .text-heading{
    font-weight: 500;
    padding: 25px;
    font-size: 24px;
}
#slider .text-description{
    font-size: 15px;

}

#content {
    height:1000px;
    
}
#content .content-section{
    
    
    margin-left: auto;
    margin-right: auto;
    padding: 64px 16px 112px;
    width: 100%;
}
#content .section-heading {
    margin: 10px 0;
    text-align: center;
    font-size: 30px;
    font-family: "Segoe UI",Arial,sans-serif;
    font-weight: 400;
    letter-spacing: 5px;
}    

#content .section-sub-heading {
    margin: 20px 0;
    opacity: 0.5;
    text-align: center;
    font-size: 15px;
   /* font-style:italic; chữ nghiêng */
}
#content .about-text {
    text-align: justify;
    margin: 15px 0 ;
    font-size: 15px;
    line-height: 1.4;
}

#content .member-list {
    margin-top: 48px;
}
#content .member-name {
    margin-top: 15px;

}
#content .member-img {
    width: 154px;
    margin-top: 15px;
    border-radius: 4px;
    
}
.tour-section {
    background-color: #000;
}

.tickets-list{
    margin-top: 40px;
    list-style: none;
}

.tickets-list li {
    font-size: 15px;
    color: #757575;
    background-color: #fff;
    border-bottom: 1px solid #ddd;
    padding: 11px 16px;
}



.tickets-list .sold-out {
    background-color: #f44336;
    padding: 3px 4px;
    margin-left: 16px;
    color: #fff;
}

.tickets-list .quantity {
    float: right;
    background-color: #000;
    color: #fff;
    width: 24px;
    height: 24px;
    text-align: center;
    border-radius: 50%;
    line-height: 24px;
    margin-top: -3px;
}
.place-list {
    margin-top: 32px;
    

}


.place-img:hover {
    opacity: 0.6;

}

.place-img {

    width: 100%;
    margin: 0px;
    display: block;
}

.place-body {
    background-color: #fff;
    color: #000;
    padding: 16px;
    font-size: 15px;
    width: 100%;
    

}

.place-heading {
    font-size: 15px;
    padding: 8px 0;
}

.place-time {
    padding: 12px 0;
    color: #757575;
}

.place-desc {
    padding: 12px 0;
    padding-bottom: 15px;
}


/* Contact-section*/

.contact-bgr{
    background-color: #fff;
    color: #000;
    margin-bottom: 48px;
}
.contact-content{
    margin-top: 48px;

}
.contact-info {
    font-size: 18px;
    line-height: 1.4;
    
}
.contact-info i[class*="ti-"] {
    width: 30px;
    display: inline-block;
}
.contact-form {
    font-size: 15px;
}

.contact-form .form-control {
    padding: 10px;
    border: 1px solid #ccc;
    width: 100%;
}
/* Map section */
.map-section img {
    width: 100%;
    padding-top: 80px;

}



#footer {
    padding: 64px 16px;
    text-align: center;
    
}








#footer .socials-list {
    font-size: 24px;

}
#footer .copyright {
    margin-top: 15px;
}

#footer .copyright a {
    color: rgba(0, 0, 0, 0.6);

}

#footer .copyright a:hover,
#footer .socials-list a {
    color: rgba(0, 0, 0, 0.4);
    text-decoration: none;
}

#footer .copyright a:hover,
#footer .socials-list a:hover {
    margin-top: 15px;
    color: rgba(0, 0, 0, 0.6);
}



.modal {
    position: fixed;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    background: rgba(0, 0, 0, 0.4);
    display:none;
    align-items: center;
    justify-content: center;
}

.modal.open{
   display: flex; 
}

.modal-container {
    background: #fff;
    width: 900px;
    max-width: calc(100% - 32px);
    min-height: 200px;
    position: relative;
    animation: modalFadeIn ease 0.5s;
}
.modal-close {
    position: absolute;
    right: 0;
    top: 0;
    color: #fff;
    padding: 12px;
    opacity: 0.8;
    cursor: pointer;
}

.modal-close:hover {
    opacity: 1;
}

 .modal-header {
    background: #009688;
    height: 130px;
    display:flex;
    align-items: center;
    justify-content: center;
    font-size: 30px;
    color: #fff;
    
   
}
.modal-heading-icon {
    margin-right: 16px;
}

.modal-body {
    padding: 16px;
}

.modal-label {
    display: block;
    font-size: 15px;
    margin-bottom: 12px;

}

.modal-input {
    border: 1px solid #ccc;
    width: 100%;
    padding: 10px;
    font-size: 15px;
    margin-bottom: 24px;
}
#buy-tickets {
    background: #009688;
    border:none;
    color: #fff;
    width: 100%;
    font-size: 15px;
    text-transform:uppercase ;
    padding: 18px;
    cursor: pointer;
}

#buy-tickets:hover {
    opacity: 0.8;

}

.modal-footer{
    padding: 16px;
    text-align: right;
}
.modal-footer a {
    color:#2196F3 ;
}

@keyframes modalFadeIn {
    from {
        opacity: 0;
        transform: translateY(-140px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}




   </style>
</head>
<body> 
    
    <div id="main">
        <div id="header">
            <!--Begin: Nav -->
            <ul id="nav">
                <li><a href="#">Home</a></li>
                <li><a href="#band">Band</a></li>
                <li><a href="#tour">Tour</a></li>
                <li><a href="#contact">Contact</a></li>
                <li>
                    <a href="">
                        More
                        <i class="nav-icon ti-angle-down" ></i>
                    </a>
                    <ul class="subnav">
                        <li style="display:block"><a href="#">Merchandise</a></li>
                        <li style="display: block;"><a href="#">Extras</a></li>
                        <li style="display: block;"><a href="#">Media</a></li>
                    </ul>
                </li>
            </ul>
        <!-- End: Nav -->

            <div class="search-b" >
                <i class="search-icon ti-search" ></i>
            </div>
        <!--Begin: Search button-->
            
        </div>
        






        <!--End: Search button-->

        <div id="slider">
            <div class="text-content">
                <h2 class="text-heading">New York</h2>
                <div class="text-description">The atmosphere in New York is lorem ipsum</div>
            </div>

        </div>

        <div id="content">
            <!--About section-->
            <div id="band" class="content-section">
            <h2 class="section-heading">THE BAND</h2>
           <p class="section-sub-heading" ><i>We love music</i></p> 
            <p class="about-text">
                We have created a fictional band website. Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
            </p>
            <div class="row member-list">
                <div class="col col-third text-center">
                <p class="member-name">Name</p>
                <img src="./assets/css/img/content1.jpg" alt="Name" class="member-img">
                </div>
                <div class="col col-third text-center">
                <p class="member-name">Name</p>
                <img src="./assets/css/img/content1.jpg" alt="Name" class="member-img">
                </div>
            
    
           
                <div class="col col-third text-center">
                <p class="member-name">Name</p>
                <img src="./assets/css/img/content1.jpg" alt="Name" class="member-img">
                </div>
                <div class="clear"></div>
            </div>

           
            

        </div>


            <!--Tour section-->
            <div class="tour-section">

                <div id="tour" class="content-section text-white">
                    <h2 class="section-heading">TOUR DATES</h2>
                   <p class="section-sub-heading" ><i>Remember to book your tickets!
        
                   </i></p> 
            <!--Tickets-->
                 <ul class="tickets-list">
                    <li>September <span class="sold-out">Sold out</span></li>
                    <li>October  <span class="sold-out">Sold out</span></li>
                    <li>November <span class="quantity">3</span></li>
                 </ul>
            <!--Place -->
                 <div class="row place-list">
                    <div class="col col-third">
                        <img src="./assets/css/img/newyork.jpg" alt="" class="place-img">
                        <div class="place-body">
                            <h3 class="place-heading">New York</h3>
                            <p class="place-time">Fri 27 Nov 2016</p>
                            <p class="place-desc">Praesent tincidunt sed tellus ut rutrum sed vitae justo.</p>
                            <button  class="btn js-buy-ticket">Buy Tickets</button>
                            <div class="clear"></div>
                        </div>
                       </div>
                       <div class="col col-third">
                        <img src="./assets/css/img/paris.jpg" alt="" class="place-img">
                        <div class="place-body">
                            <h3 class="place-heading">Paris</h3>
                            <p class="place-time">Sat 28 Nov 2016</p>
                            <p class="place-desc">Praesent tincidunt sed tellus ut rutrum sed vitae justo.</p>
                            <button  class="btn js-buy-ticket">Buy Tickets</button>
                        </div>
                       </div>
                       <div class="col col-third">
                        <img src="./assets/css/img/sanfran.jpg" alt="" class="place-img">
                        <div class="place-body">
                            <h3 class="place-heading">San Francisco</h3>
                            <p class="place-time">Sun 29 Nov 2016</p>
                            <p class="place-desc">Praesent tincidunt sed tellus ut rutrum sed vitae justo.</p>
                            <button  class="btn js-buy-ticket">Buy Tickets</button>
                        </div>
                       </div>
                       <div class="clear"></div>
                </div>
                
            </div>
                <!--Begin: Contact section-->
                <div id="contact" class="contact-bgr">
    
                    <div  class="content-section">
                        <h2 class="section-heading">CONTACT</h2>
                       <p class="section-sub-heading" >
                        <i>Fan? Drop a note! </i>
                    </p> 
                    
                
                <div class="row contact-content">
                    <div class="col col-half contact-info">
                        <p><i class="ti-location-pin"></i> Chicago, US</p> 
                        <p><i class="ti-mobile"></i> Phone: +00 151515</p>
                        <p><i class="ti-email"></i> Email: mail@mail.com</p>
                    </div>
                    
                    <div class="col col-half contact-form">
                        <form action="">
                            <div class="row"> 
                                <div class="col col-half">
                                    <input type="text" name="" placeholder="Name" required id="" class="form-control">
                                    
                                </div>
                                <div class="col col-half">
                                    <input type="email" name="" placeholder="Email" required id="" class="form-control">
                                </div>
                                <div class="clear"></div> 
                            </div>
                            <div class="row mt-8">
                                <div class="col col-full">
                                    <input type="text" name="" placeholder="Message" required id="" class="form-control">
                                    <!--<textarea name="" placeholder="Message" required id="" class="form-control"></textarea>    giúp cho người dùng có thể nhập nhiều dòng      -->
                                </div>
                            </div>
                            <input class="btn pull-right mt-16" type="submit" value="SEND">
                        </form>
                        <div class="clear"></div>
                        
                    </div>
                



                </div>
            </div>

            <!--End: Contact section-->
            <div class="map-bgr">

                <div class="map-section">
                    <img src="./assets/css/img/map.jpg" alt="Map">
                </div>
            </div>
            </div>

     </div>


        <div id="footer">
            <div class="socials-list">
                <a href="https://www.facebook.com/"><i class="ti-facebook"></i></a>
                <a href=""><i class="ti-instagram"></i></a>
                <a href=""><i class="ti-youtube"></i></a>
                <a href=""><i class="ti-pinterest"></i></a>
                <a href=""><i class="ti-twitter"></i></a>
                <a href=""><i class="ti-linkedin"></i></a>
            </div>
        <p class="copyright">Powered by <a href="">w3.css</a> </p>
        </div>
    </div>
    <div class="modal js-modal">
        <div class="modal-container js-modal-container">
            <div class="modal-close js-modal-close">
                <i class="ti-close"></i>
            </div>


            <header class="modal-header">
                <i class="modal-heading-icon ti-briefcase"></i>
                Tickets
            </header>
            <div class="moder-body">
                <label for=" quantity" class="modal-label">
                    <i class="ti-shopping-cart-full"></i>
                    Tickets, $15 per person
                </label>

                <input id="quantity" type="text" class="modal-input" placeholder="How many?">
                <label for="email" class="modal-label">
                    <i class="ti-user"></i>
                    Send to
                </label>

                <input id="email" type="email" class="modal-input" placeholder="Enter email...">

                <button id="buy-tickets">
                    Pay
                    <i class="ti-check"></i>
                </button>

            </div>
            <footer class="modal-footer">
                <p class="modal-help">Need <a href="https://www.youtube.com/" class="">help</a></p>
            </footer>


        </div>
    </div>
        <script>
            const buyBtns = document.querySelectorAll('.js-buy-ticket')
            const modal = document.querySelector('.js-modal')
            const modalClose = document.querySelector('.js-modal-close')
            const modalContainer = document.querySelector('.js-modal-container')
            // Ham hien thi modal mua ve ( them class open vao modal)
            function showBuyTickets() {
                modal.classList.add('open')
            }
            // Ham an modal mua ve (go bo class open cua modal)
            function hideBuyTickets() {
                modal.classList.remove('open')
            }
            // Lap qua tung the button va nghe hanh vi click 
            for (const buyBtn of buyBtns) {
                buyBtn.addEventListener('click',  showBuyTickets)
            }
                // Nghe hanh vi click vao button close
                modalClose.addEventListener('click', hideBuyTickets)


            modal.addEventListener('click', hideBuyTickets)

            modalContainer.addEventListener('click', function(event) {
                event.stopPropagation()
            })

        </script>
    
</body>
</html>
