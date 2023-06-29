<!DOCTYPE html>
<html>
<head>
  <title>Portfolio</title>
  <style>
   
      
        body, html {
            
  background-image: url('img/apple-gd4c6bb507_1280.jpg');
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
  background-position: center;


      margin: 50px;
      padding: 0;
      font-family: Arial, sans-serif;
      background-color: #F44336;
    
    }
    
    header {
      background-color: #FFF;
      padding: 20px;
      text-align: center;
    }
    
    footer {
      background-color: #FFF;
      padding: 20px;
      text-align: center;
    }
    
    nav {
      background-color: #FF5252;
      padding: 10px;
      text-align: center;
    }
    
    nav a {
      color: #FFF;
      text-decoration: none;
      padding: 5px 10px;
    }
    
    section {
      padding: 20px;
      color: #110f0f;
      text-align: center;
      border-color: aliceblue;
      box-shadow: #FFF;
      box-sizing: content-bo;
    }
    
    .portfolio-img {
      width: 300px;
      height: 300px;
      margin: 0 auto;
      display: block;
      border-radius: 50%;
      background-color: #c71111;
    }
  </style>
</head>
<body>
 
  <header>
    <h1>Portfolio of Mark Nkohla</h1>
  </header>
  
  <nav>
    <a href="#">Home</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

</div>
  <section>
    <h2>Welcome to my Portfolio</h2>
    <img class="portfolio-img" src="img/Mark Nkohla .jpg" alt="Portfolio Picture">
  </section>
   
  <section id="about">
    <h2>About</h2>
    <p>Mark Nkohla is a seasoned professional with a diverse range of experiences and a passion for technology, design, and music. 
        With a strong background in computer systems, he has gained extensive knowledge in web design and the effective utilization of cutting-edge marketing tools.
         Mark has honed his skills through hands-on experience, working with various organizations and contributing to the digital growth of businesses.
         <br><br>
        Additionally, Mark has demonstrated his adaptability and work ethic through his experience in plant-based nurseries. 
        His time spent in this field provided him with a deep understanding of sustainable practices and horticulture,
         enriching his skill set with knowledge of environmental conservation and the cultivation of plant-based ecosystems.
        <br><br>
        Furthermore, Mark has also showcased his dedication and strong work ethic in the retail sector, having worked at Woolworths. 
        His experience in this dynamic environment allowed him to develop exceptional interpersonal and customer service skills.
         His ability to collaborate effectively within a team and deliver outstanding results to meet customer needs has been instrumental in his success.
        <br><br>
        Beyond his professional pursuits, Mark is a passionate music producer. 
        His love for music drives him to continuously explore new avenues of creativity, constantly refining his skills and techniques.
         Mark's hard work and dedication shine through in his music, and he applies the same level of commitment and attention to detail in all his endeavors.
        <br><br>
        Overall, Mark Nkohla is a multifaceted individual with extensive computer experience, expertise in web design and marketing tools, and a passion for music production. 
        His diverse background and strong work ethic make him a valuable asset in any field he chooses to pursue.</p>
  
    </section>


  
  <section id="contact">
    <h2>Contact</h2>
    <p>.</p>
  </section>
  
  <footer>
    &copy; 2023 Your Name
  </footer>
  
  <script>
    // JavaScript for responsiveness
    const navLinks = document.querySelectorAll("nav a");

    navLinks.forEach(link => {
      link.addEventListener("click", smoothScroll);
    });

    function smoothScroll(event) {
      event.preventDefault();
      const targetId = this.getAttribute("href");
      const targetElement = document.querySelector(targetId);

      window.scrollTo({
        top: targetElement.offsetTop,
        behavior: "smooth"
      });
    }
  </script>
</body>
</html>
