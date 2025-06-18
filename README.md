# Ex01 Portfolio
## Name: UDAYAKUMAR R
## Reg No: 212222230163
## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="mediaqueries.css">
</head>
<body>
    <nav id="desktop-nav">
        <div class="logo">Udayakumar R</div>
        <div>
             <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#experience">Experience</a></li>
                <li><a href="#project">Projects</a></li>
                <li><a href="#contact">contact</a></li>
            </ul>
        </div>
    </nav>
    <nav id="hamburger-nav">
        <div class="logo">Udayakumar R</div>
        <div class="hamburger-menu">
            <div class="hamburger-icon" onclick="toggleMenu()">
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="menu-links">
                <li><a href="#about" onclick="toggleMenu()">About</a></li>
                <li><a href="#about" onclick="toggleMenu()">Experience</a></li>
                <li><a href="#about" onclick="toggleMenu()">Projects</a></li>
                <li><a href="#about" onclick="toggleMenu()">contact</a></li>
            </div>
        </div>
    </nav>
    <section id="profile">
       <div class="section-pic-container">
            <img src="assests/profile-pic2.png" alt="Udayakumar R">
        </div>
        <div class="section-text">
            <p class="section-text-p1">Hello, I'm</p>
            <h1 class="title">Udayakumar R</h1>
            <!-- <p class="section-text-p2">Frontend  Developer</p> -->
            <div class="btn-container">
                <button class="btn btn-color-2" onclick="window.open('./assests/coin.pdf/')">Resume</button>
                <button class="btn btn-color-1" onclick="location.href = './#contact'">Contact Info</button>
            </div>
            <div id="social-container">
                <img src="./assests/linkedin.png" alt="My linkedIn Profile" class="icon" onclick="location.href='https://linkedin.com/'">
                <img src="./assests/github.png" alt="My github Profile" class="icon" onclick="location.href='https://github.com/'">
            </div>
        </div> 
        </div>
    </section>
    <section id="about">
        <p class="section-text-p1">Get To Know More</p>
        <h1 class="title">About Me</h1>
        <div class="section-container">
          <div class="section-pic-container">
            <img
              src="./assests/image (5).png"
              alt="Profile picture"
              class="about-pic"
            />
          </div>
          <div class="about-details-container">
            <div class="about-containers">
              <div class="details-container">
                <img
                  src="./assests/experience.png"
                  alt="Experience icon"
                  class="icon"
                />
                <h3>Experience</h3>
                <p>2+ years <br />Frontend Development</p>
              </div>
              <div class="details-container">
                <img
                  src="./assests/education.png"
                  alt="Education icon"
                  class="icon"
                />
                <h3>Education</h3>
                <p>+2 HSLC - 89 %<br />B.Tech Artificial Intelligence & Data Science</p>
              </div>
            </div>
            <div class="text-container">
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic quis
                reprehenderit et laborum, rem, dolore eum quod voluptate
                exercitationem nobis, nihil esse debitis maxime facere minus sint
                delectus velit in eos quo officiis explicabo deleniti dignissimos.
                Eligendi illum libero dolorum cum laboriosam corrupti quidem,
                reiciendis ea magnam? Nulla, impedit fuga!
              </p>
            </div>
          </div>
        </div>
        <img
          src="./assests/arrow.png"
          alt="Arrow icon"
          class="icon arrow"
          onclick="location.href='./#experience'"
        />
      </section>
      <section id="experience">
        <p class="section-text-p1">Explore My</p>
        <h1 class="title">Experience</h1>
        <div class="experience-details-container">
            <div class="about-containers">
                <div class="details-container">
                    <h2 class="experience-sub-title">Frontend Development</h2>
                    <div class="article-container">
                        <article>
                            <img src="./assests/checkmark.png" alt="Experience Icon" class="icon">
                            <div>
                                <h3>HTML</h3>
                                <p>Exprienced</p>
                            </div>
                        </article>
                        <article>
                            <img src="./assests/checkmark.png" alt="Experience Icon" class="icon">
                            <div>
                                <h3>CSS</h3>
                                <p>Exprienced</p>
                            </div>
                        </article>
                        <article>
                            <img src="./assests/checkmark.png" alt="Experience Icon" class="icon">
                            <div>
                                <h3>JavaScript</h3>
                                <p>Basic</p>
                            </div>
                        </article>
                        <article>
                            <img src="./assests/checkmark.png" alt="Experience Icon" class="icon">
                            <div>
                                <h3>React</h3>
                                <p>Basic</p>
                            </div>
                        </article>
                        <article>
                            <img src="./assests/checkmark.png" alt="Experience Icon" class="icon">
                            <div>
                                <h3>Python</h3>
                                <p>Intermediate</p>
                            </div>
                        </article>
                        <article>
                            <img src="./assests/checkmark.png" alt="Experience Icon" class="icon">
                            <div>
                                <h3>Java</h3>
                                <p>Intermediate </p>
                            </div>
                        </article>
                    </div>
                </div>
                <div class="details-container">
                    <h2 class="experience-sub-title">Frontend Development</h2>
                    <div class="article-container">
                        <article>
                            <img src="./assests/checkmark.png" alt="Experience Icon" class="icon">
                            <div>
                                <h3>SQL</h3>
                                <p>Exprienced</p>
                            </div>
                        </article>
                        <article>
                            <img src="./assests/checkmark.png" alt="Experience Icon" class="icon">
                            <div>
                                <h3>MongoDB</h3>
                                <p>Intermediate</p>
                            </div>
                        </article>
                        <article>
                            <img src="./assests/checkmark.png" alt="Experience Icon" class="icon">
                            <div>
                                <h3>Node JS</h3>
                                <p>Basic</p>
                            </div>
                        </article>
                        <article>
                            <img src="./assests/checkmark.png" alt="Experience Icon" class="icon">
                            <div>
                                <h3>Docker</h3>
                                <p>Basic</p>
                            </div>
                        </article>
                        <article>
                            <img src="./assests/checkmark.png" alt="Experience Icon" class="icon">
                            <div>
                                <h3>C/C++</h3>
                                <p>Intermediate</p>
                            </div>
                        </article>
                        <article>
                            <img src="./assests/checkmark.png" alt="Experience Icon" class="icon">
                            <div>
                                <h3>Git</h3>
                                <p>Intermediate </p>
                            </div>
                        </article>
                    </div>
                </div>
            </div>
        </div>
        <img
        src="./assests/arrow.png"
        alt="Arrow icon"
        class="icon arrow"
        onclick="location.href='./#project'"
      />
      </section>
      <section id="project">
        <p class="section-text-p1">
            Browse My Recent
        </p>
        <h1 class="title">Projects</h1>
        <div class="experience-details-container">
            <div class="about-containers">
            <div class="details-container color-container">
                <div class="article-container">
                    <img src="./assests/project-1.png" alt="project" class="project-img">
                </div>
                <h2 class="experience-sub-title project-title">Project one</h2>
                <div class="btn-container">
                    <button class="btn btn-color-2 project-btn"
                    onclick="location.href='https://github.com/">
                Github</button>
                    <button class="btn btn-color-1 project-btn"
                    onclick="location.href='https://github.com/">
                Live Demo</button>
                </div>
            </div>
            <div class="details-container color-container">
                <div class="article-container">
                    <img src="./assests/project-2.png" alt="project 2" class="project-img">
                </div>
                <h2 class="experience-sub-title project-title">Project Two</h2>
                <div class="btn-container">
                    <button class="btn btn-color-2 project-btn"
                    onclick="location.href='https://github.com/">
                Github</button>
                    <button class="btn btn-color-1 project-btn"
                    onclick="location.href='https://github.com/">
                Live Demo</button>
                </div>
            </div>
            <div class="details-container color-container">
                <div class="article-container">
                    <img src="./assests/project-3.png" alt="project 3" class="project-img">
                </div>
                <h2 class="experience-sub-title project-title">Project Three</h2>
                <div class="btn-container">
                    <button class="btn btn-color-2 project-btn"
                    onclick="location.href='https://github.com/">
                Github</button>
                    <button class="btn btn-color-1 project-btn"
                    onclick="location.href='https://github.com/">
                Live Demo</button>
                </div>
            </div>
        </div>
        </div>
        <img
        src="./assests/arrow.png"
        alt="Arrow icon"
        class="icon arrow"
        onclick="location.href='./#contact'"
      />
      </section>
      <section id="contact">
        <p class="section-text-p1">Get in Touch</p>
        <h1 class="title">Contact Me</h1>
        <div class="contact-info-upper-container">
          <div class="contact-info-container">
            <img
              src="./assests/email.png"
              alt="Email icon"
              class="icon contact-icon email-icon"
            />
            <p><a href="mailto:examplemail@gmail.com">udayakumarr24@gmail.com</a></p>
          </div>
          <div class="contact-info-container">
            <img
              src="./assests/linkedin.png"
              alt="LinkedIn icon"
              class="icon contact-icon"
            />
            <p><a href="https://www.linkedin.com">LinkedIn</a></p>
          </div>
        </div>
      </section>
      <footer>
        <nav>
            <div class="nav-links-container">
                <ul class="nav-links">
                    <li><a href="#about">About</a></li>
                    <li><a href="#experience">Experience</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </div>
        </nav>
        <p>Copyright &#169; 2025 Udayakumar R. All Rights Reserved.</p>
      </footer>
    <script src="script.js"></script>
</body>
</html> 
```
```css
/*@import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');*/
@import url('https://fonts.googleapis.com/css2?family=Gayathri:wght@100;400;700&family=Gravitas+One&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Press+Start+2P&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Gayathri:wght@100;400;700&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Press+Start+2P&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Press+Start+2P&display=swap');

@font-face {
    font-family:'Customfont';
    src: url(/assests/Maken.ttf);
}


*{
    padding: 0;
    margin: 0;
}
body { 
       /* font-family: "Poppins", sans-serif;  */
       font-family: "Gayathri", sans-serif;
}

html {
    scroll-behavior: smooth;
}

p{
    color: rgb(85, 85, 85);
}

a,
.btn{
    transition: all 300ms ease;
}
nav,
.nav-links{
    display: flex;
}

nav {
    justify-content: space-around;
    align-items: center;
    height: 17vh;
}

.nav-links
{
    gap: 2rem;
    list-style: none;
    font-size: 1.5rem;
    
}

a{
    color: black;
    text-decoration: none;
    text-decoration-color: white;
}

a:hover{
    color: grey;
    text-decoration: underline;
    text-underline-offset: 1rem;
    text-decoration-color: rgb(181, 181, 181);
}

.logo{
    font-family: "Gayathri", sans-serif;
    font-size: 2.2rem;
    color: rgb(17, 15, 15);
}

.logo:hover{
    cursor: default;
}

/* HAMBURGER MENU*/

#hamburger-nav{
    display: none;
}

.hamburger-menu
{
    position: relative;
    display: inline-block;
}

.hamburger-icon{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    height: 24px;
    width: 30px;
    cursor: pointer;

}

.hamburger-icon span{
    width: 100%;
    height: 2px;
    background-color: black;
    transition: all 0.3 ease-in-out;
}

.menu-links{
    position: absolute;
    right: 0;
    top: 100%;
    background-color: white;
    width: fit-content;
    max-height: 0;
    overflow: hidden;
    transition: all 0.3 ease-in-out;
}

.menu-links a{
    display: block;
    padding: 10px;
    text-align: center;
    color: black;
    text-decoration: none;
    font-size: 1.5rem;
    transition: all 0.3 ease-in-out;
}

.menu-links li{
    list-style: none;
}

.menu-links.open{
    max-height: 300px;
}

.hamburger-icon.open span:first-child{
    transform: rotate(45deg) translate(10px, 5px);
}
.hamburger-icon.open span:nth-child(2){
    opacity: 0;
}
.hamburger-icon.open span:last-child{
    transform: rotate(-45deg) translate(10px,-5px);
}

.hamburger-icon span:first-child{
    transform: none;
}
.hamburger-icon span:first-child{
    opacity: 1;
}
.hamburger-icon span:first-child{
    transform: none;
}

/* SECTIONS */
section {
    /* background-image: linear-gradient(rgba(195, 195, 175, 0.548),rgba(54, 146, 198, 0.767),rgba(255, 0, 0, 0.224)); */
    padding-top: 4vh;
    height: 96vh;
    margin: 0 10rem;
    box-sizing: border-box;
    min-height: fit-content;
}

.section-container {
    display: flex;
}


.about1-container {
    position: relative;
    width: 400px; /* Adjust as needed */
    text-align: center;
    margin: auto;
}

.about1-container h1 {
    position: absolute;
    top: 10px;
    left: 50%;
    transform: translateX(-50%);
    font-size: 6rem; /* Adjust font size */
    font-weight: bold;
    color: white; /* Fill color */
    -webkit-text-stroke: 3px black; /* Border effect */
    text-transform: uppercase;
    z-index: 1; /* Behind the image */
}

.about1-container img {
    width: 100%;
    position: relative;
    z-index: 2; /* Image on top */
}


/* PROFILE SECTION */

#profile {
    display: flex;
    justify-content: center;
    gap: 10rem;
    height: 80vh;
} 
.section-pic-container{
    display: flex;
    height: 600px;
    width: 600px;
    margin: auto 0;
}

.section-text
{
    align-self: center;
    text-align: center;
}
.section-text p
{
    font-weight: 600;
}
.section-text-p1{
    text-align: center;
}
.section-text-p2
{
    font-size: 1.75rem;
    margin-bottom: 1rem;
}

.title {
    font-size: 2rem;
    text-align: center;
}

#social-container
{
    display: flex;
    justify-content: center;
    margin-top: 1rem;
    gap: 1rem;
}

.icon {
    cursor: pointer;
    height: 2rem;
}

/* BUTTONS */

.btn-container {
    display: flex;
    justify-content: center;
    gap: 1rem;
}

.btn {
    font-family: "Gayathri", sans-serif;
    font-weight: 500;
    transition: all 300ms ease;
    padding: 1rem;
    width: 7rem;
    border-radius: 2rem;
}

.btn-color-1,
.btn-color-2:hover {
    background: rgb(53,53, 53);
    color: white;
}

.btn-color-1:hover{
    background: rgb(0, 0, 0);
}

.btn-color-2 {
    background: none;
}

.btn-color-2:hover {
    border: rgb(255, 255, 255);
}

.btn-container{
    gap: 1rem;
}  


/* ABOUT */

#about {
    position: relative;
  }
  
  .about-containers {
    gap: 2rem;
    margin-bottom: 2rem;
    margin-top: 2rem;
  }
  
  .about-details-container {
    justify-content: center;
    flex-direction: column;
  }
  
  .about-containers,
  .about-details-container {
    display: flex;
  }
  
  .about-pic {
    border-radius: 2rem;
  }
  
  .arrow {
    position: absolute;
    right: -5rem;
    bottom: 2.5rem;
  }
  
  .details-container {
    padding: 1.5rem;
    flex: 1;
    background: white;
    border-radius: 2rem;
    border: rgb(53, 53, 53) 0.1rem solid;
    border-color: rgb(163, 163, 163);
    text-align: center;
  }
  
  .section-container {
    gap: 4rem;
    height: 80%;
  }
  
  .section-pic-container {
    height: 400px;
    width: 400px;
    margin: auto 0;
  }

   /* EXPERIENCE SECTION */

   #experience{
    position: relative;
   }

   .experience-sub-title {
    color: rgb(85, 85, 85);
    font-weight: 600;
    font-size: 1.75rem;
    margin-bottom: 2rem;
   }

   .experience-details-container{
    display: flex;
    justify-content: center;
    flex-direction: column;
   }

   .article-container{
    display: flex;
    text-align: initial;
    flex-wrap: wrap;
    flex-direction: row;
    gap: 2.5rem;
    justify-content: space-around;
   }

   article {
    display: flex;
    width: 10rem;
    justify-content: space-around;
    gap: 0.5rem;
   }

   article .icon{
    cursor: default;
   }

   /* PROJECT SECTION */
   #project {
    position: relative;
   }

   .color-container {
    border-color: rgb(163, 163, 163);
    background: rgb(250, 250, 250);
   }

   .project-img {
    border-radius: 2rem;
    width: 90%;
    height: 90%;
   }

   .project-title{
    margin: 1rem;
    color: black;
   }

   /* CONTACTS SECTION */
   #contact {
    display: flex;
    justify-content: center;
    flex-direction: column;
    height: 70vh;
  }
  
  .contact-info-upper-container {
    display: flex;
    justify-content: center;
    border-radius: 2rem;
    border: rgb(53, 53, 53) 0.1rem solid;
    border-color: rgb(163, 163, 163);
    background: (250, 250, 250);
    margin: 2rem auto;
    padding: 0.5rem;
  }
  
  .contact-info-container {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 0.5rem;
    margin: 1rem;
  }
  
  .contact-info-container p {
    font-size: larger;
  }
  
  .contact-icon {
    cursor: default;
  }
  
  .email-icon {
    height: 2.5rem;
  }
  

  /* FOOTER SECTION */

  footer{
    height: 26vh;
    margin: 0 1rem;
  }

  footer p {
    text-align: center;
  }
```
## OUTPUT
![image](https://github.com/user-attachments/assets/ed9ebb29-4aa3-4dbc-ad15-c2dfad9b15ea)
![image](https://github.com/user-attachments/assets/438050d3-d6aa-4695-8d97-20f13bb74c83)
![image](https://github.com/user-attachments/assets/68746856-4053-4a4d-8069-918c85d82eef)

![image](https://github.com/user-attachments/assets/4ced1608-0775-4f77-8100-9d26cce0f4c9)
![image](https://github.com/user-attachments/assets/a1d48e8d-edbd-40fe-8385-3190b5e88180)


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
