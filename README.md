

# Portfolio
Sample of my Portfolio
<<CSS>>
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
font-family: 'Times New Roman', Times, serif;
line-height:1,4;
color: #333;
overflow-x: hidden;
}
.container{
    max-width: 1100px;
    margin: auto;
}
.text-primary{
    color: #3693ff;
}
.bg-light{
    background: #f4f4f4;
    color: #333;
}
#navbar{
    display: flex;
    justify-content: space-between;
    background: #333;
    color: #fff;
    padding: 1.5rem 8rem;
    position: sticky;
    top: 0;
    z-index: 1;
    border-bottom: 3px solid #3693ff;
}
#navbar ul{
    display: flex;
    align-items: center;
    list-style: none;
}
#navbar h2 a{
    color: #fff;
    text-decoration: none;
}
#navbar li a{
    text-decoration: none;
    color: #fff;
    padding: 1rem;
    font-size: 1.3rem;
    margin: 0 0.5rem;
    border-radius: 5px;
    transition: background-color 0.3s;
}
#navbar li a:hover{
    background-color: #3693ff;
}

#showcase{
    background: url(../images/wp4974496.jpg) no-repeat center center/cover;
    height: 100vh;
}
 .showcase-content {
display: flex;
flex-direction: column;
text-align: center;
align-items: center;
justify-content: center;
position: absolute;
top: 81px;
left: 0;
bottom: 0;
right: 0;
background: rgba(0,0,0,0.7);
color: #fff;
}

.showcase-content h1 {
    font-size: 4rem;
    margin-top: 0.5rem;
}

.showcase-content .btn {
    font-size: 1.5rem;
    padding:  1rem 10 rem;
}

.btn {
    color: #3693ff;
    text-decoration: none;
    display: inline-block;
    padding: 1rem 2rem;
    border: 1px solid #3693ff;
    border-radius: 10px;
    font-weight: bold;
}

#about {
    padding: 5rem 0;

}

#about h2 {
    text-align: center;
    font-size: 4rem;
    margin-bottom: 3rem;
}

#about h3 {
    font-size: 2rem;
    margin-bottom: 2rem;
}

#about p.lead {
margin-bottom: 1rem;
font-family: 'Times New Roman', Times, serif;
font-size: 1.5rem;
text-align: center;
}

#about .about-content {
    display:flex;
    font-family: 'Times New Roman', Times, serif;
font-size: 1.5rem;
text-align: center;
}

#about .About-text,

#Services{
    padding: 3rem;
}

#Services h2{
    text-align: center;
    margin-bottom: 2rem;
    font-size: 2rem;
}

#Services .boxes{
    display: flex;
}

#Services .box{
    background: #fff;
    flex: 1;
    padding: 3rem;
    margin: 0 3rem;
    border-radius: 10px;
    box-shadow: 2px 2px 5px #d1d1d1;
    font-size: 1.3rem;
}
#Services .box i{
    color: #fff;
    padding:  1rem;
    background: #3693ff;
    border-radius: 50%;
    margin: 0 1rem;
    margin-bottom: 2rem;
}


#Portfolio {
    padding: 2rem;
}
#Portfolio h2{
    text-align: center;
    margin-bottom: 2rem;
    font-size: 2rem;
}
#Portfolio p.lead{
    font-size: 2rem;
    display: flex;
    font-family: 'Times New Roman', Times, serif;
}
.center{
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 50%;
}

#Contact{
    padding: 5rem 0; 
}

#Contact h2{
    text-align: center;
    font-size: 3rem;
    margin-bottom: 8rem;
}

#Contact h3{
    text-align: center;
    font-size: 2.5rem;
    margin: 3rem 0;
    margin-top: 5rem;
}

#Contact .form-box{
    background: #fff;
    padding: 3rem;
    box-shadow: 2px 2px 5px #d1d1d1;
    border-radius: 10px;
}

#Contact .form-group{
    margin-bottom: 2rem;
}

#Contact .form-group label{
    display: block;
    margin-bottom: 0.5rem;
    width: 80%;
    margin-left: 10%;
    font-size: 1.1rem;
}

#Contact .form-group input,
#Contact .form-group textarea{
    width:  80%;
    margin-left: 10%;
    font-size: 1.3rem;
    padding: 1rem;
    border: 0.5px solid #333;
    border-radius: 5px;
}

#Contact .form-group textarea{
    font-family: 'Times New Roman', Times, serif;

}

#Contact .contact-btn{
    width: 80%;
    margin-left: 10%;
    display: inline-block;
    padding: 1rem;
    border: none;
    border-radius:  5px;
    font-size: 1.5rem;
    background: #3693ff;
    color: #fff;
    margin-bottom: 2rem;
    cursor: pointer;
}

#Contact .contact-btn:hover{
    background: #0378ff;
}

#Contact .form-container{
    position: relative;
}
#Contact .mail-icon{
    font-size: 4rem;
    background: #3693ff;
    color: #fff;
    display: inline-block;
    padding: 1.5rem 2rem;
    border-radius: 50%;
    position: absolute;
    top: -7%;
}
footer{
    padding: 4rem;
    background: #333;
    color: #fff;
}
footer p{
    text-align: center;
}
#wrapper{
    margin-bottom: 30px;
position: center;
transform: translate(-50%, -50%);
}
.wrapper ul{
    list-style: none;
}

.wrapper ul li{
    width: 55px;
    height: 55px;
    line-height: 62px;
    margin: 0 10px;
    text-align: center;
    cursor: pointer;
    border-radius: 50%;
    border: 3px solid;
    float: left;
    transition: all 0.5s ease;
}
.wrapper ul li .fa{
    color: #fff;
    margin-top: 5px;
    transition: all 0.5s ease;
}

.wrapper ul li:hover:nth-child(1){
    border: 3px solid #3b5998;
    box-shadow: 0 0 15px #3b5998 ;
}

.wrapper ul li:hover .fa-facebook{
    color: #3b5998;
    text-shadow: 0 0 15px #3b5998;
    transition: all 0.5s ease;
}

.wrapper ul li:hover:nth-child(2){
    border: 3px solid #bc2a8d;
    box-shadow: 0 0 15px #bc2a8d ;
}

.wrapper ul li:hover .fa-instagram{
    color: #bc2a8d;
    text-shadow: 0 0 15px #bc2a8d;
    transition: all 0.5s ease;
}

.wrapper ul li:hover:nth-child(3){
    border: 3px solid #0a66c2;
    box-shadow: 0 0 15px  #0a66c2;
}

.wrapper ul li:hover .fa-linkedin{
    color: #0a66c2;
    text-shadow: 0 0 15px #0a66c2;
    transition: all 0.5s ease;
}


<<HTML>>
  <!DOCTYPE html>
<html lang="en">
<head>
        <meta charet="UTF-8">
        <title>Ruba WebDev</title>
        <meta name="viewport" content= "device-width, initial-scale=1.0">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
        <link rel="stylesheet" href="css/style.css">
    </head>
    <body id="home">
<nav id="navbar">
    <h2><a href="#home"><span class="text-primary">Ruba</span>  Qazi</a></h2>
    <ul>
        <li><a href="#home">Home</Home></a></li>
        <li><a href="#about">About</About></a></li>
        <li><a href="#Services">Services</Services></a></li>
        <li><a href="#Portfolio">Portfolio</Contact></a></li>   
        <li><a href="#Contact">Contact</Contact></a></li>  
    </ul>
    </nav>
    <header id="showcase">
       <div class="showcase-content">
           <div class="container">
               <h1>Take your Company to the <br><spam class="text-primary"> Next Level</spam></h1> 
               <a href="#about" class="btn">FIND OUT HOW</a>
           </div>

    </header>
    <section id="about">
        <h2 class="About-heading">Get to Know <span class="text-primary">About Me</span></h2>
        <div class="about-content">
            <div class="about-text">
            <h3> A Little Bit <spam class="text-primary">About MySelf</spam></h3>
            <p> Hello, My Name is Ruba a young front-end developer and a Software Engineer. I like to code things from scratch, and bringing ideas to life in the browser. I'm an expert developer with scholastic experience. Front End Developers work on those sections of a website or application that is visible for the users to use and interact with. I can code anything you need from little tasks, models to whole applications.</p><br>
            <p class="lead">Coding is my hobby not my passion. I code for my happiness and feel happy by helping others in their codes. Having experience in creating websites, creating web applications through reactjs.</p>
            <p> With all these, I am a student of BS Computer Science in Fatima Jinnah Women University Rawalpindi.</p>
            <p>I am also a professional Graphic designer, photographer, videographer, and a professional typist.</p><br>
            <p> I am also a player of Cricket(team Captain), Badminton, Football, Baseball, because I Love Playing.</p><br>
            <h4> Below I have uploaded my <spam class="text-primary">Resume</spam></h4>
                <img src="images/CV.png" alt="A resume is attached">
         </div>
        </div>
    </section>

    <section id="Services" class="bg-light">
        <div class="container">
            <h2> Here is What<span class="text-primary">  I have to offer</span></h2>
            <div class="boxes">
                <div class="box">
                    <h3><span class="text-primary">Developer & Software Engineer</span></h3>
                    <div class="feature">
                       <i class="fa fa-check"></i> Modern Layout design
                    </div>
                    <div class="feature">
                        <i class="fa fa-check"></i> Responsive Website design
                    </div>
                    <div class="feature">
                        <i class="fa fa-check"></i> Mockups
                    </div>
                    <div class="feature">
                        <i class="fa fa-check"></i> Browser Compatibility
                    </div> 
                    <div class="feature">
                        <i class="fa fa-check"></i> Web Applications
                    </div>
                    <div class="feature">
                        <i class="fa fa-check"></i> Android Applications
                    </div>
                </div>
                <div class="box">
                    <h3><span class="text-primary">Graphic Designer & Writer</span></h3>
                    <div class="feature">
                        <i class="fa fa-check"></i> Photography, Photo-editing
                    </div>
                    <div class="feature">
                        <i class="fa fa-check"></i> Videography, Video-editing
                    </div>
                    <div class="feature">
                        <i class="fa fa-check"></i> Logo Design
                    </div>
                    <div class="feature">
                        <i class="fa fa-check"></i> Resume,CV
                    </div> 
                    <div class="feature">
                        <i class="fa fa-check"></i> Blog writing
                    </div> 
                    <div class="feature">
                        <i class="fa fa-check"></i> Content writing
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="Portfolio">
        <div>
        <h2> Here is what <spam class="text-primary">I have done</spam>.<br> Hope so you will <spam class="text-primary"> like it</spam>.</h2>
        <p class="lead"> This is the logo I have created for a <spam class="text-primary"> Dog House</spam></p><br>
            <img src="images/Dog.png" alt= "500" height="700" class="center"> 
        </div>
        <br>
        <br>
        <div>
            <p class="lead"> This is the logo I have created for a <spam class="text-primary"> Photography Page</spam></p><br>
            <img src="images/DR Logo.jpg" width="600" height="500" class="center">
        </div>
        <br>
        <br>
        <div>
            <p class="lead"> This is the logo I have created for a <spam class="text-primary"> Blog website</spam></p><br>
            <img src="images/Blog Logo.jpeg" width="500" height="500" class="center">
        </div>
        <br>
        <br>
        <div>
            <p class="lead"> This is the logo I have created for a company named <spam class="text-primary"> BlueHat</spam></p><br>
            <img src="images/coloured Ruba logo.jpg" width="400" height="500" class="center">
        </div>
        <br>
        <br>
        <div>
            <p class="lead"> This is the picture I have created for my  <spam class="text-primary"> Whatsapp Display Picture</spam></p><br>
            <img src="images/Whatsapp DP.JPG" width="300" height="500" class="center">
        </div>
        <br>
        <br>
        <div>
            <p class="lead"> These are outputs of a  <spam class="text-primary">calculator</spam> I have created <spam class="text-primary"> Reactjs </spam></p><br>
            <img src="images/Calculator.png" width="1300" height="700">
        </div>
        <div>
            <p class="lead"> I am creating a functional website as a project of a software house from <spam class="text-primary"> Mockups</spam> I have created</p><br>
            <img src="images/Mockup.png" width="1300" height="700">
        </div>
        <p class="lead"> And here is some collection of my <spam class="text-primary"> Clicks(Photography)</spam></p>
        <img src="images/Car.png" width="500" height="400" class="center"><br>
        <img src="images/Car1.png" width="400" height="650" class="center"><br>
        <img src="images/Hostel.png" width="400" height="650" class="center"><br>
        <img src="images/WhatsApp Image 2021-05-10 at 5.32.56 PM (1).jpeg" width="50" height="400" class="center"><br>
        <img src="images/WhatsApp Image 2021-05-10 at 5.32.56 PM.jpeg" width="300" height="400" class="center"><br>
        <img src="images/WhatsApp Image 2021-05-10 at 5.33.44 PM.jpeg" width="200" height="700" class="center"><br>
        <br>
        <br>
    </section>


<section id="Contact" class="bg-light">
    <div class="container">
        <h2> Get Your <spam class="text-primary"> Killer Website</spam> Now</h2>
        <div class="form-container">
            <div class="mail-icon"> <i class="fa fa-envelope"></i></div>
            <div class="form-box">
                <h3> Shoot Me a <spam class="text-primary"> Message</spam> </h3>
                <form>
                    <div class="form-group">
                        <label for="first-name">First Name</label>
                        <input type="text" placeholder="Enter your First Name">
                    </div>
                    <div class="form-group">
                        <label for="last-name">Last Name</label>
                        <input type="text" placeholder="Enter your Last Name">
                    </div>
                    <div class="form-group">
                        <label for="email">Email</label>
                        <input type="text" placeholder="Enter your Email Address">
                    </div>
                    <div class="form-group">
                        <label for="message">Message</label>
                        <textarea rows="7" placeholder="Type your message here"></textarea>
                    </div>
                    <input type="submit" onclick="sendEmail()" value="Send Message" class="contact-btn">

                    </div>
                </form>
            </div>
        </div> 
    </div>
</section>
<footer>
    <p> Copyrigt &copy; Ruba Qazi Web Dev 2021</p>
<div class="wrapper">
    <ul>
      <li><a href="https://www.facebook.com/profile.php?id=100025798638713"><i class="fa fa-facebook fa-2x" aria-hidden="true"></i></li></a>  
      <li><a href="https://www.instagram.com/r_u_b_a_q_a_z_i/"><i class="fa fa-instagram fa-2x" aria-hidden="true"></i></li></a>  
      <li><a href="https://www.linkedin.com/in/ruba-tabassum-a067151b8"><i class="fa fa-linkedin fa-2x" aria-hidden="true"></i></li></a> 
    </ul>
</div>
</footer>

<script
  src="https://code.jquery.com/jquery-3.6.0.min.js"
  integrity="sha256-/xUj+3OJU5yExlq6GSYGSHk7tPXikynS7ogEvDej/m4="
  crossorigin="anonymous"></script>

  <script src="js/main.js">
</script>

</body>
</html>
