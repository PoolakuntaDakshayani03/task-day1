# task-day1
# 🌐 Internship Portal – InternLaunch

This project is a basic **Internship Portal landing page** built using **HTML** and **CSS**. It features a responsive layout, attractive design, and includes a motivational slogan and company branding.

---

## 📌 Objective

The aim of this project is to design a static internship homepage for students looking to find internships and connect with companies. It is designed with a clean user interface and a responsive layout suitable for various screen sizes.

---

## 🏗️ Code Explanation

### 1. `index.html` - Main HTML Structure

This is the primary file containing the structure of the webpage.

#### 📌 Header Section
```html
<header>
  <div class="logo">
    <img src="logo.png" alt="InternLaunch Logo" />
    <span>InternLaunch</span>
  </div>
  <nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">Internships</a></li>
      <li><a href="#">Companies</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>
</header>

Displays the logo and the name InternLaunch

Includes a navigation bar with 4 links: Home, Internships, Companies, Contact


<section class="hero">
  <h1>Intern Today. Lead Tomorrow.</h1>
  <p>Your gateway to real-world experience and career growth.</p>
  <a href="#" class="cta-button">Explore Internships</a>
</section>

Main headline and slogan

Motivational text for students

A Call-To-Action button prompting users to explore internships

<footer>
  <p>Follow us on</p>
  <div class="social-links">
    <a href="#">Twitter</a>
    <a href="#">Instagram</a>
    <a href="#">LinkedIn</a>
  </div>
  <p>&copy; 2025 InternLaunch. All rights reserved.</p>
</footer>

Social media links

Copyright notice



style.css - Custom Styling
This file contains all the visual styling for the website.

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background: linear-gradient(to right, #e0f7fa, #e1bee7);
}

Resets default margins/padding

Applies a gradient background

Sets a clean, readable font family

header {
  display: flex;
  justify-content: space-between;
  background-color: #512da8;
  color: white;
  padding: 1rem 2rem;
}
.logo img {
  height: 40px;
  margin-right: 10px;
}
nav ul {
  display: flex;
  gap: 1rem;
  list-style: none;
}
nav ul li a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

Uses Flexbox for layout

Stylish dark purple header

Interactive hover effects for links


.hero {
  text-align: center;
  background-color: #fff8e1;
  color: #4a148c;
  padding: 4rem 2rem;
}
.cta-button {
  background-color: #7e57c2;
  padding: 0.75rem 1.5rem;
  color: white;
  border-radius: 25px;
  font-weight: bold;
}

Light yellow background

Large fonts and bold colors for engagement

Button stands out with rounded edges and hover effect

@media (max-width: 600px) {
  header {
    flex-direction: column;
    text-align: center;
  }
  nav ul {
    flex-direction: column;
  }
}

Ensures mobile-friendly layout

Header and navigation collapse into a column on small screens

💡 Slogan
"Intern Today. Lead Tomorrow."
Your gateway to real-world experience and career growth.


🚀 Future Improvements
Add internship listings dynamically

Connect to a database or API

Add a registration/login system

Include animations using JavaScript

🙋 Author
Name: Poolakunta Dakshayani

GitHub: 

