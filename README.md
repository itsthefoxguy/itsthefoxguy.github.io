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

        /* Introduction and about us */
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

        /* Why Us section */
        .why-us {
            background-color: #fff;
            padding: 50px 20px;
            text-align: center;
        }

        .why-us h2 {
            font-size: 2.5em;
            color: #333;
        }

        .why-us p {
            font-size: 1.2em;
            line-height: 1.8;
            margin: 20px 0;
        }

        .why-us ul {
            list-style-type: none;
            padding: 0;
        }

        .why-us ul li {
            margin-bottom: 15px;
            font-size: 1.2em;
            color: #444;
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
            position: relative; /* Endret fra fixed til relative for bedre layout */
            width: 100%;
            box-sizing: border-box; /* Sørger for at padding ikke ødelegger layouten */
        }

    </style>

    <!-- PayPal SDK -->
    <script src="https://www.paypal.com/sdk/js?client-id=AX9h_vpCyfAeEmRzIVGea-SJmmtvepfZgJgaN9iJGYZ7Yeg6mBSV1CeP-tYDXKkEiFObaLT5lOLuHL_W&components=buttons"></script>

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
    <ul>
        <li>💡 Unique and creative designs that no one else has.</li>
        <li>🌍 Sustainable production with eco-friendly materials.</li>
        <li>🔄 Fast shipping and easy returns.</li>
        <li>🎨 New designs are added regularly – always something new to discover!</li>
    </ul>
</section>

<section id="products" class="product-gallery">
    <!-- Product 1: Basic T-Shirt -->
    <div class="product-card">
        <img src="https://via.placeholder.com/400x400" alt="Product 1" />
        <h3>Basic T-Shirt</h3>
        <p>A classic t-shirt with a minimalist design.</p>
        <div class="price">199 NOK</div>

        <!-- PayPal button -->
        <div id="paypal-button-container-1"></div>
    </div>

    <!-- Product 2: Vintage Sweater -->
    <div class="product-card">
        <img src="https://via.placeholder.com/400x400" alt="Product 2" />
        <h3>Vintage Sweater</h3>
        <p>A stylish sweater with a retro design.</p>
        <div class="price">399 NOK</div>

        <!-- PayPal button -->
        <div id="paypal-button-container-2"></div>
    </div>

    <!-- Product 3: Hettegenser (New) -->
    <div class="product-card">
        <img src="https://via.placeholder.com/400x400" alt="Product 4" />
        <h3>Hettegenser</h3>
        <p>En komfortabel hettegenser med moderne design.</p>
        <div class="price">349 NOK</div>

        <!-- PayPal button -->
        <div id="paypal-button-container-4"></div>
    </div>

    <!-- Product 4: Graphic T-Shirt -->
    <div class="product-card">
        <img src="https://via.placeholder.com/400x400" alt="Product 3" />
        <h3>Graphic T-Shirt</h3>
        <p>A striking t-shirt with a graphic print.</p>
        <div class="price">249 NOK</div>

        <!-- PayPal button -->
        <div id="paypal-button-container-3"></div>
    </div>
</section>

<footer>
    <p>&copy; 2024 Merch Store | All rights reserved</p>
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
        renderPaypalButton(3, '349.00'); // Hettegenser
        renderPaypalButton(4, '249.00');
    });
</script>

</body>

</html>
