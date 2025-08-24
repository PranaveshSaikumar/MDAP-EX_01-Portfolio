# MDAP-EX_01-Portfolio
## Date: 20-08-2025

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
```
html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="Exp1Style.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#intro">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#works">Works</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="intro">
    <h1>Hello, I'm Pranavesh Saikumar</h1>
    <p>Aspiring designer in the field of IoT and Embedded Systems | Programmer</p>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>
      I am really interested in <strong>IoT</strong> and <strong>Embedded Systems</strong>, 
      exploring how software and hardware can integrate to create impactful applications. 
      I have experience in programming languages such as <strong>C</strong>, 
      <strong>Python</strong>, <strong>C++</strong>, and <strong>Java</strong>. 
      Currently, I am learning <strong>Embedded C</strong> and continuously exploring 
      new opportunities to apply my skills in real-world projects.
    </p>
  </section>

  <section id="works">
    <h2>My Works</h2>
    <div class="work-grid">
      <div class="work">
        <a href="https://github.com/PranaveshSaikumar" target="_blank">
          <img src="images/STM.jpeg" alt="Project One">
        </a>
        <p>Check out works related to IoT and other domains.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>Phone: <a href="tel:8754400115">8754400115</a></p>
    <p>Email: <a href="mailto:pranaveshsaikumar2005@gmail.com">pranaveshsaikumar2005@gmail.com</a></p>
    <p>LinkedIn: <a href="https://linkedin.com/in/PranaveshSaikumar" target="_blank">linkedin.com/in/PranaveshSaikumar</a></p>
  </section>

  <footer>
    <p>© 2025 My Portfolio</p>
  </footer>
</body>
</html>
```
```
.css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Segoe UI", Arial, sans-serif;
  line-height: 1.6;
  background: #f5f7fa;
  color: #333;
}

header {
  background: #2c3e50;
  padding: 15px 0;
  position: sticky;
  top: 0;
  z-index: 1000;
}

nav ul {
  display: flex;
  justify-content: center;
  list-style: none;
}

nav ul li {
  margin: 0 20px;
}

nav ul li a {
  color: #ecf0f1;
  text-decoration: none;
  font-weight: bold;
  transition: color 0.3s;
}

nav ul li a:hover {
  color: #1abc9c;
}

section {
  padding: 80px 20px;
  text-align: center;
}

section:nth-child(even) {
  background: #ecf0f1;
}

h1, h2 {
  margin-bottom: 20px;
  color: #2c3e50;
}

p {
  max-width: 600px;
  margin: 0 auto 20px;
  font-size: 1.1rem;
}

#intro img {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  margin-top: 20px;
  border: 4px solid #1abc9c;
}

/* Works section */
.work-grid {
  display: flex;
  justify-content: center;
  gap: 20px;
  flex-wrap: wrap;
  margin-top: 30px;
}

.work {
  background: transparent;
  padding: 15px;
  width: 280px;
  text-align: center;
}

/* Fix oversized images */
.work img {
  width: 100%;          /* scale to container */
  max-width: 250px;     /* prevent too large */
  height: auto;         /* keep proportions */
  border-radius: 10px;
  margin-bottom: 15px;
  transition: transform 0.3s;
}

.work img:hover {
  transform: scale(1.05);
}

#contact p {
  font-size: 1.1rem;
  margin: 10px 0;
}

#contact a {
  color: #1abc9c;
  text-decoration: none;
}

#contact a:hover {
  text-decoration: underline;
}

footer {
  text-align: center;
  padding: 20px;
  background: #2c3e50;
  color: #ecf0f1;
  margin-top: 30px;
}
```


## OUTPUT

<img width="1918" height="988" alt="image" src="https://github.com/user-attachments/assets/d798c164-6d22-4e03-88e4-2ab91b61cc8e" />

<img width="1917" height="917" alt="image" src="https://github.com/user-attachments/assets/63a355f9-cdf4-4c90-8f2d-633129010404" />

<img width="1893" height="567" alt="image" src="https://github.com/user-attachments/assets/b07f45ca-086e-4777-bb32-04dcd910d762" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
