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
            background-color: #f4f4f4;  /* Lys bakgrunn for kontrast */
            padding: 50px 20px;
            text-align: center;
        }

        .why-us h2 {
            font-size: 2.5em;
            color: #333;
            margin-bottom: 20px;
        }

        .why-us p {
            font-size: 1.2em;
            line-height: 1.8;
            margin-bottom: 40px;
            color: #555;
        }

        .why-us-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); /* Responsiv grid */
            gap: 30px;  /* Avstand mellom elementene */
        }

        .why-us-item {
            background-color: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .why-us-item:hover {
            transform: translateY(-10px); /* Liten heving ved hover */
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2); /* Større skygge på hover */
        }

        .why-us-item i {
            font-size: 3em;
            color: #4CAF50;
            margin-bottom: 15px;
        }

        .why-us-item h3 {
            font-size: 1.8em;
            color: #333;
            margin-bottom: 10px;
        }

        .why-us-item p {
            font-size: 1.1em;
            color: #777;
            line-height: 1.5;
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
            padding: 15px 20px;
            position: fixed;
            width: 100%;
            bottom: 0;
            display: flex;
            justify-content: center; /* Sentraliserer innholdet horisontalt */
            align-items: center; /* Sentraliserer innholdet vertikalt */
            gap: 10px; /* Legger til mellomrom mellom teksten og Discord-knappen */
            box-sizing: border-box; /* Sørger for at padding og margin ikke påvirker totalbredde */
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
    <a href="#products">Products</a> <!-- New Products Link -->
</nav>

<section id="about" class="about-section">
    <div>
        <h2>About Merch Store</h2>
        <p>Merch Store was founded with one mission: to offer creative and unique designs on t-shirts and sweatshirts for anyone who loves to express themselves through style. We work with talented designers to create products that stand out while using eco-friendly materials and sustainable production methods.</p>
    </div>
    <div>
        <img src="https://via.placeholder.com/400x400" alt="Merch Store Image">
    </div>
</section>

<section id="why-us" class="why-us">
    <h2>Why Choose Us?</h2>
    <p>We believe that everyone deserves clothing that fits their personality and passion. Here’s why you should choose us for your next purchase:</p>
    <div class="why-us-content">
        <div class="why-us-item">
            <i class="fas fa-tshirt"></i>
            <h3>Unique Designs</h3>
            <p>Our designs are exclusive and created by talented artists.</p>
        </div>
        <div class="why-us-item">
            <i class="fas fa-leaf"></i>
            <h3>Eco-Friendly Materials</h3>
            <p>We use organic and sustainable materials in all our products.</p>
        </div>
        <div class="why-us-item">
            <i class="fas fa-truck"></i>
            <h3>Fast Delivery</h3>
            <p>Get your order quickly, no matter where you are in the world!</p>
        </div>
    </div>
</section>

<section id="products" class="product-gallery">
    <h2>Our Newest Products</h2>
    <p>Check out our latest collection of t-shirts and sweatshirts.</p>

    <div class="product-gallery-grid">
        <div class="product-card">
            <img src="https://via.placeholder.com/400x400" alt="Basic T-Shirt">
            <h3>Basic T-Shirt</h3>
            <p>A classic t-shirt with a minimalist design.</p>
            <div class="price">199 NOK</div>
            <!-- PayPal Button for Basic T-Shirt -->
            <div id="paypal-button-container-basic-tshirt"></div>
            <script>
                paypal.Buttons({
                    createOrder: function(data, actions) {
                        return actions.order.create({
                            purchase_units: [{
                                amount: {
                                    value: '199.00'  // Produktprisen
                                }
                            }]
                        });
                    },
                    onApprove: function(data, actions) {
                        return actions.order.capture().then(function(details) {
                            alert('Takk for at du handlet hos oss, ' + details.payer.name.given_name);
                        });
                    }
                }).render('#paypal-button-container-basic-tshirt');
            </script>
        </div>

        <div class="product-card">
            <img src="https://via.placeholder.com/400x400" alt="Vintage Sweater">
            <h3>Vintage Sweater</h3>
            <p>A stylish sweater with a retro design.</p>
            <div class="price">399 NOK</div>
            <!-- PayPal Button for Vintage Sweater -->
            <div id="paypal-button-container-vintage-sweater"></div>
            <script>
                paypal.Buttons({
                    createOrder: function(data, actions) {
                        return actions.order.create({
                            purchase_units: [{
                                amount: {
                                    value: '399.00'  // Produktprisen
                                }
                            }]
                        });
                    },
                    onApprove: function(data, actions) {
                        return actions.order.capture().then(function(details) {
                            alert('Takk for at du handlet hos oss, ' + details.payer.name.given_name);
                        });
                    }
                }).render('#paypal-button-container-vintage-sweater');
            </script>
        </div>

        <div class="product-card">
            <img src="https://via.placeholder.com/400x400" alt="Graphic T-Shirt">
            <h3>Graphic T-Shirt</h3>
            <p>A striking t-shirt with a graphic print.</p>
            <div class="price">249 NOK</div>
            <!-- PayPal Button for Graphic T-Shirt -->
            <div id="paypal-button-container-graphic-tshirt"></div>
            <script>
                paypal.Buttons({
                    createOrder: function(data, actions) {
                        return actions.order.create({
                            purchase_units: [{
                                amount: {
                                    value: '249.00'  // Produktprisen
                                }
                            }]
                        });
                    },
                    onApprove: function(data, actions) {
                        return actions.order.capture().then(function(details) {
                            alert('Takk for at du handlet hos oss, ' + details.payer.name.given_name);
                        });
                    }
                }).render('#paypal-button-container-graphic-tshirt');
            </script>
        </div>
    </div>
</section>

<footer>
    <p>&copy; 2024 Merch Store. All rights reserved.</p>
    <a href="https://discord.com" target="_blank" class="discord-button"><i class="fab fa-discord"></i> Join our Discord</a>
</footer>

</body>
</html>
