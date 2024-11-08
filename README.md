<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Buy unique t-shirts and sweatshirts from our online store! Our designs are inspired by creativity and style.">
    <title>Merch Store - Unique T-Shirts and Sweatshirts</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

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

        /* About Us Section */
        .about-section {
            display: flex;
            justify-content: space-around;
            padding: 50px 20px;
            background-color: #e4e4e4;
        }

        .about-section div {
            max-width: 45%;
        }

        .about-section h2 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }

        .about-section p {
            font-size: 1.1em;
            line-height: 1.6;
        }

        /* Why Us Section */
        .why-us {
            background-color: #fff;
            padding: 50px 20px;
            text-align: center;
            max-width: 1200px;
            margin: 0 auto;
        }

        .why-us h2 {
            font-size: 2.5em;
            color: #333;
            margin-bottom: 20px;
        }

        .why-us p {
            font-size: 1.2em;
            line-height: 1.8;
            color: #555;
            margin-bottom: 30px;
        }

        /* Why Choose Us List */
        .why-us-list {
            list-style-type: none;
            padding: 0;
            margin: 0;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 40px;  /* Gap between items */
        }

        .why-us-list li {
            font-size: 1.3em;
            color: #444;
            max-width: 250px; /* Control max size for list items */
            text-align: center;
            line-height: 1.6;
        }

        .why-us-list li i {
            font-size: 2em;
            color: #4CAF50;  /* Green icons */
            margin-bottom: 10px;
            display: block;
        }

        /* Products */
        .product-gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            padding: 40px 20px;
        }

        .product-card {
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            text-align: center;
        }

        .product-card img {
            width: 100%;
            height: auto;
        }

        .product-card h3 {
            font-size: 1.8em;
            color: #333;
            margin: 20px 0 10px;
        }

        .product-card p {
            font-size: 1.1em;
            color: #777;
        }

        .product-card .price {
            font-size: 1.5em;
            color: #4CAF50;
            font-weight: bold;
        }

        .product-card .button {
            background-color: #4CAF50;
            color: white;
            text-decoration: none;
            padding: 15px;
            display: inline-block;
            margin: 20px 0;
            border-radius: 5px;
            font-weight: 600;
        }

        .product-card .button:hover {
            background-color: #45a049;
        }

        /* Footer */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px 20px;
            position: fixed;
            width: 100%;
            bottom: 0;
            display: flex;
            justify-content: center; /* Sentraliserer innholdet horisontalt */
            align-items: center; /* Sentraliserer innholdet vertikalt */
            gap: 10px; /* Legger til mellomrom mellom teksten og Discord-knappen */
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

<section id="about" class="about-section">
    <div>
        <h2>About Merch Store</h2>
        <p>Merch Store was founded with one mission: to offer creative and unique designs on t-shirts and sweatshirts for anyone who loves to express themselves through style. We work with talented designers to create products that stand out while using eco-friendly materials and sustainable production methods.</p>
    </div>
    <div>
        <img src="https://via.placeholder.com/500" alt="T-shirt Design" />
    </div>
</section>

<section id="why-us" class="why-us">
    <h2>Why Choose Us?</h2>
    <p>We offer more than just clothes – we offer a way to express yourself. Here are some reasons why you should shop with us:</p>
    <ul class="why-us-list">
        <li><i class="fas fa-lightbulb"></i> Unique and creative designs that no one else has.</li>
        <li><i class="fas fa-globe"></i> Sustainable production with eco-friendly materials.</li>
        <li><i class="fas fa-truck"></i> Fast shipping and easy returns.</li>
        <li><i class="fas fa-palette"></i> New designs are added regularly – always something new to discover!</li>
    </ul>
</section>

<section id="products" class="product-gallery">
    <div class="product-card">
        <img src="https://via.placeholder.com/400x400" alt="Product 1" />
        <h3>Basic T-Shirt</h3>
        <p>A classic t-shirt with a minimalist design.</p>
        <div class="price">199 NOK</div>

        <!-- PayPal button -->
        <div id="paypal-button-container-1"></div>
    </div>

    <div class="product-card">
        <img src="https://via.placeholder.com/400x400" alt="Product 2" />
        <h3>Vintage Sweater</h3>
        <p>A stylish sweater with a retro design.</p>
        <div class="price">399 NOK</div>

        <!-- PayPal button -->
        <div id="paypal-button-container-2"></div>
    </div>

    <div class="product-card">
        <img src="https://via.placeholder.com/400x400" alt="Product 3" />
        <h3>Graphic T-Shirt</h3>
        <p>A striking t-shirt with a graphic print.</p>
        <div class="price">249 NOK</div>

        <!-- PayPal button -->
        <div id="paypal-button-container-3"></div>
    </div>

    <div class="product-card">
        <img src="https://via.placeholder.com/400x400" alt="Product 4" />
        <h3>Hoodie</h3>
        <p>Cozy hoodie with a cool graphic design.</p>
        <div class="price">399 NOK</div>

        <!-- PayPal button -->
        <div id="paypal-button-container-4"></div>
    </div>
</section>

<footer>
    <p>&copy; 2024 Merch Store | All rights reserved</p>
    <a href="https://discord.com" class="discord-button"><i class="fab fa-discord"></i> Join Our Discord</a>
</footer>

<script>
    // Function to render PayPal buttons
    function renderPaypalButton(productId, price) {
        paypal.Buttons({
            createOrder: function(data, actions) {
                return actions.order.create({
                    purchase_units: [{
                        amount: {
                            value: price
                        }
                    }]
                });
            },
            onApprove: function(data, actions) {
                return actions.order.capture().then(function(details) {
                    alert('Payment was successful, ' + details.payer.name.given_name);
                });
            },
            onError: function(err) {
                alert('Something went wrong. Please try again later.');
            }
        }).render('#paypal-button-container-' + productId);  // Button placement
    }

    // Run the function when the document is loaded
    document.addEventListener('DOMContentLoaded', function() {
        renderPaypalButton(1, '199.00');
        renderPaypalButton(2, '399.00');
        renderPaypalButton(3, '249.00');
        renderPaypalButton(4, '399.00');
    });
</script>

</body>

</html>
