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

        /* Why Us section */
        .why-us {
            background-color: #f5f5f5;
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
            line-height: 1.6;
            margin-bottom: 40px;
            color: #666;
        }

        .why-us-content {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .why-us-item {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: all 0.3s ease;
        }

        .why-us-item:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
        }

        .why-us-item .icon {
            font-size: 2.5em;
            color: #4CAF50;
            margin-bottom: 15px;
        }

        .why-us-item .text h3 {
            font-size: 1.8em;
            color: #333;
            margin-bottom: 10px;
        }

        .why-us-item .text p {
            font-size: 1.1em;
            color: #666;
            line-height: 1.5;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
            position: relative;
            width: 100%;
        }

        footer p {
            margin: 0;
            font-size: 1.1em;
        }

        .discord-button {
            display: inline-block;
            background-color: #7289da;
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            margin-top: 10px;
            border-radius: 5px;
            font-weight: bold;
            transition: background-color 0.3s ease;
        }

        .discord-button i {
            margin-right: 8px;
        }

        .discord-button:hover {
            background-color: #5b6eae;
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
    <div class="why-us-content">
        <div class="why-us-item">
            <div class="icon">
                <i class="fas fa-lightbulb"></i>
            </div>
            <div class="text">
                <h3>Unique Designs</h3>
                <p>Creative and one-of-a-kind designs that stand out from the crowd.</p>
            </div>
        </div>
        <div class="why-us-item">
            <div class="icon">
                <i class="fas fa-globe"></i>
            </div>
            <div class="text">
                <h3>Sustainable Production</h3>
                <p>We use eco-friendly materials and sustainable production methods.</p>
            </div>
        </div>
        <div class="why-us-item">
            <div class="icon">
                <i class="fas fa-truck"></i>
            </div>
            <div class="text">
                <h3>Fast Shipping</h3>
                <p>Get your orders delivered quickly, with easy returns if needed.</p>
            </div>
        </div>
        <div class="why-us-item">
            <div class="icon">
                <i class="fas fa-palette"></i>
            </div>
            <div class="text">
                <h3>Regular New Designs</h3>
                <p>We release new designs regularly, so there's always something fresh.</p>
            </div>
        </div>
    </div>
</section>

<footer>
    <p>&copy; 2024 Merch Store | All rights reserved</p>
    <a href="https://discord.gg/N8hgGWer2c" class="discord-button">
        <i class="fab fa-discord"></i> Join Our Discord
    </a>
</footer>

</body>

</html>
