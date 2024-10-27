<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Edu+TAS+Beginner&family=Montserrat&family=Noto+Sans:ital@0;1&family=Open+Sans&display=swap');
      body{
          margin:0;
          background-color: black;
          color: white;
      }
      .navbar{
          display: flex;
          flex-direction: row;
          justify-content: space-between;
          background-color: black;
      }
      .navbar-left{
          padding-left: 5px;  
      }
      .navbar-right{
          display: flex;
          align-items: center;
          font-family: 'Open Sans', sans-serif;
          
      }
      .a-element{
       padding: 10px;
       margin:10px;
       font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
       font-size: 15px;
       font-weight: bold;
      }
      .a-element:hover {
          color: #f1e9e9; /* Text color on hover */
          background-color: #007bff; /* Background color on hover */
          border-radius: 4px; /* Rounded corners for the background */
      }
      .home{
          display: flex;
          flex-direction: row;
          justify-content: space-between;
          align-items: center;
          height: 85vh; 
      }
      .home-left{
          width: 50vw;
          padding-right: 20px;
          text-align: right;
          font-family: 'Edu TAS Beginner', cursive;
          font-weight:lighter;
      }
      .t-h1{
          font-family: 'Montserrat', sans-serif;
          font-style: italic;
      }
      .home-right{
        width: 50vw;
    
      }
      .About{
      text-align: center;
      padding-top: 100px;

      }
      .about-info{
          font-family: 'Montserrat', sans-serif;
          font-style: italic;
      }
      
      .Services{
          padding: 20px;
          text-align: center;
          padding-top: 150px;
      }
      .Ser-h1{
          padding: 20px;
          font-family: 'Noto Sans', sans-serif;
          letter-spacing: 2px;
          color: rgb(16, 232, 16);
          font-size: 30px;
          font-style: italic;
      }
      .Services-sub-cont{
          display: flex;
          flex-direction: row;
      }
      .Services-card{
          border: 2px rgb(40, 205, 54) solid;
          margin: 20px;
          padding: 20px;
          width: 400px;
      
      }
      .Services-card:hover {
          background-color: #aac3d9; /* Change to a light color on hover */
          box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2); /* Add shadow on hover */
      }
      .sc-h1{
          font-family: 'Montserrat', sans-serif;
          font-size: 25px;
          font-style: italic;
      }
      .sc-p{
          font-family: 'Open Sans', sans-serif;
          font-size: 15px;
      
      }
      .contact{
          text-align: center;
          padding-top: 100px;
      }
      .contact-info{
          font-family: 'Montserrat', sans-serif;
          font-size: 20px;
          
      }
      .social-icon-img{
          height: 50px;
          padding: 10px;
      }
    </style>
</head>
<body>
    <div class="navbar">
        <div class="navbar-left">
            <h2>RAMBO_EDITZ</h2>
        </div>
        <div class="navbar-right">
            <a class="a-element" href="#home">Home</a>
            <a class="a-element" href="#About">About</a>
            <a class="a-element" href="#Services">Services</a>
            <a class="a-element" href="#contact">Contact</a>
        </div>
    </div>
    <div class="home" id="home">
        <div class="home-left">
         <h1 class="t-h1">Rammohan Chowdary</h1>
         <p>I'm rammohan pursuing my B.Tech 4th year in KL University.I came for agriculture background and also like farming so much.my goal is to settle as a good personality in the society.</p>
        </div>
        <div class="home-right">
          <img src="https://res.cloudinary.com/dnfyvshwt/image/upload/v1696593724/Rams_image_qdmjzc.jpg" alt="my-logo">
        </div>
    </div>
    <div class="About" id="About">
        <h1 class="Ser-h1">ABOUT US</h1>
        <div class="about-info">
            <p>I am a dedicated web designer and editor with a passion for creating visually appealing and user-friendly websites. My work involves a blend of artistic design and technical expertise, as I strive to craft digital spaces that not only look stunning but also function seamlessly. I specialize in translating my clients' visions into reality, ensuring that their websites reflect their brand identity and resonate with their target audience. With a keen eye for detail and a commitment to staying up-to-date with the latest industry trends, I take pride in delivering websites that not only meet but exceed expectations.</p>
        </div>
    </div>
    <div class="Services" id="Services">
        <h1 class="Ser-h1">SERVICES WE OFFER</h1>
        <div class="Services-sub-cont">
            <div class="Services-card">
                <h1 class="sc-h1">Web Designing</h1>
                <p class="sc-p">I'm Web developer.I'm a frontend developer as per now for developing a good looking website.Learning backend.</p>
            </div>
            <div class="Services-card">
                <h1 class="sc-h1">Photo Editing</h1>
                <p class="sc-p">I'm Photo editor.I'm good in editing photos and poster and also I'm Excellent in political editing like CDP's and posters.</p>
            </div>
            <div class="Services-card">
                <h1 class="sc-h1">Video Editing</h1>
                <p class="sc-p">I'm Video editor.I'm good in video editing sync with beats and the effects.Excellent in political videos</p>
            </div>
        </div>
    </div>
    <div class="contact" id="contact">
        <h1 class="Ser-h1">CONTACT US</h1>
        <div class="contact-info">
            <p>Rammohan Chowdary Kuchipudi</p>
            <p>+91 6281692525</p>
            <p>rammohankuchipudi.143@gmail.com</p>
        </div>
        <div class="social-icons">
            <div class="social-icon">
            <a href="https://www.instagram.com/_rammohan_chowdary__/">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a5/Instagram_icon.png/600px-Instagram_icon.png" class="social-icon-img">
            </a>
            <a href="https://www.facebook.com/rammohanchowdary.kuchipudi/">
                <img src="https://static-00.iconduck.com/assets.00/facebook-icon-512x512-seb542ju.png" class="social-icon-img">
            </a>
            <a href="https://www.youtube.com/@Rammohan_5769">
                <img src="https://static-00.iconduck.com/assets.00/youtube-icon-2048x2048-879wd8sv.png" class="social-icon-img">
            </a>
            </div>
        </div>
 
    </div>
</body>
</html>
