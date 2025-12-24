<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Glow Beauty</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>Glow Beauty</h1>
    <p>Your everyday makeup essentials</p>
</header>

<nav>
    <a href="#products">Products</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</nav>

<section class="hero">
    <h2>Feel Confident. Feel Beautiful.</h2>
    <p>Discover makeup made to shine with you ✨</p>
</section>

<section id="products" class="products">
    <h2>Our Products</h2>

    <div class="product-card">
        <img src="https://via.placeholder.com/200" alt="Lipstick">
        <h3>Matte Lipstick</h3>
        <p>Long-lasting and smooth finish.</p>
    </div>

    <div class="product-card">
        <img src="https://via.placeholder.com/200" alt="Foundation">
        <h3>Liquid Foundation</h3>
        <p>Lightweight and natural look.</p>
    </div>

    <div class="product-card">
        <img src="https://via.placeholder.com/200" alt="Eyeshadow">
        <h3>Eyeshadow Palette</h3>
        <p>Soft colors for every style.</p>
    </div>
</section>

<section id="about" class="about">
    <h2>About Us</h2>
    <p>
        Glow Beauty is all about confidence, creativity, and self-expression.
        Our products are designed for everyday use and all skin types.
    </p>
</section>

<section id="contact" class="contact">
    <h2>Contact</h2>
    <p>Email: hello@glowbeauty.com</p>
</section>

<footer>
    <p>© 2025 Glow Beauty</p>
</footer>

</body>
</html>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #fff5f8;
    color: #333;
}

header {
    background-color: #ffb6c1;
    text-align: center;
    padding: 20px;
}

nav {
    background-color: #ffc0cb;
    display: flex;
    justify-content: center;
    gap: 20px;
    padding: 10px;
}

nav a {
    text-decoration: none;
    color: #333;
    font-weight: bold;
}

.hero {
    text-align: center;
    padding: 40px 20px;
}

.products {
    padding: 40px 20px;
    text-align: center;
}

.product-card {
    display: inline-block;
    background-color: white;
    margin: 15px;
    padding: 15px;
    border-radius: 10px;
    width: 220px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.product-card img {
    width: 100%;
    border-radius: 10px;
}

.about, .contact {
    padding: 40px 20px;
    text-align: center;
}

footer {
    background-color: #ffb6c1;
    text-align: center;
    padding: 10px;
}



