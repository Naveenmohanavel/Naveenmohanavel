<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Naveen Mohanavel | Portfolio</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#f4f4f4;
    color:#333;
}

header{
    background:#222;
    color:white;
    padding:20px;
    text-align:center;
}

nav{
    background:#444;
    padding:10px;
    text-align:center;
}

nav a{
    color:white;
    text-decoration:none;
    margin:20px;
    font-weight:bold;
}

nav a:hover{
    color:orange;
}

section{
    width:80%;
    margin:auto;
    padding:40px 0;
}

h2{
    color:#222;
    margin-bottom:15px;
}

.card{
    background:white;
    padding:20px;
    margin:20px 0;
    border-radius:10px;
    box-shadow:0 0 10px gray;
}

ul{
    padding-left:20px;
}

button{
    background:#007BFF;
    color:white;
    padding:10px 20px;
    border:none;
    border-radius:5px;
    cursor:pointer;
}

button:hover{
    background:#0056b3;
}

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:15px;
    margin-top:30px;
}

</style>

</head>

<body>

<header>
    <h1>Naveen Mohanavel</h1>
    <p>Computer Science Engineering Student</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#education">Education</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">

<div class="card">
<h2>About Me</h2>

<p>
Hello! I am Naveen Mohanavel, a Computer Science Engineering student passionate about Web Development, Java Programming, Cloud Computing, Networking, and AI technologies.
</p>

</div>

</section>

<section id="skills">

<div class="card">

<h2>Skills</h2>

<ul>
<li>HTML</li>
<li>CSS</li>
<li>JavaScript</li>
<li>Java</li>
<li>Python</li>
<li>SQL</li>
<li>Git & GitHub</li>
<li>Azure Cloud</li>

</ul>

</div>

</section>

<section id="projects">

<div class="card">

<h2>Projects</h2>

<h3>1. Smart Traffic Control System</h3>

<p>
Developed a smart traffic management system using MERN Stack for intelligent traffic monitoring.
</p>

<br>

<h3>2. Cloud Resume Website</h3>

<p>
Created a portfolio website using Azure Blob Storage, Azure Functions and GitHub Pages.
</p>

<br>

<h3>3. Smart Earthquake Detection System</h3>

<p>
An IoT-based system for detecting earthquakes using sensors and cloud technologies.
</p>

</div>

</section>

<section id="education">

<div class="card">

<h2>Education</h2>

<p>
<b>B.E Computer Science and Engineering</b><br>
Karpagam Institute of Technology<br>
2023 - 2027
</p>

</div>

</section>

<section id="contact">

<div class="card">

<h2>Contact</h2>

<p>Email : yourmail@gmail.com</p>

<p>Phone : +91 XXXXXXXXXX</p>

<p>GitHub :
<a href="https://github.com/yourusername" target="_blank">
https://github.com/yourusername
</a>
</p>

<br>

<button onclick="message()">
Say Hello
</button>

</div>

</section>

<footer>

<p>© 2026 Naveen Mohanavel | All Rights Reserved</p>

</footer>

<script>

function message()
{
    alert("Thank you for visiting my Portfolio!");
}

</script>

</body>
</html>
