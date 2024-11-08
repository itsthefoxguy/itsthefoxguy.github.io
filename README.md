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
            background-color: #f4f4f4;
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
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); 
            gap: 30px;  
        }

        .why-us-item {
            background-color: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .why-us-item:hover {
            transform: translateY(-10px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
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

        /* Footer Styles */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px 20px;
            width: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 10px;
            box-sizing: border-box;
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

        /* Social Media Buttons */
        .social-button {
            background-color: #3b5998; 
            padding: 10px;
            border-radius: 5px;
            color: white;
            font-size: 1.2em;
            margin: 0 5px;
        }

        .social-button:hover {
            background-color: #2d4373;
        }

        .social-button.twitter {
            background-color: #1da1f2;
        }

        .social-button.twitter:hover {
            background-color: #1991db;
        }

        /* Media Queries for Mobile */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2.5em;
            }

            .product-gallery {
                grid-template-columns: repeat(2, 1fr);
            }

            .why-us-content {
                grid-template-columns: 1fr;
            }
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
        <img src="https://via.placeholder.com/500" alt="Eco-friendly t-shirt design with minimalist artwork" />
    </div>
</section>

<section id="why-us" class="why-us">
    <h2>Why Choose Us?</h2>
    <p>We believe in offering only the best designs, quality, and customer service. Here's why we stand out:</p>
    <div class="why-us-content">
        <div class="why-us-item">
            <i class="fas fa-lightbulb" aria-hidden="true"></i>
            <h3>Unique Designs</h3>
            <p>Our designers craft one-of-a-kind artwork for each product, ensuring you wear something that speaks to your individuality.</p>
        </div>
        <div class="why-us-item">
            <i class="fas fa-recycle" aria-hidden="true"></i>
            <h3>Eco-Friendly Materials</h3>
            <p>We use only the best sustainable fabrics and processes to create our clothing, helping you make a positive impact.</p>
        </div>
        <div class="why-us-item">
            <i class="fas fa-cogs" aria-hidden="true"></i>
            <h3>Quality Craftsmanship</h3>
            <p>Our t-shirts and sweatshirts are made with the highest quality materials and crafted to last.</p>
        </div>
    </div>
</section>

<section id="products">
    <div class="product-gallery">
        <div class="product-card">
            <img src="https://via.placeholder.com/500" alt="Eco-friendly t-shirt design with minimalist artwork" />
            <h3>Minimalist T-Shirt</h3>
            <p>A sleek and stylish t-shirt with a minimalist design that will match any outfit.</p>
            <p class="price">$25.00</p>
            <div id="paypal-button-container"></div>
        </div>
        <div class="product-card">
            <img src="https://via.placeholder.com/500" alt="Comfortable sweatshirt with bold graphic" />
            <h3>Bold Graphic Sweatshirt</h3>
            <p>A comfortable sweatshirt featuring a bold graphic design that makes a statement.</p>
            <p class="price">$35.00</p>
            <div id="paypal-button-container"></div>
        </div>
    </div>
</section>

<footer>
    <p>&copy; 2024 Merch Store | All rights reserved</p>
    <a href="https://discord.gg/N8hgGWer2c" class="discord-button"><i class="fab fa-discord"></i> Join Our Discord</a>
    <a href="https://facebook.com" class="social-button"><i class="fab fa-facebook"></i></a>
    <a href="https://twitter.com" class="social-button twitter"><i class="fab fa-twitter"></i></a>
</footer>

<script>
    // PayPal Button Setup
    paypal.Buttons({
        createOrder: function(data, actions) {
            return actions.order.create({
                purchase_units: [{
                    amount: {
                        value: '25.00'
                    }
                }]
            });
        },
        onApprove: function(data, actions) {
            return actions.order.capture().then(function(details) {
                alert('Payment was successful! Thank you for your purchase, ' + details.payer.name.given_name);
                window.location.href = "/thank-you"; // Redirect to a thank you page after successful payment.
            });
        },
        onError: function(err) {
            alert('An error occurred during the payment process. Please try again or contact support if the problem persists.');
        }
    }).render('#paypal-button-container');
</script>

</body>
</html>
