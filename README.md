<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="style.css">
    <style>
        * {
    margin: 0%;
    padding: 0%;
    font-family: 'Poppins',sans-serif;
    color: rgb(255, 255, 255);
}
body{
    background-color: black;
}
html{
    scroll-behavior: smooth;
}
#container{
    height: 100vh;
    width: 100%;
    background-image: url("https://tse1.mm.bing.net/th?id=OIP.s6qkxOqsGKB_7JnvbKujWAHaE2&pid=Api&P=0&h=180");
    background-repeat: no-repeat;
    background-size:100% 100vh;
    background-position:center;
    background-attachment: fixed;
}
#header{
    padding: 10px 10%;
}
.logo{
    width: 250px;
    height: 60px;
    padding-left: 10px;
 }
 nav{
    display: flex;
    justify-content: space-between;
 }
 nav ul li{
    display: inline-block;
    list-style: none;
    margin: 15px;
    align-items: center;
 }
 nav ul li a{
    text-decoration: none;
    position: relative;
 }
 nav ul li a::after{
    content: '';
    width: 0;
    height: 3px;
    background-color:#FACB0F;
    position: absolute;
    left: 0;
    bottom: -6px;
    border-radius: 2px;
    box-shadow: 2.5px 2.5px 4.5px #f5cf34;
    transition: width 0.3s;
}
nav ul li a:hover::after{
    width:100%;
}
.text {
    font-size: 30px;
    margin-top: 140px;
    align-items: center;
}
.text p{
    font-size: 20px;
    font-weight: lighter;
    font-family: Calibri,sans-serif,;
}
/*........................................about................................*/
#about{
    padding-top: 30px;
    background-color: rgb(0, 0, 0);
}
.empty{
    display: flex;
    justify-content: space-around;
}
.ig{
    width: 400px;
    height: 400px
}
.about-img{
    padding-top: 30px;
    margin: 50px;
}
.about-text{
    padding-top: 40.5px;
    height: 550px;
    width: 600px;
    padding-right: 100px;
}
.sub-titles{
    display: flex;
    justify-content: space-between;
    margin: 30px 0 30px;
}
.subtitle1{
    margin-right: 50px;
    font-size: 18px;
    font-weight:500px ;
    cursor: pointer;
    position: relative;
}
.subtitle1::after{
    content: '';
    width: 100%;
    height: 3px;
    background-color:#FACB0F;
    position: absolute;
    left: 0;
    bottom: -6px;
    border-radius: 2px;
    box-shadow: 2.5px 2.5px 4.5px #f5cf34;  
}
div ul li{
    list-style:square;
}
/*...........................................services..............................*/
#services{
    padding: 30px 0;
}
.container{
    margin: 50px;
}
.services-types{
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
    grid-gap:40px;
}
.services-types div{
    background-color: #262626;
    padding: 40px;
    font-size: 20px;
    font-weight: 200;
    border-radius: 10px;
    transition: width 0.5s, height 0.5s;
}
.services-types div:hover{
    box-shadow: 10px 10px 20px #262626;
    transform:translateY(-10px);
}
.services-types div p{
    margin: 20px 0;
    font-size:15px;
    letter-spacing: 1px;
}
/*................................... contact.............................*/
.contact-detail{
    height: 400px;
    width: 90%;
    padding: 20px;
    display: flex;
   justify-content: space-around;
   position: absolute;
}
.contactus{
    height: 300px;
    width: 350px;
}
.img{
    padding-top: 30px;
    padding-left: 60px;
    height: 200px;
    width: 400px;
    filter:drop-shadow(10px 5px 5px#f5cf34 )
}
.icons{
    padding-left: 40px;
}
div .c-m{
    padding-bottom: 30px;
    border-radius: 5px;
}



    </style>
</head>
<body>
    <div id="container">
        <div id="header">
        <nav>
            <img class="logo" src="C:\Users\damer\OneDrive\Pictures\logo.jpg"/>
            <ul>
                <li><a href="#Home">Home</a></li>
                <li><a href="#container1">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
        <div class="text">
            <p>Web development</p>
            <h1>Hi, I'm<span style="color:#f5cf34; text-shadow: 2px 2px 10px  #f5cf34 ;"> Likhitha</span><br><span>Damerla From India</span></h1>
        </div>
    </div>
        </div>
    <div id="container1">
        <div id="about">
            <div class="empty">
            <div class="about-img">
                <img src="C:\Users\damer\OneDrive\Desktop\intern\portfolio\circle.png" class="ig">
            </div>
            <div class="about-text">
                <h2 style="font-size: 35px; text-shadow: 2px 1.5px 4px #ffffff"><span style="color: #f5cf34;text-shadow: 2px 1.5px 4px #f5cf34">A</span>bout Me</h2>
                <br>
                <p style="word-spacing: 2px;">I am Likhitha, currently pursuing a BTech in tha stream of Data Science at St.Mary's women's Engineering College. I am passionate about learning new things and constantly expanding my knowledge and skills. <br>I am eager to learn and enhance my skills further. My goal is to continuously develop myself and contribute effectively to the tech community.</p>
                <div class="sub-titles">
                    <p class="subtitle1">Skills<br></p>
                    </div>
                    <div><ul>
                        <li>wed developement</li><br>
                        <li>UI/UX</li><br>
                        <li>Good at Communication</li>
                    </ul></div>
                    <div class="sub-titles">
                        <p class="subtitle1">Education<br></p></div>
                        <div><ul>
                            <li>2021-2025 - B.Tech, St.Marys Womens Enginnering college (CGPA-8.034)</li><br>
                            <li>2019-2021 - Intermediate(MPC), SVL college (CGPA-8.79)</li><br>
                            <li>2018-2019 - SSC, Loyola public school (CGPA-9.7)</li>
                        </ul></div>
                </div>
            </div>
            </div>
        </div>
    </div>
    <div id="services">
        <div class="container">
        <h1 class="subtopic" style=" font-size: 35px; padding-bottom: 30px; color: #f5cf34; text-shadow: 2px 1.5px 4px #f5cf34 ;"> My Services</h1>
        <div class="services-types">
        <div>
        <h2 class="hlo">Web <span style="color: #f5cf34;">Design</span></h2><br>
        <p>As a web designer, I specialize in creating basic web designs that are clean, user-friendly, and visually appealing. I focus on layout, color schemes, and typography to ensure a cohesive and professional look. My designs prioritize simplicity and functionality to provide an enjoyable browsing experience for visitors. Let's work together to bring your basic web design ideas to life!</p>
        <br>
        <a href="#" style="color: #000000; display: inline-block;text-shadow: 2px 2px 4px #f5cf34; font-size: 17px; ">Learn more</a>
        </div>
        <div>
        <h2 class="hlo"><span style="color: #f5cf34;display: inline-block;">UI/UX</span> Design</h2>
        <br>
        <p>As a UI and UX designer, I focus on creating intuitive layouts, easy navigation, and engaging interactions to enhance user satisfaction. By combining visual appeal with user-centered design principles, I strive to deliver seamless and enjoyable digital experiences. Let's collaborate to develop basic designs that not only look great but also provide a smooth and delightful user journey!</p>
        <a href="#"  style="color: black; text-shadow: 2px 2px 4px #f5cf34; font-size: 17px;">Learn more</a>
        </div>
        </div>
 </div>
<br><br><br><br><br><br><br><br><br>
 <div id="contact">
    <div class="empty">
    <div class="contact-detail">
    <div class="contactus">
        <h1 style="color:#f5cf34; text-shadow: 2px 2px 10px  #f5cf34;">Contact Me</h1><br><br>
        <div class="c-m" ><br><br>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<i class="fa-solid fa-envelope" style="color: #f5cf34; font-size: 20px;"></i> &nbsp;&nbsp;&nbsp;&nbsp;likhithadamerla07@gmail.com</p><br><br>
            <p >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<i class="fa-solid fa-phone" style="color: #f5cf34; font-size: 20px;"></i>&nbsp;&nbsp;&nbsp;&nbsp;********55</p>
            <br><br><br>
        <div class="icons">
            &nbsp;&nbsp;&nbsp;&nbsp;
            <a href="#"><i class="fa-brands fa-square-instagram" style="color: #f5cf34; font-size: 25px;"></i></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <a href="#"><i class="fa-solid fa-inbox"style="color: #f5cf34; font-size: 25px;"></i></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <a href="#"><i class="fa-brands fa-linkedin"style="color: #f5cf34; font-size: 25px;"></i></a>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            <a href="#"> <i class="fa-brands fa-github"style="color: #f5cf34; font-size: 25px;"></i></a>
        </div></div>
    </div>
    <div class="img">
         <img  style="height: 300px; width: 450px; border-radius: 100%;" src="C:\Users\damer\OneDrive\Desktop\intern\portfolio\contact.jpg"/>
    </div>
    </div>
    </div>
 </div>
    </div>
</body>
</html>
