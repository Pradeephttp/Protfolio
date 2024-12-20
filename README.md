# Protfolio
Protfolio is responsive website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/ab60b183fc.js" crossorigin="anonymous"></script>
</head>
<body>
<div id="header">
    <div class="container">
        <nav>
            <img src="images/logo.png" class="logo">
            <ul>
                <li><a herf="#">Home</a></li>
                <li><a herf="#">About</a></li>
                <li><a herf="#">Services</a></li> 
                <li><a herf="#">Portfolio</a></li>
                <li><a herf="#">Contact</a></li>
                <i class="fa-solid fa-circle-xmark"></i>
            </ul>
            <i class="fa-solid fa-bars"></i>
        </nav>
        <div class="header-text"></div>
        <p>WEB Developer</p>
        <h1>Hi,I'm <span>Pradeep</span><br>Mourya from India</h1>
    </div>
</div>
<!---------------about---------->
<div id="about">
    <div class="container">
        <div class="row">
            <div class="about-col-1">
                <img src="images/user.png">
            </div>
            <div class="about-col-2">
                <h1 class="sub-title">About Me</h1>
                <p>Goal-oriented professional looking for a position as a Web Designer with significant web design skills and the ability to develop attractive <br>web pages using a variety of software and tools to assist the firm in achieving a tech-enabled efficiency.
                </p>
               <div class="tab-title">
                    <p class="tab-link active-link" onclick="opentab('skills')">Skills</p>
                    <p class="tab-link" onclick="opentab('experience')">Experience</p>
                    <p class="tab-link" onclick="opentab('education')">Education</p>

                </div>
                 <div class="tab-contents active-tab" id="skills">
                    <ul>
                        <li><span>Web Developer</span><br>Front-End/Back-End</li>
                        <li><span>App Developer</span><br>On Android studio</li>
                        <li><span>Web application Developer</span><br>In Java and Spingboot</li>
                    </ul>
                </div>
                <div class="tab-contents" id="experience">
                    <ul>
                        <li><span>2024</span><br>Learn Android studio on youtube/ Complete My first Project</li>
                    </ul>
                </div>
                <div class="tab-contents" id="education">
                    <ul>
                        <li><span>2023</span><br>Web Developer training at Ukti IT Classes</li>
                        <li><span>2023</span><br>Learn Android studio on youtube</li>
                        <li><span>2024</span><br>I pursue My Digree from S.K.C Digree Collage</li>
                    </ul>
                </div>
            </div>

        </div>

    </div>
</div>
<!--------------services-------------->
<div id="services">
    <div class="container">
        <h1 class="sub-title">My Services</h1>
        <div class="services-list">
        <div>
            <i class="fa-solid fa-code"></i>
            <h2>Web development</h2>
            <p>I want to introduce myself and my skills in<br>a way that is clear, concise,and catches<br>the reader's attention.I am a web developer<br> with years of experience in creating and managing<br> websites. My skills include coding in HTML, CSS, and JavaScript,<br>as well as working with CMSs like WordPress and Drupal.</p>
               <a href="#">Learn more</a>
        </div>
        <div>
            </i><i class="fa-brands fa-app-store"></i>
            <h2>App development</h2>
            <p>I want to introduce myself and my skills in<br>a way that is clear, concise,and catches<br>the reader's attention.I am a web developer<br> with years of experience in creating and managing<br> websites. My skills include coding in HTML, CSS, and JavaScript,<br>as well as working with CMSs like WordPress and Drupal.</p>
               <a href="#">Learn more</a>
        </div>
        <div>
            <i class="fa-brands fa-java"></i>
            <h2>Web app development</h2>
            <p>I want to introduce myself and my skills in<br>a way that is clear, concise,and catches<br>the reader's attention.I am a web developer<br> with years of experience in creating and managing<br> websites. My skills include coding in HTML, CSS, and JavaScript,<br>as well as working with CMSs like WordPress and Drupal.</p>
               <a href="#">Learn more</a>
        </div>
    </div>
</div>
<!----------protfolio----------->

<div id="protfolio">
    <div class="container">
        <h1 class="sub-title">My Work</h1>
        <div class="work-list">
            <div class="work">
                <img src="images/work-1.png">
                <div class="layer">
                    <h3>Social Media App</h3>
                    <p>The app connects you the talented people around the world.
                        Download it from play store.</p>
                        <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="images/work-2.png">
                <div class="layer">
                    <h3>Music App</h3>
                    <p>The app connects you the talented people around the world.
                        Download it from play store.</p>
                        <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
            <div class="work">
                <img src="images/work-3.png">
                <div class="layer">
                    <h3>Online Shopping App</h3>
                    <p>The app connects you the talented people around the world.
                        Download it from play store.</p>
                        <a href="#"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
        </div>
        <a href="#" class="btn">See more</a>
    </div>
</div>

<!-----------contact----------->

<div class="contact">
    <div class="container">
        <div class="row">
            <div class="contact-left">
                <h1 class="sub-title">Contact Me</h1>
                <p> <i class="fa-solid fa-paper-plane"></i>mouryap053@gmail.com</p>
                <p><i class="fa-solid fa-phone"></i>9172620880</p>
                <div class="social-icons">
                    <a href=""><i class="fa-brands fa-facebook"></i></a>
                    <a href=""><i class="fa-brands fa-github"></i></a>
                    <a href=""><i class="fa-brands fa-instagram"></i></a>
                    <a href=""><i class="fa-brands fa-linkedin"></i></a>
                </div>
                <a href="images/my-cv.pdf" download class="btn btn2">Download CV</a>
            </div>
            <div class="contact-right">
                <form>
                    <input type="text" name="Name" placeholder="Your Name" required>
                    <input type="text" name="email" placeholder="Your@gmail.com"required>
                    <textarea name="Message" rows="6" placeholder="Your Message"></textarea>
                    <button type="submit" class="btn btn2">Submit</button>
                </form>
            </div>
        </div>
    </div>
    <div class="copyright">
        <p>Copyright © Pradeep.Made with <i class="fa-solid fa-heart"></i> by Easy Tutorials</p>
    </div> 
</div>
<script>

    var tablinks = document.getElementsByClassName("tab-links");
    var tabcontents = document.getElementsByClassName("tab-contents");

    function opentab(tabname){
        for(tablink of tablinks){
            tablink.classList.remove("active-link");
        }
        for(tabcontent of tabcontents){
            tabcontent.classList.remove("active-tab");
        }
        event.currentTarget.classList.add("active-link");
        document.getElementById(tabname).classList.add("active-tab");
    }
</script>


    
</body>
</html>
