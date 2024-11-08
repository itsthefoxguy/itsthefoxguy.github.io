<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Buy unique t-shirts and sweatshirts from our online store! Our designs are inspired by creativity and style.">
    <title>Merch Store - Unique T-Shirts and Sweatshirts</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <!-- Font Awesome for icons -->
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" rel="stylesheet">

    <style>
        /* General styles */
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }

        header {
            background-color: #2d2d2d;
            color: white;
            text-align: center;
            padding: 40px 20px;
        }

        header h1 {
            font-size: 3em;
            margin: 0;
        }

        header p {
            font-size: 1.2em;
            margin-top: 10px;
        }

        /* Navigation menu */
        nav {
            background-color: #333;
            padding: 15px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            padding: 12px 20px;
            margin: 0 15px;
            font-weight: 600;
        }

        nav a:hover {
            background-color: #4CAF50;
            border-radius: 5px;
        }

        /* New Products Section */
        .product-gallery {
            background-color: #f4f4f4;
            padding: 50px 20px;
            text-align: center;
        }

        .product-gallery h2 {
            font-size: 2.5em;
            color: #333;
            margin-bottom: 20px;
        }

        .product-gallery p {
            font-size: 1.2em;
            color: #777;
            margin-bottom: 40px;
        }

        .product-gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(280px, 1fr)); /* Responsiv grid */
            gap: 20px;
        }

        .product-card {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .product-card:hover {
            transform: translateY(-5px); /* Liten heving ved hover */
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2); /* Større skygge på hover */
        }

        .product-card img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }

        .product-card h3 {
            font-size: 1.8em;
            color: #333;
            margin-top: 20px;
        }

        .product-card p {
            font-size: 1.1em;
            color: #777;
            margin-bottom: 15px;
        }

        .product-card .price {
            font-size: 1.4em;
            color: #4CAF50;
            font-weight: bold;
            margin-bottom: 20px;
        }

        .product-card .button {
            background-color: #4CAF50;
            color: white;
            text-decoration: none;
            padding: 15px;
            border-radius: 5px;
            font-weight: 600;
            transition: background-color 0.3s;
        }

        .product-card .button:hover {
            background-color: #45a049;
        }

        /* Footer Styles */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            width: 100%;
            position: relative;
            bottom: 0;
            display: flex;
            flex-direction: column;  /* Legger til vertikal oppstilling */
            justify-content: center; /* Sentraliserer innholdet horisontalt */
            align-items: center; /* Sentraliserer innholdet vertikalt */
            box-sizing: border-box; /* Sørger for at padding ikke påvirker totalbredde */
            margin-top: 40px;
        }

        footer p {
            margin: 0;
            font-size: 1em;
        }

        .discord-button {
            background-color: #7289da;
            color: white;
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
            font-size: 1.2em;
            display: inline-block;
            margin-top: 10px;
        }

        .discord-button:hover {
            background-color: #5b6eae;
        }

        .discord-button i {
            margin-right: 10px;
        }

    </style>
</head>

<body>

<header>
    <h1>Welcome to Merch Store</h1>
    <p>Unique T-Shirts and Sweatshirts for Creative Souls</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#about">About Us</a>
    <a href="#why-us">Why Choose Us?</a>
    <a href="#products">Products</a>
</nav>

<section id="products" class="product-gallery">
    <h2>Our Products</h2>
    <p>Discover our unique collection of t-shirts and sweatshirts, each designed to help you express yourself.</p>
    <div class="product-gallery-grid">
        <!-- Product 1 -->
        <div class="product-card">
            <img src="https://via.placeholder.com/400x400" alt="Basic T-Shirt">
            <h3>Basic T-Shirt</h3>
            <p>A classic t-shirt with a minimalist design.</p>
            <div class="price">199 NOK</div>
            <!-- PayPal Button -->
            <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_blank">
                <input type="hidden" name="cmd" value="_s-xclick">
                <input type="hidden" name="hosted_button_id" value="YOUR_BUTTON_ID">
                <input type="submit" class="button" value="Buy Now">
            </form>
        </div>

        <!-- Product 2 -->
        <div class="product-card">
            <img src="https://via.placeholder.com/400x400" alt="Vintage Sweater">
            <h3>Vintage Sweater</h3>
            <p>A stylish sweater with a retro design.</p>
            <div class="price">399 NOK</div>
            <!-- PayPal Button -->
            <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_blank">
                <input type="hidden" name="cmd" value="_s-xclick">
                <input type="hidden" name="hosted_button_id" value="YOUR_BUTTON_ID">
                <input type="submit" class="button" value="Buy Now">
            </form>
        </div>

        <!-- Product 3 -->
        <div class="product-card">
            <img src="https://via.placeholder.com/400x400" alt="Graphic T-Shirt">
            <h3>Graphic T-Shirt</h3>
            <p>A striking t-shirt with a graphic print.</p>
            <div class="price">249 NOK</div>
            <!-- PayPal Button -->
            <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_blank">
                <input type="hidden" name="cmd" value="_s-xclick">
                <input type="hidden" name="hosted_button_id" value="YOUR_BUTTON_ID">
                <input type="submit" class="button" value="Buy Now">
            </form>
        </div>
    </div>
</section>

<footer>
    <p>&copy; 2024 Merch Store</p>
    <a href="https://discord.com" class="discord-button"><i class="fab fa-discord"></i> Join Our Discord</a>
</footer>

</body>

</html>
