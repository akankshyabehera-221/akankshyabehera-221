
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Website</title>
    <link rel="stylesheet" href="style3.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
        integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>

<body>

    <div class="hero">
        <nav>
            <h2 class="logo">Portfolio</h2>
            <ul>
                <li><a href="#" class="active">Home</a></li>
                <li><a href="#about">about</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#project">Project</a></li>
                <li><a href="#contact">Contact</a></li>

            </ul>
            <a href="#" class="btn">Download Resume</a>
        </nav>

        <section class="home" id="home">
            <div class="content">
                <h4>Hello, my name is</h4>
                <h1>Akankshya Behera</h1>
                <h3>I am a web Developer.</h3>
                <p>Web Designer with experience for over 1 year.expertise is to create and website design, Frontend.
                    designs and many more. </p>
            </div>
    </div>
    </section>
    <section class="about" id="about">
        <div class="photo7">
            <!-- <img src="photo7.jpg"> -->
            <div class="about-text">
                <h2>About Me</h2>
                <h5>Developer <span>& Designer</span></h5>
                <p>I am a Front-end web developer . I can provide clean code and pixel perfect design . I a also make
                    the website more & more intractive with web animation. I can provide clean code and pixel perfect
                    design .I also make the website more & more intractive with web animation . A responsive design
                    makes your website accesible to all users , regardless of their device.</p>
                <button type="button">Let's Talk</button>
            </div>

        </div>
    </section>

    <div class="skills" id="skills">
        <div class="title">
            <h2>Skills</h2>
        </div>
        <div class="box">
            <div class="card">
                <i class="fa-brands fa-html5"></i>
                <h5>HTML</h5>
                <div class="pra">
                    <p>covering basic to advanced concepts including HTML5, CSS, and responsive web design. Developed
                        practical skills through hands-on projects .</p>
                    <p style="text-align: center;">
                        <a class="button" href="#">Read More</a>
                    </p>
                </div>
            </div>


            <div class="card">
                <i class="fa-brands fa-css3"></i>
                <h5>CSS</h5>
                <div class="pra">
                    <p>focusing on advanced styling techniques, CSS frameworks, and best practices for modern web
                        design. Applied knowledge in real-world projects.</p>
                    <p style="text-align: center;">
                        <a class="button" href="#">Read More</a>
                    </p>
                </div>
            </div>


            <div class="card">
                <i class="fa-brands fa-js"></i>
                <h5>JAVASCRIPT</h5>
                <div class="pra">
                    <p>Completed a comprehensive course in JavaScript,event handling.Developed proficiency in front-end
                        and back-end JavaScript development.</p>
                    <p style="text-align: center;">
                        <a class="button" href="#">Read More</a>
                    </p>
                </div>
            </div>
        </div>
    </div>
    </div>


    <section class="Resume" id="project">
        <h2 class="heading">Latest <span>Project</span></h2>
        <div class="Resume-container">
            <div class="Resume-box">
                <img src="p1.webp.jpg" alt="">
                <div class="Resume-layer">
                    <h4>Web Design</h4>
                    <p>Check out 10 Best Design's updates for the top web design & development companies.</p>
                    <a href="#"><i class='bx bx-link-external'></i></a>
                </div>
            </div>

            <div class="Resume-box">
                <img src="p2.jpeg.jpg" alt="">
                <div class="Resume-layer">
                    <h4>Web Design</h4>
                    <p>Check out 10 Best Design's updates for the top web design & development companies.</p>
                    <a href="#"><i class='bx bx-link-external'></i></a>

                </div>

            </div>


            <div class="Resume-box">
                <img src="p3.jpeg.avif" alt="">
                <div class="Resume-layer">
                    <h4>Web Design</h4>
                    <p>Check out 10 Best Design's updates for the top web design & development companies.</p>
                    <a href="#"><i class='bx bx-link-external'></i></a>

                </div>

            </div>


        </div>
    </section>
    <section class="contact">

        <div class="contact-form" id="contact">
            <h1>Contact<span>Us</span></h1>
            <p>I am available for freelance work. Connect with me via phone:000261728 or email: admin@hello.com.</p>
            <form action="">
                <input type="" placeholder="Your Name" required>
                <input type="email" name="email" id="email" placeholder="E-mail" required>
                <input type="" placeholder="Write a subject" required>
                <textarea name="" id="" cols="30" rows="10" placeholder="Your Message" required>
    </textarea>
                <input type="Submit" name="" value="Submit" class="btn">
            </form>
        </div>

    </section>



    <footer>
        <p>Akankshya Behera</p>
        <p>For more HTML,CSS and JAVASCRIPT Knowldege -Please click on the link below :</p>
        <div class="social-media">
            <a href="#"><i class="fa-brands fa-facebook"></i></a>
            <a href="#"><i class="fa-brands fa-instagram"></i></a>
            <a href="#"><i class="fa-brands fa-linkedin"></i></a>
            <a href="#"><i class="fa-brands fa-twitter"></i></a>
        </div>
        <p class="end">CopyRight By Akankshya Behera</p>


    </footer>

</body>


</body>

</html>


#css
*{
    margin: 0;
    padding: 0;
    font-family: 'Josefin Sans', sans-serif;
    box-sizing: border-box;
}
 

.hero {
    height: 100vh;
    width: 100%;
    background-image: url("background.webp.jpg") ;
    background-position: center;
}

nav {
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-top: 45px;
    padding-right: 8%;

}
.logo{
    color: white;
    font-size: 35px;
    letter-spacing: 1px;
    cursor: pointer;


}
span {
    color: #5206f6;
}

nav ul li {
    list-style-type: none;
    display: inline-block;
    padding: 10px 25px;

}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
    text-transform: capitalize ;


}

nav ul li a:hover {
    color: #1100f9 ;
    transition: .4s;
}
 
.btn {
    background-color: #3305be;
    color: white;
    text-decoration: none;
    border: 2px solid transparent;
    font-weight: bold;
    padding: 10px 25px;
    border-radius: 30px;
    transition: transform .4s;
}

.btn:hover{
    transform: scale(1.2);
}

.content{
    position: absolute;
    top: 50%;
    left: 8%;
    transform: translateY(-50%);
    color:#fff;
}

h1{
    color: white;
    margin: 20px 0px 20px;
    font-size: 75px;
}

h3{
    color: white;
    margin-bottom: 50px;
    font-size: 25px;
}
h4{
    color: #fcfc;
    letter-spacing: 2px;
    font-size: 20px;
}
.newslatter form {
    width: 380px;
    max-width: 100%;
    position: relative;
}

.newslatter form input:first-child {
    display: inline-block;
    width: 100%;
    padding:14px 130px 14px 15px;
    border:2px solid #1504d3;
    outline: none;
    border-radius: 30px;
}
.newslatter form input:last-child{
    position: absolute;
    display: inline-block;
    outline: none;
    border: none;
    padding: 10px 30px;
    border-radius: 30px;
    background-color: #4006e0;
    color: white;
    box-shadow: 0px 0px 5px #000 , 0px opx 15px #858585;
    top:6px;
    right:6px; 

}

.about{
    width: 100%;
    padding: 100px 0px;
    background-color: #191919;
}

.about img {
    height: auto;
    width: 430px;
}
.about-text {
    width: 550px;
}

.photo7 {
    width: 1130px;
    max-width: 95%;
    margin: 0  auto;
    display: flex;
    align-items: center;
    justify-content: space-around;
}

.about-text h2{
    color:white;
    font-size: 75px;
    text-transform: capitalize;
    margin-bottom: 20px;
}

.about-text h5{
    color: white;
    letter-spacing: 2px;
    font-size: 22px;
    margin-bottom: 25px;
    text-transform: capitalize;
}

.about-text p{
    color: #fcfc ;
    letter-spacing: 1px;
    line-height: 28px;
    font-size: 18px;
    margin-bottom: 45px;
}


button{
    background-color: #2805d9;
    color: white;
    text-decoration: none;
    border: 2px solid transparent;
    font-weight: bold;
    padding: 13px 30px;
    border-radius: 30px;
    transition: .4s;
}
button:hover{
    background-color: transparent;
    border: 2px solid #3006d9;
    cursor:pointer;
}

.skills{
    background: #101010;
    width: 100%;
    padding: 100px 0px;
}

.title  h2 {
    color: white;
    font-size: 75px;
    width: 1130px;
    margin: 30px auto;
    text-align: center;
}

.box{
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 400px;
}

.card{
    height: 365px;
    width: 335px;
    padding: 20px 35px;
    background: #191919;
    border-radius: 20px;
    margin: 15px;
    position: relative;
    overflow: hidden;
    text-align: center;
}

.card i{
    font-size: 50px;
    display: block;
    text-align: center;
    margin: 25px 0px;
    color: #2304ed;

}

h5{
    color: white;
    font-size: 23px;
    margin-bottom: 15px;
}
.pra p {
    color: #fcfc;
    font-size: 16px;
    line-height: 27px;
    margin-bottom: 25px;
     
}
.card .button{
    background-color: #3f07d9;
    color: white;
    text-decoration: none;
    border: 2px solid transparent;
    font-weight: bold;
    padding: 9px 22px;
    border-radius: 30px;
    transition: .4s;
}

.card .button:hover{
    background-color: transparent;
    border: 2px solid #0c05d9;
    cursor: pointer;
}


.Resume {
    background: var(--second-bg-color);

}

.Resume h2 {
    margin-bottom: 4rem;

}
   
.Resume-container {
    display: grid;
    grid-template-columns: repeat(3 ,1fr);
    align-items: center;
    gap: 2.5rem;
}

 .Resume-container  .Resume-box {
    position: relative;
    border-radius: 2rem;
    box-shadow: 0 0 1rem var(--bg-color);
    overflow: hidden;
    display: flex;

 }

 .Resume-box img {
     width: 100%;
     transition: .5s ease;

 }

 .Resume-box:hover img {
    transform: scale(1.1);
 }

 .Resume-box .Resume-layer {
      position: absolute;
      bottom: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: linear-gradient(rgba(0,0,0,.1), var(--main-color));
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      text-align:center;
      padding: 0 4rem;
      transform: translateY(100%);
      transition: .5s ease;

 }
 .Resume-box:hover .Resume-layer {
    transform: translateY(0);
 }


 .Resume-layer h4 {
    font-size: 3rem;

 }

 

 .Resume-layer p {
    font-size: 1.6rem;
    margin: .3rem 0 1rem;

 }
 
 .Resume-layer a {
    display: inline-flex;
    justify-content: center;
    align-items: center;
    width: 5rem;
    height: 5rem;
    background: var(--text-color);
    border-radius: 50%;
 }
  

 .Resume-layer a i {
    font-size: 2rem;
    color: var(--second-bg-color);

 }

section{
    padding: 40px 15%;
}
.contact{
   background: #101010 ;
   height: 100%;
   width: 100%;
   min-height:100vh;
   display: grid;
   grid-template-columns: repeat(2,2fr);
   align-items: center;
   grid-gap: 6rem;
}

.contact-form h1{
    font-size: 80px;
    color:#fff;
    margin-bottom: 20px;
}

span{
    color:#3e00f9;
}
.contact-form p{
    color: #c6c9d8bf;
    letter-spacing: 1px;
    line-height: 26px;
    font-size: 1.1rem;
    margin-bottom: 3.8rem;
}

.contact-form form{
    position: relative;


}
.contact-form form input,
form textarea{
    width:100%;
    padding: 17px;
    border: none;
    outline: #191919;
    color:#858585;
    font-size: 1.1rem;
    margin-bottom: 0.7rem;
    border-radius: 10px;
}

.contact-form textarea{
    resize: none;
    height: 200px;
}
.contact-form form .btn{ 
    display: inline-block;
    background: #000000;
    font-size: 1.1rem;
    letter-spacing: 1px;
    text-transform: uppercase;
    font-family: 600;
    border: 2px solid transparent;
    border-radius: 10px;
    width: 220px;
    transition: ease .20s;
    cursor: pointer;

}
.contact-form form .btn:hover{
    border: 2px solid #0a04c4;
    background: transparent;
    transform: scale(1.1);

}

@media (max-width:1570px){
    section{
        padding:80px 3%;
        transition: .2s;
    }
    .contact-form h1{
        font-size: 60px;
    }
    .contact-form p{
        margin-bottom: 3rem;
    }
}

@media (max-width:1090px){
    .contact{
        grid-gap: 2rem;
        transition: .3s;
    }
}

@media (max-width:1000px){
    .contact{
        grid-template-columns: 1fr;
    }
    .contact-form{
        order: 2;
    }
}


footer {
    position: relative;
    width:100%;
    height:400px;
    display: flex;
    background: #101010;
    display :flex;
    flex-direction:column;
    align-items: center;
    justify-content: center;
    
}


/*.social a {
    display: inline-flex;
    justify-content: center;
    align-items: center;
    width: 4rem;
    height: 4rem;
    background: transparent;
    border: .2rem solid var(--main-color);
    border-radius: 50%;
    font-size: 2rem;
    color: var(--main-color);
    margin: 3rem 1.5rem 3rem 0;
    transition: .5s ease;
}
.social a:hover {
    background: var(--main-color);
    color: var(--second-bg-color);
    box-shadow: 0 0 1rem var(--main-color);
}*/



footer p:nth-child(1) {
    font-size: 30px;
    color: white;
    margin-bottom: 20px;
    font-weight: bold;
}

footer p:nth-child(2){
    color: white;
    font-size: 17px;
    width: 500px;
    text-align: center;
    line-height: 26px;
}
.social-media{
    display:flex;
}
.social-media a{
    width: 45px;
    height: 45px;
    display: flex;
    align-items: center;
    justify-content: center;
    background: #1b05e4;
    border-radius: 50%;
    margin: 22px 10px;
    color: white;
    text-decoration: none;
    font-size: 20px;

}
.social-media a:hover{
    transform: scale(1.3);
    transition: .3s ;

}
.end{

position: absolute;
color: #2500f9;
bottom: 35px;
font-size: 14px;
}






<!---
akankshyabehera-221/akankshyabehera-221 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
