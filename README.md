# Simple Web Interface

## Description

This repository contains a simple web interface built using HTML and CSS. The interface includes basic features such as a header, navigation bar, main content area, and footer.

## Features

- **Header**: The header section contains the title or logo of the website.
- **Navigation Bar**: The navigation bar provides links to different sections or pages of the website.
- **Main Content Area**: This is where the main content of the website is displayed.
- **Footer**: The footer section typically contains copyright information, contact details, and links to social media.

## Usage

### HTML Structure

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Web Interface</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>My Website</h1>
    </header>
    
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <main>
        <section id="home">
            <h2>Welcome to My Website!</h2>
            <p>This is the homepage of my simple web interface.</p>
        </section>
        
        <section id="about">
            <h2>About Us</h2>
            <p>Learn more about our company and mission.</p>
        </section>
        
        <section id="contact">
            <h2>Contact Us</h2>
            <p>Get in touch with us via email or phone.</p>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2024 My Website. All rights reserved.</p>
    </footer>
</body>
</html>
