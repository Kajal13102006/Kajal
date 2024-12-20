
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="zomato.css">
    <link rel="stylesheet" href="main-body.css">
    <link rel="stylesheet" href="collection.css">
    <link rel="stylesheet" href="location.css">
    <link rel="stylesheet" href="app-section.css">
    <link rel="stylesheet" href="footer.css">
<style>
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&family=Raleway&family=Ubuntu:ital,wght@0,300;0,400;0,500;0,700;1,300;1,400;1,500;1,700&display=swap');
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Raleway",sans-serif;

}

header{
    background-image: url("https://b.zmtcdn.com/web_assets/81f3ff974d82520780078ba1cfbd453a1583259680.png");
    height: 60vh;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center center;
}

nav{
   /* background-color: red;*/
   height: 72px;
   display: flex;
   justify-content: space-around;
   align-items: center;
}

#getApp span{
    color: #fff;
    font-size: 14px;
    font-weight: 500;
}
#menu ul{
    display: flex;
    gap: 50px;
    color: #fff;
    font-size: 18px;
}

#logoTagSearch{
    /*border:5px solid aqua; */
    height: calc(60vh-72px);
    padding-top: 20px;
    display: flex;
    flex-direction: column;
    /*justify-content: center;*/
    align-items: center;
}

#logoTagSearch #logo img{
    width: 300px;
}

#logoTagSearch #tagLine{
    margin-top: 30px;
}

#logoTagSearch #tagLine h1{
    color: #fff;
    font-size: 36px;
    font-weight: normal;
}

#searchContainer{
    background-color: #fff;
    margin-top: 30px;
    padding: 15px 25px;
    width: 50%;
    border-radius: 10px;
    display: flex;
}
#searchContainer #location{
    display: flex;
    align-items: center;
    border-right: 2px solid #cfcfcf;
    padding-right: 10px;
}
#searchContainer input{
    border: none;
}

#searchContainer #restraunt{
    margin-left: 20px;
}
#searchContainer #restraunt span{
    color: #c9c8c8;
}@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100..900;1,100..900&family=Raleway&family=Ubuntu:ital,wght@0,300;0,400;0,500;0,700;1,300;1,400;1,500;1,700&display=swap');
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Raleway",sans-serif;

}

header{
    background-image: url("https://b.zmtcdn.com/web_assets/81f3ff974d82520780078ba1cfbd453a1583259680.png");
    height: 60vh;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center center;
}

nav{
   /* background-color: red;*/
   height: 72px;
   display: flex;
   justify-content: space-around;
   align-items: center;
}

#getApp span{
    color: #fff;
    font-size: 14px;
    font-weight: 500;
}
#menu ul{
    display: flex;
    gap: 50px;
    color: #fff;
    font-size: 18px;
}

#logoTagSearch{
    /*border:5px solid aqua; */
    height: calc(60vh-72px);
    padding-top: 20px;
    display: flex;
    flex-direction: column;
    /*justify-content: center;*/
    align-items: center;
}

#logoTagSearch #logo img{
    width: 300px;
}

#logoTagSearch #tagLine{
    margin-top: 30px;
}

#logoTagSearch #tagLine h1{
    color: #fff;
    font-size: 36px;
    font-weight: normal;
}

#searchContainer{
    background-color: #fff;
    margin-top: 30px;
    padding: 15px 25px;
    width: 50%;
    border-radius: 10px;
    display: flex;
}
#searchContainer #location{
    display: flex;
    align-items: center;
    border-right: 2px solid #cfcfcf;
    padding-right: 10px;
}
#searchContainer input{
    border: none;
}

#searchContainer #restraunt{
    margin-left: 20px;
}
#searchContainer #restraunt span{
    color: #c9c8c8;
}
</style>

</head>
<body>

    <header>
        <nav>
            <div id="getApp">
                <i class="fa-solid fa-mobile-screen-button" style="color: hsl(0, 0%, 100%); margin-right: 5px;"></i>
                <span>Get the App</span>
            </div>

            <div id="menu">
                <ul type="none">
                <li>Investor Relation</li>
                <li>Add restraunt</li>
                <li>Log in</li>
                <li>Sign up</li>
                </ul>
            </div>
        </nav>

        <div id="logoTagSearch">

            <div id="logo">
                <img src="https://b.zmtcdn.com/web_assets/8313a97515fcb0447d2d77c276532a511583262271.png" alt="">
            </div>

            <div id="tagLine">
                <h1>Discover the best food & drinks in <span>Ahmedabad</span></h1>
            </div>

             <div id="searchContainer">
                <div id="location">
                    <i class="fa-solid fa-location-dot fa-lg" style="color: #ff7e8b; margin-right: 10px;"></i>

                    <input type="text" placeholder="Ahmedabad">

                    <i class="fa-solid fa-caret-down" style="color: #4f4f4f;"></i>
                </div>

                <div id="restraunt">
                    <i class="fa-solid fa-magnifying-glass" style="color: #6e6e6e; margin-right: 10px;"></i>
                  <span>Search for Restraunt, cuisine or dish</span>
                </div>
             </div>
        </div>
    </header>


    <section id="main-body">

        <div id="services">

            <div id="options">
                <div id="image">
                    <img src="https://b.zmtcdn.com/webFrontend/e5b8785c257af2a7f354f1addaf37e4e1647364814.jpeg?output-format=webp&fit=around|402:360&crop=402:360;*,*" alt="">
                </div>

                <div id="info">
                    <h2>Order Online</h2>
                    <p>Stay home and order to your doorstep</p>
                </div>
            </div>

            <div id="options">
                <div id="image">
                    <img src="https://b.zmtcdn.com/webFrontend/d026b357feb0d63c997549f6398da8cc1647364915.jpeg?output-format=webp&fit=around|402:360&crop=402:360;*,*" alt="">
                </div>

                <div id="info">
                    <h2>Dining</h2>
                    <p>View the city's favourite dining venue</p>
                </div>
            </div>

            <div id="options">
                <div id="image">
                    <img src="https://b.zmtcdn.com/data/o2_assets/371de657644f1b5818fcb5d83387c8c91722851940.png?output-format=webp&fit=around|402:360&crop=402:360;*,*" alt="">
                </div>

                <div id="info">
                    <h2>Live Events</h2>
                    <p>Discover India's best events and concerts</p>
                </div>
            </div>

        </div>
    </section>

    <div id="collection">
        <h2>Collections</h2>

        <div id="col-description">
            <p>Explore curated lists of top restaurants, cafes, pubs, and bars in Ahmedabad,based on trends</p>
            <a href="">All Collections in Ahmedabad <i class="fa-solid fa-caret-right" style="color: #ff7e8b;"></i></a>
        </div>

        <div id="col-list">
            <div id="col-options">
                <div id="col-image">
                    <img alt="Christmas Special Restaurants" src="https://b.zmtcdn.com/data/collections/dfbc5317500ed8778ae6e04969e229fb_1734093348.png?output-format=webp">
                </div>

                <div id="list-overlay">
                    <div id="overlay-info">
                        <p>Christmas special Restaurants</p>
                        <a href="">11 Places <i class="fa-solid fa-caret-right"></i></a>
                    </div>
                </div>
            </div>

            <div id="col-options">
                <div id="col-image">
                    <img src="https://b.zmtcdn.com/data/collections/6922d49fb675d0490edb652abf5ca45f_1727171275.png?output-format=webp">
                </div>

                <div id="list-overlay">
                    <div id="overlay-info">
                        <p>Newly Opened Restaurants</p>
                        <a href="">26 Places <i class="fa-solid fa-caret-right"></i></a>
                    </div>
                </div>
            </div>

            <div id="col-options">
                <div id="col-image">
                    <img alt="Top Trending Spots" src="https://b.zmtcdn.com/data/collections/684397cd092de6a98862220e8cc40aca_1724236728.png?output-format=webp">
                </div>

                <div id="list-overlay">
                    <div id="overlay-info">
                        <p>Top Trending Spots</p>
                        <a href="">19 Places <i class="fa-solid fa-caret-right"></i></a>
                    </div>
                </div>
            </div>

            <div id="col-options">
                <div id="col-image">
                    <img alt="Gujarati Thalis" src="https://b.zmtcdn.com/data/collections/1541bcd444e2623a01fbc751465fd23a_1675252064.jpg?output-format=webp">
                </div>

                <div id="list-overlay">
                    <div id="overlay-info">
                        <p>Gujarati Thalis</p>
                        <a href="">18 Places <i class="fa-solid fa-caret-right"></i></a>
                    </div>
                </div>
            </div>

        </div>
    </div>


    <div id="locations">

        <div id="location-title">
            <p>Popular localities in and around <span>Ahmedabad</span></p>
        </div>

        <div id="place-container">

            <div id="places"> 
                <div id="place-name">
                  <h5>Bodakdev</h5>
                  <p>477 places</p>
                </div>
                <i class="fa-solid fa-chevron-right" style="color: #1c1c1c;"></i>
            </div>

            <div id="places"> 
                <div id="place-name">
                  <h5>Navrangpura</h5>
                  <p>407 places</p>
                </div>
                <i class="fa-solid fa-chevron-right" style="color: #1c1c1c;"></i>
            </div>

            <div id="places"> 
                <div id="place-name">
                  <h5>Prahladnagar</h5>
                  <p>249 places</p>
                </div>
                <i class="fa-solid fa-chevron-right" style="color: #1c1c1c;"></i>
            </div>
            
            <div id="places"> 
                <div id="place-name">
                  <h5>Satellite</h5>
                  <p>418 places</p>
                </div>
                <i class="fa-solid fa-chevron-right" style="color: #1c1c1c;"></i>
            </div>

            <div id="places"> 
                <div id="place-name">
                  <h5>Vastrapur</h5>
                  <p>300 places</p>
                </div>
                <i class="fa-solid fa-chevron-right" style="color: #1c1c1c;"></i>
            </div>

            <div id="places"> 
                <div id="place-name">
                  <h5>C G Road</h5>
                  <p>112 places</p>
                </div>
                <i class="fa-solid fa-chevron-right" style="color: #1c1c1c;"></i>
            </div>

            <div id="places"> 
                <div id="place-name">
                  <h5>Gurukul</h5>
                  <p>123 places</p>
                </div>
                <i class="fa-solid fa-chevron-right" style="color: #1c1c1c;"></i>
            </div>

            <div id="places"> 
                <div id="place-name">
                  <h5>Thaltej</h5>
                  <p>456 places</p>
                </div>
                <i class="fa-solid fa-chevron-right" style="color: #1c1c1c;"></i>
            </div>

            <div id="see-more">
                <p>see more</p>
                <i class="fa-solid fa-chevron-down" style="color: #1c1c1c;"></i>
            </div>  
        </div>

    </div>

    <section id="app-section">

        <div id="app-container">

            <div id="app-image">
                <img alt="get-zomato-app" src="https://b.zmtcdn.com/data/o2_assets/ce5bc038a8a2d4f8f24465c8826182af1726501431.png">
            </div>

            <div id="app-info">
                <div id="app-title">
                    <h2>Get the Zomato App</h2>
                    <p>We will send you a link, open it on your phone to download the app</p>
                </div>

                <div id="app-options">
                    <div id="option1">
                        <input type="radio" name="option" id="email" checked>
                        <label for="email">Email</label>
                    </div>
                    <div id="option2">
                        <input type="radio" name="option" id="phone">
                        <label for="phone">Phone</label>
                    </div>
                </div>

                <div id="email-input-container">
                    <input type="email" name="" id="email-input" placeholder="Email">
                    <button>Share App Link</button>
                </div>

                <div id="store">
                    <p>Download app from</p>
                    <div id="store-image">
                        <img alt="image" src="https://b.zmtcdn.com/data/webuikit/23e930757c3df49840c482a8638bf5c31556001144.png">
                        <img alt="image" src="https://b.zmtcdn.com/data/webuikit/9f0c85a5e33adb783fa0aef667075f9e1556003622.png">
                    </div>
                </div>
            </div>

        </div>
    </section>

    <footer>
        <div id="footer-container">

            <div id="footer-top">
                <div id="footer-logo">
                    <img src="https://b.zmtcdn.com/web_assets/b40b97e677bc7b2ca77c58c61db266fe1603954218.png?fit=around|198:42&amp;crop=198:42;*,*" alt="Zomato logo">
                </div>

                <div id="dropdown-container">
                    <div class="dropdown-item">
                        <img width="20px" src="india flag.jfif" >
                        <span>India</span>
                        <i class="fa-solid fa-chevron-down" style="color: #1c1c1c;"></i>
                    </div>

                    <div class="dropdown-item">
                        <i class="fa-solid fa-globe" style="color: #000000;"></i>
                        <span>English</span>
                        <i class="fa-solid fa-chevron-down" style="color: #1c1c1c;"></i>
                    </div>
                </div>
            </div>

            <div id="footer-middle">
                <div class="footer-links">
                    <h6>About Zomato</h6>
                    <ul>
                        <li>Who we are</li>
                        <li>Blog</li>
                        <li>Work with us</li>
                        <li>Investor Relations</li>
                        <li>Report Fraud</li>
                        <li>Press Kit</li>
                        <li>Contact Us</li>
                    </ul>
                </div>

                <div class="footer-links">
                    <h6>Zomaverse</h6>
                    <ul>
                        <li>Zomato</li>
                        <li>Blinkit</li>
                        <li>District</li>
                        <li>Feeding India</li>
                        <li>Hyperpure</li>
                        <li>Zomato Live</li>
                        <li>Zomaland</li>
                        <li>Weather Union</li>
                    </ul>
                </div>

                <div class="footer-links">
                    <h6>For Restaurants</h6>
                    <ul>
                        <li>Partner with Us</li>
                        <li>Apps for you</li>
                    </ul>
                </div>

                <div class="footer-links">
                    <h6>Learn More</h6>
                    <ul>
                        <li>Privacy</li>
                        <li>Security</li>
                        <li>Terms</li>
                    </ul>
                </div>

                <div id="social-links" class="footer links">
                    <h6>Social Links</h6>
                    <div id="social-icons">

                        <i class="fa-brands fa-linkedin" style="color: #000000;"></i>
                        <i class="fa-brands fa-square-instagram" style="color: #000000;"></i>
                        <i class="fa-brands fa-square-x-twitter" style="color: #000000;"></i>
                        <i class="fa-brands fa-youtube" style="color: #000000;"></i>
                        <i class="fa-brands fa-facebook" style="color: #000000;"></i>
                    </div>

                    <div id="download-app">
                        <img alt="image" src="https://b.zmtcdn.com/data/webuikit/23e930757c3df49840c482a8638bf5c31556001144.png">
                        <img alt="image" src="https://b.zmtcdn.com/data/webuikit/9f0c85a5e33adb783fa0aef667075f9e1556003622.png">
                    </div>

                </div>

            </div>

            <hr>
            <div id="footer-end">
                <p>By continuing past this page, you agree to our Terms of Service, Cookie Policy, Privacy Policy and Content Policies. All trademarks are properties of their respective owners. 2008-2024 © Zomato™ Ltd. All rights reserved</p>
            </div>
        </div>
    </footer>
    
</body>
</html>
