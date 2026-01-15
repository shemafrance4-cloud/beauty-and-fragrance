<!DOCTYPE html>
<html lang="en">
<head>[index.html](https://github.com/user-attachments/files/24644182/index.html)

    <meta charset="UTF-8">
    <title>Beauty & Fragrance | Luxury Perfumes</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <nav class="navbar">
        <h1 class="logo">Beauty & Fragrance</h1>
        <ul class="nav-links">
            <li><a href="index.html" class="active">Home</a></li>
            <li><a href="products.html">Products</a></li>
            <li><a href="services.html">Services</a></li>
            <li><a href="about.html">About</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>
</header>

<!-- HERO SECTION -->
<section class="hero">
    <div class="hero-text">
        <h2>Luxury Scents That Define You</h2>
        <p>Discover exclusive perfumes crafted for elegance and confidence.</p>
        <a href="products.html" class="btn">Explore Collection</a>
    </div>
</section>

<!-- HOME PERFUMES SECTION -->
<section class="featured">
    <h2>Featured Perfumes</h2>
    <p class="product-intro">
        Our hand-picked fragrances loved by customers worldwide.
    </p>

    <div class="product-grid">

        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1615634260167-c8cdede054de" alt="Perfume">
            <h3>Crystal Bloom</h3>
            <p class="price">$68.00</p>
            <button onclick="buyProduct('Crystal Bloom', 6800)">Buy Now</button>
        </div>

        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1592945403244-b3fbafd7f539" alt="Perfume">
            <h3>Black Sapphire</h3>
            <p class="price">$82.00</p>
            <button onclick="buyProduct('Black Sapphire', 8200)">Buy Now</button>
        </div>

        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1600185365483-26d7a4cc7519" alt="Perfume">
            <h3>Pure Jasmine</h3>
            <p class="price">$58.00</p>
            <button onclick="buyProduct('Pure Jasmine', 5800)">Buy Now</button>
        </div>

        <div class="product-card">
            <img src="https://images.unsplash.com/photo-1587017539504-67cfbddac569" alt="Perfume">
            <h3>Royal Amber</h3>
            <p class="price">$90.00</p>
            <button onclick="buyProduct('Royal Amber', 9000)">Buy Now</button>
        </div>

    </div>

    <div style="margin-top:40px;">
        <a href="products.html" class="btn">View All Perfumes</a>
    </div>
</section>

<footer>
    <p>© 2026 Beauty & Fragrance | Luxury Perfumes</p>
</footer>

<script src="script.js"></script>
</body>
</html>

