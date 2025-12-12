# fliperin
 e-commerce shop page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fliperin</title>

    <!-- CSS Link -->
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- HEADER -->
    <header>
        <h1>Fliperin</h1>
        <nav>
            <a href="#">Home</a>
            <a href="#products">Products</a>
            <a href="#">Cart</a>
        </nav>
    </header>

    <!-- HERO SECTION -->
    <section class="hero">
        <h2>Welcome to Fliperin</h2>
        <p>Quality products at the best price.</p>
        <button onclick="scrollToProducts()">Shop Now</button>
    </section>

    <!-- PRODUCT SECTION -->
    <section id="products" class="product-section">
        <h2>Our Products</h2>
        <div id="product-list" class="product-list">
            <!-- Products Load Here -->
        </div>
    </section>

    <!-- JS Link -->
    <script src="script.js"></script>
</body>
</html>
