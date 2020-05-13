<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <link rel="stylesheet" href="./css/animate.css" />
    <link rel="stylesheet" href="./css/style.css" />
    <title>Sougata Chanda | HOME</title>
  </head>
  <body>
    
    <div class="container navbar">
      <header>
        <div class="logo">
          <h1>Sougata Chanda</h1>
        </div>
        <nav>
          <ul>
            <li><a href="#about">About me</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#work">My work</a></li>
            <li><a href="#light" class="light">light</a></li>
          </ul>
        </nav>
      </header>
    </div>

    <div class="container main-info-section">
      <div class="text">
        <h1>
          Hi, I'm Sougata
        </h1>
        <p>WEB/HTML/CSS/PROGRAMMER/ANALYST</p>
        <a href="#contact">Contact Me</a>
      </div>
      <div class="profile-image">
        <img src="./img/profile-image.png" alt="">
      </div>
    </div>

    <div class="container about" id="about">
      <h1>About Me</h1>
      <div class="about-me-info">
      <p>I am a 1st year B.Tech Student studying Computer Science Engineering with specialization in Big Data Analytics under IBM at <a href="https://www.cuchd.in/">Chandigarh University</a>.</p>
      <p>I have a good knowledge in Web Designing,Programming and Database.</p>
      <p>I am good in Team Work along with good Time Management skill.</p> 
      </div>
      <img src="./img/dotted-shape.png" alt="">
    </div>

    <div class="container skills" id="skills">
      <h1>Skills</h1>
      <p class="skill-info"> Currently, I am learning various skills. The progress of my learning various skills are given below. I will always update my skill bar as soon as I complete or start learning new skill(s).</p>
     <div class="box">
      <div class="bar">
      <span class="name">Html</span>
      <div class="percent">
        <div class="progress" style="width: 98%;"></div>
      </div>
      <span class="value">98%</span>
    
    </div>
    <div class="bar">
      <span class="name">CSS</span>
      <div class="percent">
        <div class="progress" style="width: 80%;"></div>
      </div>
      <span class="value">80%</span>
    
    </div>
    <div class="bar">
      <span class="name">C++</span>
      <div class="percent">
        <div class="progress" style="width: 90%;"></div>
      </div>
      <span class="value">90%</span>
    
    </div>
    <div class="bar">
      <span class="name">MySQL</span>
      <div class="percent">
        <div class="progress" style="width: 100%;"></div>
      </div>
      <span class="value">100%</span>
     </div>
    </div>
    </div>

    <div class="container work" id="work">
     <h1>Work</h1>
     <div class="work-category">
      <button id="designing" class="active">Web designing</button>
      <button id="animation">Web animation</button>
      <button id="project">React Project</button>
     </div>
       <div class="category-designing showcategory">
         <a href=""><img src="./img/1.png" alt=""></a>
         <a href=""><img src="./img/2.png" alt=""></a>
         <a href=""><img src="./img/3.png" alt=""></a>
        <a href=""><img src="./img/3.png" alt=""></a>
       </div>
      <div class="category-designing hidecategory">
        <a href=""><img src="./img/1.png" alt=""></a>
      </div>
      <div class="category-designing hidecategory">
        <a href=""><img src="./img/1.png" alt=""></a>
        <a href=""><img src="./img/2.png" alt=""></a>
      </div>
    </div> 

    <div class="container contact" id="contact">
     <h1>Contact Me</h1>
     <form action="">
       <input type="text" name="name" placeholder="Full Name">
       <input type="email" placeholder="Email">
       <input type="email" placeholder="abc@gmail.com" disabled>
       <textarea name="message" id="" cols="30" rows="10" placeholder="Message"></textarea>
       <input type="submit">     
      </form>
    </div>

    <footer>
      <hr>
      <p>2020 Copyrights. All Rights are Reserved </p>
    </footer>

    <script src="./js/ScrollMagic.min.js"></script>
    <script src="./js/animation.gsap.min.js"></script>
    <script src="./js/TimelineLite.min.js"></script>
    <script src="./js/TweenMax.min.js"></script>
    <script src="./js/CSSPlugin.min.js"></script>
    <script src="./js/script.js"></script>
  </body>
</html>
