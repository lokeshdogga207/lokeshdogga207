

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="Stylesheet" href="portfolio.css">
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar">
        <div class="max-width">
            <div class="logo">
                <a href="#">portfolio.</a>
            </div>
            <ul class="menu">
                <li><a href="#home" class="menu-btn">Home</a></li>
                <li><a href="#about" class="menu-btn">About</a></li>
                <li><a href="#skill" class="menu-btn">Skills</a></li>
                <li><a href="#contact" class="menu-btn">Contact</a></li>
            </ul>
            <!-- <span class="menu-btn">
                <i class="fas fa-bars"></i>
            </span> -->
        </div>
    </nav>

    <!-- Home -->

    <section class="home" id="home">
       <div class="max-width">
          <div class="home-content">
              <div class="text-1">Hello,I am</div>
              <div class="text-2">Lokesh</div>
              <div class="text-3">And I am a <span class="change_text"></span></div>
              <a href="#">Hire Me</a>
          </div>
       </div>
    </section> 
<br>
    <!-- About--> 

    <section class="about" id="about">
      <div class="max-width">
            <h2 class="title">About Me</h2>
         <div class="about-content">
             <div class="column left">
                 <img src="water.jpg" alt="" width="200px" height="200px">
             </div>
             <div class="column right">
                <div class="text">I am D.Lokesh and i am a<span> student</span></div>
                <p>I have learnt front end development(HTML,CSS,JS) from the growth ninja,in growth ninja they explained the whole front-end into three divisions.It is very interesting to learn coding for web development in growth ninja.So, i am very interested to learn the front-end course.</p>
                <a href="#">Download CV</a>
             </div> 
         </div>
        </div>
    </section> 
    
    <!-- services -->

    <section class="services" id="services">
        <div class="max-width">
            <h2 class="title">My services</h2>
            <div class="service-content">
                <div class="card">
                    <div class="box">
                        <i class="fas fa-code"></i>
                        <div class="text">Website designer</div>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni, adipisci.</p>
                    </div>
                </div>

                <div class="card">
                    <div class="box">
                        <i class="fas fa-video"></i>
                        <div class="text">video editor</div>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni, adipisci.</p>
                    </div>
                </div>

                <div class="card">
                    <div class="box">
                        <i class="fas fa-pen-nib"></i>
                        <div class="text">content writer</div>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni, adipisci.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- SKills -->

    <section class="skill" id="skill">
        <div class="max-width">
          <h2 class="title"> My Skills </h2>
            <div class="skill-content">
                <div class="column left">
                    <div class="text">My creative skills and experience</div>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias, officiis, excepturi vero exercitationem voluptatum nihil asperiores ipsa sit fugiat a natus omnis, eius quo porro illo in fuga doloribus beatae Lorem ipsum dolor sit amet, consectetur adipisicing elit. Similique, vitae Lorem ipsum dolor sit, amet consectetur adipisicing elit. Culpa accusantium asperiores maiores magni qui temporibus, quo illo aut minus. A odio doloremque repellat reprehenderit enim architecto esse dolores maiores placeat.</p>
                    <a href="#">Read more</a>
                </div>
                <div class="column right">
                    <div class="bars">
                        <div class="info">
                            <span>HTML</span>
                            <span>90%</span>
                        </div>
                        <div class="line html"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>CSS</span>
                            <span>80%</span>
                        </div>
                        <div class="line css"></div>
                    </div>
                    <div class="bars">
                        <div class="info">
                            <span>Java Script</span>
                            <span>70%</span>
                        </div>
                        <div class="line javascript"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>

     <!-- contact -->

    <section class="contact" id="contact">
        <div class="max-width">
            <h2 class="title">Contact Me</h2>
            <div class="contact-content">
                <div class="column left">
                    <div class="text">Get In Touch</div>
                    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Distinctio neque in nihil, odio porro at optio accusantium quos? Quidem nemo quae asperiores voluptatibus architecto, aspernatur ea quibusdam dolore quas porro!</p>
                    <div class="icons">
                        <div class="row">
                            <i class="fas fa-user"></i>
                            <div class="info">
                                <div class="head">Name</div>
                                <div class="sub-title">Lokesh</div>
                            </div>
                        </div>  

                        <div class="row">
                            <i class="fas fa-map-marker-alt"></i>
                            <div class="info">
                                <div class="head">Address</div>
                                <div class="sub-title">New Delhi</div>
                            </div>
                        </div>

                        <div class="row">
                            <i class="fas fa-envelop"></i>
                            <div class="info">
                                <div class="head">Email</div>
                                <div class="sub-title">abc@gmail.com</div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="column right">
                    <div class="text">Message Me</div>
                    <form action="#">
                        <div class="fields">
                           <div class="field name">
                            <input type="text" placeholder="Name" required>
                           </div>

                           <div class="field email">
                            <input type="email" placeholder="Email" required>
                           </div>
                        
                        </div>
                        <div>
                           <div class="field ">
                            <input type="field" placeholder="Subject" required>
                           </div>

                           <div class="field textarea">
                            <textarea cols="30" rows="10" placeholder="Describe Project" required></textarea>
                           </div>

                           <div class="button">
                            <button type="submit">send message</button>
                           </div>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- footer -->
 <footer>
    <span>Created By  <a href="#">Lokesh</a> | <span class="far fa-copyright"></span>2023 All rights reserved</span>
 </footer>
    <script src="portfolio.js"></script>
</body>
</html>
