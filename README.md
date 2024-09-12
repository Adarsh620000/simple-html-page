# simple-html-page
Its a simple page of html/css. this project is given by Main flow
Creating this project in different pages by using vs code..
IN html
html.index
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="A simple webpage with semantic HTML structure, styled with CSS for an optimized user experience.">
    <title>Simple Webpage with Semantic HTML</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header role="banner">
        <div class="container1">
            <h1>Welcome to Satyug</h1>
        </div>
    </header>

    <nav aria-label="Main Navigation">
        <div class="container">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </div>
    </nav>

    <main role="main" class="content">
        <section aria-labelledby="about-us">
            <div class="container">
                <p>.</p>
                <h3>RADHE RADHE !!</h3>
                <h4>  .</h4>
                <div class="bigbox">
                    
             <figure> <image  src="https://static.vecteezy.com/system/resources/thumbnails/049/001/826/small/a-person-immersed-in-a-captivating-virtual-reality-world-wearing-advanced-vr-goggles-and-surrounded-by-vibrant-neon-lights-embodying-the-essence-of-modern-gaming-with-cuttingedge-technology-photo.jpg" height="200">
                <figcaption>Modern world!</figcaption>
             </figure>
                <figure>
                    <image src="https://i.pinimg.com/736x/5c/9c/9f/5c9c9f77cc79cc96d6116f531db46729.jpg" height="200">
                    <figcaption>Satyug!</figcaption>
                    </figure>
                        <figure>
                            <image src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSE5E4X0-yFET8GVml2e871dslT2X4OD0xnAkcZO3VJlOpH4vatWinF9QxUB2koHya3VYI&usqp=CAU" height="200">
                       <figcaption>  Satyug!</figcaption>   
                            </figure> 
                            </div>
                <h2 id="about-us">About Us</h2>
                <p style="font-size: 18px;"> <b> Our vision is very clear to make modern world like satguy free of corruption,enemies,stress,headache etc..</b></p>
                <p style="font-size: 14px;">   This webpage is an example of using semantic HTML and CSS to create an accessible and SEO-friendly webpage.</p>
                <p style="font-size: 14px;">   We follow best practices in web development to ensure a consistent and user-friendly experience.</p>
                
            </div>
        </section>
    </main>

    <footer role="contentinfo">
        <div class="container">
            <p>&copy; 2024 My Simple Webpage. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>

In css
styles.css
/* Reset some default browser styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Consistent styling for body text */
body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
    padding: 20px;
}

/* Container for layout consistency */
.container1 {
    max-width: 1100px;
    margin: 0 auto;
    padding: 0 20px;
    color:#f5b505;
    bold;font-weight:
}
.bigbox{
    display:flex;
    justify-content:space-evenly;
    padding-bottom: 0%;
}

/* Header styling */
header {
    background-color: #0f0f10;
    color: white;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    margin: 0;
}

/* Navigation styling */
nav ul {
    list-style: none;
    padding: 10px;
    background-color: #555;
    display:flex;
    justify-content:space-evenly;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s ease;
}

nav ul li a:hover {
    color: #f0c040;
    text-decoration: underline;
}

/* Main content area styling */
main .content {
    margin: 20px 0;
    padding: 20px;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

main h2 {
    color: #333;
    margin-bottom: 10px;
}

main p {
    margin-bottom: 15px;
}
.bigbox
{
    height:400px;
}

/* Footer styling */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
    margin-top: 20px;
    position: relative;
    bottom: 0;
    width: 100%;
}

footer p {
    margin: 0;
}

h3{
    font-size: 25px;
    font-weight: bold;
}

figure{
    font-size:20px;
    text-align: center;
}
