# Final Project and Deployment

## Objectives
Build a fully functional web application.
Apply HTML, CSS, and JavaScript concepts learned.
Deploy the project using GitHub Pages, Netlify, or Vercel.

## Instructions
Choose one of the following project ideas:
Blog Website: Implement a multi-page site with navigation.
Ecommerce Website: Implement a multi-page site with navigation.

>[!NOTE]
> - Include at least:
> - A responsive design.
> - JavaScript interactivity.
> - A deployment link.

## Tasks

Create a well-structured HTML5 document.
Use at least 5 different HTML elements.
Ensure semantic correctness.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Blog</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <article>
                <h2>My First Blog Post</h2>
                <p>Welcome to my first blog post! Here, I'll be sharing my thoughts on web development.</p>
            </article>
            <article>
                <h2>Understanding JavaScript</h2>
                <p>JavaScript is a powerful programming language for web development. Let's explore its features...</p>
            </article>
        </section>

        <section id="about">
            <h2>About Me</h2>
            <p>I'm a web development enthusiast learning to create beautiful websites with HTML, CSS, and JavaScript!</p>
        </section>

        <section id="contact">
            <h2>Contact</h2>
            <p>Email me at: <a href="mailto:email@example.com">email@example.com</a></p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 My Blog | Designed by Me</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: white;
    padding: 10px;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

/* Main Content Styles */
main {
    padding: 20px;
}

article {
    background-color: #f9f9f9;
    margin-bottom: 20px;
    padding: 20px;
    border-radius: 8px;
}

article h2 {
    color: #333;
}

/* Footer Styles */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}

/* Media Queries for Responsiveness */
@media (max-width: 600px) {
    nav ul {
        text-align: center;
    }
    
    nav ul li {
        display: block;
        margin-bottom: 10px;
    }
    
    article {
        margin-left: 0;
        margin-right: 0;
    }
}
// script.js

document.addEventListener("DOMContentLoaded", function() {
    const changeColorButton = document.createElement("button");
    changeColorButton.textContent = "Change Background Color";
    document.body.appendChild(changeColorButton);

    changeColorButton.addEventListener("click", function() {
        document.body.style.backgroundColor = document.body.style.backgroundColor === "lightblue" ? "white" : "lightblue";
    });
});


Good luck and happy coding! 🚀💻
