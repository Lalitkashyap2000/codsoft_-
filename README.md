# codsoft_-
internship 
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Lalit kashyap - Web Developer Portfolio</title>
        <link rel="stylesheet" href="style.css">
    </head>
<body>
    <!-- Header Section -->
    <header>
        <div class="logo">
            <h1>Lalit Kashyap</h1>
        </div>
    </header>

    <!-- About Section -->
    <section id="about">
        <div class="bio">
            <img src="lalit.jpeg" alt="Your Photo">
            <p>Hello! I'm Lalit Kashyap, a passionate web developer with expertise in front-end and back-end technologies(php). I create responsive, user-friendly websites and applications like CRUD.</p>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML, CSS, PHP, MySQL, GitHub<li>

          
        </ul>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <img src="p1.jpg" alt="Project 1"> | <img src="p2.jpg" alt="Project 1"> <br><br>
            <h3>Project 1 Title</h3>
            <p>This is a description of Project 1. It includes the technologies used to create logo.</p><br><br>
            <h3>Project 2 Title</h3>
            <p>This is a description of Project 2. It includes the technologies to use CRUD application.</p>
        </div>
    </section>

    <!-- Resume Section -->
    <section id="resume">
        <h2>Resume</h2>
        <a href="lalit UPDATED CV.pdf" download>Download My Resume (PDF)</a>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact</h2>
        <p>Email: kashyapkaylalit@email.com</p>
        <p>Phone: 853-200-9436</p>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Lalit Kashyap. All rights reserved.</p>
        <p><a href="https://www.linkedin.com/in/lalit-kashyap-102b3b21a?">LinkedIn</a> | <a href="https://github.com/Lalitkashyap2000/">GitHub</a> | <a href="https://web.telegram.org/a/">Telegram</a></p>
    </footer>
</body>

css----------


* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
}

header .logo h1 {
    font-size: 36px;
}

section {
    padding: 40px 20px;
    text-align: center;
}

#about {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 20px;
}

#about img {
    border-radius: 70%;
    width: 150px;
    height: 150px;
    object-fit: cover;
}

#skills ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    gap: 15px;
    font-size: 18px;
}

#projects .project {
    margin-bottom: 20px;
}

#projects img {
    width: 100%;
    max-width: 400px;
    height: auto;
    margin-bottom: 10px;
}

#projects .project h3 {
    margin-top: 10px;
    font-size: 24px;
}

#resume a {
    font-size: 15px;
    color: #333;
    text-decoration: none;
    background-color: #f4f4f4;
    padding: 5px 10px;
    border-radius: 5px;
}


#contact p {
    font-size: 18px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
}

footer a {
    color: #fff;
    text-decoration: none;
    margin: 0 10px;
}

footer a:hover {
    text-decoration: underline;
}

</html>
