<!-- =================
  WRITE YOUR HTML HERE

You only need to write the HTML that goes inside the <body> tag. To add things to the <head>, click the ⚙️ 
   ===================
-->

<!--- All the tests are red! You have to make them green. 

Q How do you make the tests pass?
A Meet the requirements!

Make the first test pass by adding a <header> </header>-->
<!DOCTYPE html>
<html lang="en">
  <head> 
    <meta charset="utf-8">
    <title>Personal  Home Page</title>
    <style>
  body {
  margin: 0;
  height: 100%;
      font-family: 'Raleway', sans-serif;
      background-color (#f2f2f2, #cbe8f3);
}
header {
      background-color: #0275f4;
      color: white;
      padding: 2px;
      text-align: center;
      border-bottom: 4px solid #025aa5;
    }
nav {
      background-color: #025aa5;
      padding: 1rem;
      text-align: center;
    }

 nav a {
      color: white;
      margin: 10px;
      text-decoration: none;
      font-weight: bold;
    }
 main {
      padding: 2px;
      max-width:auto;
      margin: auto;
    }
section {
      margin-bottom: 2px;
    }
#aboutme ,#image, #skills, #video,#education, #contact  {
      margin-top:15px;
      background: white;
      border-radius: 12px;
      padding: 15px;
      box-shadow: 0 4px 8px rgba(0,0,0,1);
    }
.img {
      width: 150px;
      height: 150px;
      display: block;
      margin: 0 auto 1px;
  border: 4px solid #0275d8;}
  
  
  footer {
    background-color: #0275f4;
      color: white;
      padding: 2px;
      text-align: right;
      border-bottom: 4px solid #025aa5;
      margin-top:15px;}</style>
  </head>
  <body>
    <header>
      <h1>Fadi Dandoush</h1>
      <p class="c-site-header">Personal Home Page</p>
    </header>

    <nav aria-label="Main Site Links">
      <a href="#aboutme">About</a>
      <a href="#skills">Skills</a>
      <a href="#education">Education</a>
      <a href="#video">Video</a>
      <a href="#contact">Contact</a>
    </nav>

    <main>
     
      <section id="image">
 <h2>Profile Photo</h2>
        <img class="img" src="https://drive.google.com/file/d/16xmrSrAEkQI52xB_uKEWOJxvpVt0v3su/view?usp=drive_link" alt="my photo">
      </section>

      <section id="aboutme">
        <h2>About Me</h2>
        <p>
          I am a person who loves IT and enjoys learning new software.<br>
          Technology keeps changing, and I like discovering how different programs work. Trying new tools and improving my skills excites me, and I enjoy the challenge of keeping up with the latest developments.<br>
          I want to develop my skills in programming, so I am glad to join this course, and I hope it helps us in the future.
        </p>
      </section>

      <section id="skills">
        <h2>My Skills</h2>
        <ul>
          <li>Basic Photoshop and Designing</li>
          <li>VBA</li>
          <li>Advanced Excel</li>
        </ul>
      </section>

      <section id="video">
        <h2>Video</h2>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/ItZN6o0ylao" title="YouTube video"></iframe>
      </section>

      <section id="education">
        <h2>Education</h2>
        <ul>
          <li>Diploma in Computer Engineering</li>
          <li>ICDL Certificate</li>
          <li>Personal Development Employability Level 1</li>
          <li>Customer Service E3</li>
        </ul>
      </section>

      <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: fadidandoush@hotmail.com</p>
      </section>
    </main>

    <footer>
      <p class="c-site-footer">Fadi Dandoush</p>
    </footer>
  </body>
</html>
