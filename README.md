# Ex02 Commercial Website
## Date:09/03/2026

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
```
<!DOCTYPE html>
<html>
<head>
    <title>Commercial Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>My Commercial Website</h1>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">Products</a>
    <a href="#">Services</a>
    <a href="#">Contact</a>
</nav>

<section class="container">
    <div class="card">
        <h2>Product 1</h2>
         <img src="c:\Users\admin\Downloads\download (2).jpg" alt="Product 1">
        <p>Best quality product for your needs.</p>
    </div>

    <div class="card">
        <h2>Product 2</h2>
        <img src="c:\Users\admin\Downloads\Jhumka's.jpg" alt="Product 2">
        <p>Affordable and reliable solution.</p>
    </div>

    <div class="card">
        <h2>Product 3</h2>
        <img src="c:\Users\admin\Downloads\new collection.jpg" alt="Product 3">
        <p>Premium choice for professionals.</p>
    </div>
</section>

<footer>
    <p>Name: prathikshaa</p>
    <p>Register No: 212224100043</p>
</footer>

</body>
</html>

/* Reset default spacing */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body Styling */
body {
    font-family: Arial, Helvetica, sans-serif;
    background-color: #f4f4f4;
}

/* Header */
header {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 20px;
}

/* Navigation Bar */
nav {
    display: flex;
    justify-content: center;
    background-color: #444;
}

nav a {
    color: white;
    text-decoration: none;
    padding: 15px 20px;
    transition: 0.3s;
}

nav a:hover {
    background-color: #666;
}

/* Hero Section (Optional Banner) */
.hero img {
    width: 100%;
    height: 350px;
    object-fit: cover;
}

/* Product Container using Flexbox */
.container {
    display: flex;
    justify-content: space-evenly;
    flex-wrap: wrap;
    padding: 40px 20px;
    gap: 20px;
}

/* Product Card */
.card {
    background-color: white;
    width: 300px;
    padding: 15px;
    text-align: center;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
    transition: transform 0.3s;
}

.card:hover {
    transform: scale(1.05);
}

/* Image inside Card */
.card img {
    width: 100%;
    height: 200px;   /* Reduced image size */
    object-fit: cover;
    border-radius: 10px;
}

/* Card Heading */
.card h2 {
    margin: 15px 0 10px;
}

/* Card Paragraph */
.card p {
    color: #555;
    font-size: 14px;
}

/* Footer */
footer {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 20px;
    margin-top: 30px;
}
```


## OUTPUT
<img width="1919" height="1081" alt="Screenshot 2026-02-26 114601" src="https://github.com/user-attachments/assets/6372622a-7a37-462a-a863-1ae498a8e150" />


## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
