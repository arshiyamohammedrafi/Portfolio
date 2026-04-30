# Ex01 Portfolio
## Date:

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Arshiya's Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            background-color: #333;
            color: white;
            padding: 0.5rem;
        }
        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            margin: 0 1rem;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        section {
            padding: 2rem;
            margin: 0 auto;
            max-width: 800px;
        }
        #home {
            background-color: #f4f4f4;
            text-align: center;
        }
        .home-photo {
            width: 180px;
            height: 180px;
            border-radius: 50%;
            object-fit: cover;
            margin: 1rem auto;
            border: 4px solid #4CAF50;
            display: block;
        }
        #about {
            background-color: #e9e9e9;
        }
        #skills {
            background-color: #f4f4f4;
        }
        #contact {
            background-color: #e9e9e9;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
        }
        .skills-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .skill {
            background-color: #4CAF50;
            color: white;
            padding: 0.5rem 1rem;
            margin: 0.5rem;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Arshiya's Portfolio</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section id="home">
        <h2>Welcome to My Portfolio</h2>
        <img src="mypic.jpeg" alt="Arshiya's photo" class="home-photo">
        <p>Hello! I'm Arshiya, a passionate developer and designer.</p>
    </section>
    <section id="about">
        <h2>About Me</h2>
        <p>I am Arshiya, enthusiastic about technology and creativity. I enjoy coding and designing user-friendly applications.</p>
    </section>
    <section id="skills">
        <h2>My Skills</h2>
        <div class="skills-list">
            <div class="skill">C</div>
            <div class="skill">C++</div>
            <div class="skill">Python</div>
            <div class="skill">GitHub</div>
            <div class="skill">Canva</div>
            <div class="skill">Figma</div>
            <div class="skill">SQL</div>
        </div>
    </section>
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Feel free to reach out!</p>
        <p>Email: arshiya@example.com</p>
        <p>Phone: (123) 456-7890</p>
    </section>
    <footer>
        <p>&copy; 2026 Arshiya. All rights reserved.</p>
    </footer>
</body>
</html>
```





## OUTPUT

<img width="1906" height="824" alt="image" src="https://github.com/user-attachments/assets/7d6857d1-ba2c-4c3e-9ec7-78827a075d7c" />

<img width="1873" height="947" alt="image" src="https://github.com/user-attachments/assets/9fa95f9d-0427-41fd-aaeb-57ac990b2b29" />







## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
