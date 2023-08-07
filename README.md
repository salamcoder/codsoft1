<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio Website</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"/>
    <script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.11/typed.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/waypoints/4.0.1/jquery.waypoints.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/owl.carousel.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css"/>

</head>
<body>
    <div class="scroll-up-btn">
        <i class="fas fa-angle-up"></i>
    </div>
    <div class="icon">
        <h2 class="logo"></h2>
    </div>
    <nav class="navbar">
        <div class="max-width">
            <div class="logo"><a href="#"><span>My Portfolio</span></a></div>
            <ul class="menu">
                <li><a href="#home" class="menu-btn">Home</a></li>
                <li><a href="#about" class="menu-btn">About</a></li>
                <li><a href="#services" class="menu-btn">Education</a></li>
                <li><a href="#skills" class="menu-btn">Skills</a></li>
                <li><a href="#contact" class="menu-btn">Contact</a></li>
            </ul>
            <div class="menu-btn">
                <i class="fas fa-bars"></i>
            </div>
        </div>
    </nav>

    <!-- home -->
    <section class="home" id="home">
        <div class="max-width">
            <div class="home-content">
                <div class="text-1">Hello, I am </div>
                <div class="text-2">salam</div>
                <div class="text-3">And I'm a <span class="typing"></span></div>
                <a href="mailto:khanmdsalam96@gmail.com">Hire me</a>
            </div>
        </div>
    </section>

    <!-- about me -->
    <section class="about" id="about">
        <div class="max-width">
            <h2 class="title">About me</h2>
            <div class="about-content">
                <div class="column left">
                    <img src="images/profile.jpg" alt="profile-image">
                </div>
                <div class="column right">
                    <div class="text">I am Md Salam Khan  </div>
                    <p>I am an Engineering Student. Currently I pursuing my B.Tech in Electronics & Communication from Aliah University Kolkata with an aggregate 8.1 CGPA. I am from Kolkata. I completed my school education from Khalsa English High School Kolkata. I am looking for a job in Web Develeopment and Full Stack Development. Currently, I am doing a remote
                        Internship in Web Development and Designing from Oasis Infobyte Company. I have done certification in Python Programming(IITK), Web Development, C basics
                        etc. You can have a look at my resume.
                    </p>
                    <a href="Salam-Khan-Resume.pdf" target="_blank">My Resume</a>
                </div>
            </div>
        </div>
    </section>

    <!-- education -->
    <section class="services" id="services">
        <div class="max-width">
            <h2 class="title">My Education</h2>
            <div class="serv-content">
                <div class="card">
                    <div class="box">
                        <i class="fas fa-pen"></i>
                        <div class="text">SSC </div>
                            <ul style="list-style-type:none">
                                <li>Year:   2016-17</li>
                                <li>Board:  WB Board</li>
                                <li>School: Khalsa Englishg High School I/C Kolkata</li>
                                <li>Marks:  84%</li>
                            </ul>
                    </div>
                </div>
                <div class="card">
                    <div class="box">
                        <i class="fas fa-book"></i>
                        <div class="text">HSC</div>
                        <ul style="list-style-type:none">
                            <li>Year:   2018-19</li>
                            <li>Board:  WB Board</li>
                            <li>School: Khalsa English High School I/C Kolkata</li>
                            <li>Marks:  78.40%</li>
                        </ul>
                    </div>
                </div>
                <div class="card">
                    <div class="box">
                        <i class="fas fa-laptop"></i>
                        <div class="text">Under Graduate</div>
                        <ul style="list-style-type:none">
                            <li>Year:   2023-Present</li>
                            <li>University: AKTU</li>
                            <li>College:   Aliah University Kolkata</li>
                            <li>Marks:  8.1/10 CGPA</li>
                        </ul>
                    </div>
                </div>
               </div>
            </div>
        </div>
    </section>

    <!-- technical skills -->
    <section class="skills" id="skills">
        <div class="max-width">
            <h2 class="title">Technical skills</h2>
            <div class="skills-content">
                <div class="column left">
                    <div class="text">My Skills & experiences.</div>
                    <p>This is the summary of Hard Skills. I know HTML, CSS, JavaScript, Programming in C,
                        Core Java, DBMS, etc. I am currently doing an Internship in Web Develeopment & Designing
                        from Oasis Infobyte Company.
                    </p>
                    <a href="#">Read more</a>
                </div>
                <div class="column right">
                    <div class="bars">
                        <div class="info">
                            <span>HTML</span>
                            <span>Intermediate</span>
                        </div>
                        <div class="line html"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>CSS</span>
                            <span>Intermediate</span>
                        </div>
                        <div class="line css"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>JavaScript</span>
                            <span>Beginner</span>
                        </div>
                        <div class="line js"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>Programming in C</span>
                            <span>Beginner</span>
                        </div>
                        <div class="line c"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>Core Java</span>
                            <span>Beginner</span>
                        </div>
                        <div class="line cj"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>DBMS</span>
                            <span>Intermediate</span>
                        </div>
                        <div class="line dbms"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>

     <!-- soft skills -->
    <section class="skills" id="skills">
        <div class="max-width">
            <h2 class="title">Soft Skills</h2>
            <div class="skills-content">
                <div class="column left">
                    <div class="text">My Soft Skills</div>
                    <p>Team Work, Good Communication, Collaboration, Hardworking, Leadership, Team Builder. These are some
                        of my soft skills.
                    </p>
                    <a href="#">Read more</a>
                </div>
                <div class="column right">
                    <div class="bars">
                        <div class="info">
                            <span>Team Work</span>
                            <span>Intermediate</span>
                        </div>
                        <div class="line tw"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>Good Communication</span>
                            <span>Beginner</span>
                        </div>
                        <div class="line gc"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>Collaboration</span>
                            <span>Beginner</span>
                        </div>
                        <div class="line cl"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>Hardworking</span>
                            <span>Advanced</span>
                        </div>
                        <div class="line h"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>Leadership</span>
                            <span>Intermediate</span>
                        </div>
                        <div class="line l"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>Team Builder</span>
                            <span>Intermediate</span>
                        </div>
                        <div class="line tb"></div>
                </div>
            </div>
        </div>
    </section>


    <!-- contact section start -->
    <section class="contact" id="contact">
        <div class="max-width">
            <h2 class="title">Contact me</h2>
            <div class="contact-content">
                <div class="column left">
                    <p>To get in touch with me: </p>
                    <div class="icons">
                        <div class="row">
                            <i class="fas fa-user"></i>
                            <div class="info">
                                <div class="head">Name</div>
                                <div class="sub-title">Md Salam Khan</div>
                            </div>
                        </div>
                        <div class="row">
                            <i class="fas fa-map-marker-alt"></i>
                            <div class="info">
                                <div class="head">Address</div>
                                <div class="sub-title">11/1/H/3,M.M ALI ROAD</div>
                            </div>
                        </div>

                        <div class="row">
                            <i class="fas fa-envelope"></i>
                            <div class="info">
                                <div class="head">Email</div>
                                <div class="sub-title">khanmdsalam96@gmail.com</div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="column right">
                    <div class="text">Message me</div>
                    <form action="#">
                        <div class="fields">
                            <div class="field name">
                                <input type="text" placeholder="Name" required>
                            </div>
                            <div class="field email">
                                <input type="email" placeholder="Email" required>
                            </div>
                        </div>
                        <div class="field">
                            <input type="text" placeholder="Subject" required>
                        </div>
                        <div class="field textarea">
                            <textarea cols="30" rows="10" placeholder="Message.." required></textarea>
                        </div>
                        <div class="button-area">
                            <button type="submit">Send message</button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- footer section start -->
    <footer>
        <p><b>© 2022-2023 Md Salam Khan</b></p>
        <div class="social">
            <a href="https://www.facebook.com/profile.php?id=100012786284930&mibextid=ZbWKwL" target="_blank">
                <i class="fa fa-facebook-f">&emsp;</i>
            </a>
            <a href="https://www.instagram.com/official_hemant_rajpoot85/" target="_blank">
                <i class="fa fa-instagram">&emsp;</i>
            </a>
            <a href="https://www.linkedin.com/in/hemantkumar980/" target="_blank">
                <i class="fa fa-linkedin-square">&emsp;</i>
            </a>
            <a href="https://github.com/hemantkumar980" target="_blank">
                <i class="fa fa-github"></i>
            </a>




        </div>
    </footer>


    <script src="script.js"></script>
</body>
</html>
