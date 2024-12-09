# Landing-page.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <link rel="stylesheet" href="task1.css">
</head>
<body>
    <header>
        <h1>Welcome to purple</h1>
        <p>Love The Skin You're In</p>
    </header>
    <section id="features">
        <div class="feature">
            <center><img src="c:\Users\golis\Pictures\internship\LEVEL1\images\Care free icons designed by Freepik.jpg"</center>
            <h2>LOYALITY PROGRAMS</h2>
            <p>purplle has a loyality program called "purplle Insider." offering perks like early access to sales. Exclusive discounts and free gifts.</p>
        </div>
        <div class="feature">
            <center><img src="c:\Users\golis\Pictures\internship\LEVEL1\images\products.png"</center>
            <h2>WIDE RANGE OF PRODUCTS</h2>
            <p>purplle offers 30000 products from 650+ brands. Including both indian and international beauty brands.It also provides exclusive budget-friendly brands like Good vibes and NY BAE and many more products</p>
        </div>
        <div class="feature">
            <center><img src="c:\Users\golis\Pictures\internship\LEVEL1\images\packed.jpg"</center>
            <h2>FAST DELIVERY AND GOOD PACKAGING</h2>
            <p>custromers appreciate purplle's prompt delivery services and products are well-packaged. Ensuring saftey during transit</p>
        </div>
    </section>
    <footer>
        <p>&copy; 2024 Your Company. All rights reserved.</p>
    </footer>
</body>
</html>

#Landing-page.css

/* Basic Reset */
body, h1, h2, p {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
}

header {
    background-color: lightcoral;
    color: #fff;
    text-align: center;
    padding: 1em 0;
}

header h1 {
    font-size: 2.5em;
}

header p {
    font-size: 1.2em;
}

section#features {
    display: flex;
    justify-content: space-around;
    padding: 2em;
    background-color: #ebe6e6;
    background-image:url("https://i.pinimg.com/736x/11/9b/8f/119b8fa0d64ea95a7ecd318a6ba1bd44.jpg") ;
    background-position: center;
    
}

.feature {
    flex: 1;
    margin: 0 1em;
    padding: 1em;
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}
img {
    width: 330px;
    height: 225px;
}

.feature h2 {
    text-align: center;
    margin-bottom: 0.5em;
}
.feature p {
    text-align: center;
    font-size: 13px;
    font-weight: 400;
}

footer {
    text-align: center;
    padding: 1em 0;
    background-color: #333;
    color: #fff;
}

