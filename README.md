<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zhai.in - Luxury Minimalist Streetwear & Accessories</title>
    <style>
        :root {
            --bg-color: #e2e1dd;
            --primary-brown: #533824;
            --accent-gray: #b7b3aa;
            --dark-text: #1a1a1a;
            --white: #ffffff;
        }
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Helvetica Neue', Arial, sans-serif;
        }
        body {
            background-color: var(--bg-color);
            color: var(--dark-text);
            line-height: 1.6;
        }
        header {
            background-color: var(--primary-brown);
            color: var(--white);
            padding: 20px 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        .logo {
            font-size: 28px;
            font-weight: bold;
            letter-spacing: 2px;
        }
        nav a {
            color: var(--bg-color);
            text-decoration: none;
            margin-left: 25px;
            font-size: 15px;
            transition: color 0.3s;
        }
        nav a:hover {
            color: var(--white);
        }
        .hero {
            padding: 80px 20px;
            text-align: center;
            background-color: var(--accent-gray);
            color: var(--primary-brown);
        }
        .hero h1 {
            font-size: 48px;
            margin-bottom: 15px;
            letter-spacing: 1px;
        }
        .hero p {
            font-size: 18px;
            margin-bottom: 30px;
        }
        .btn {
            background-color: var(--primary-brown);
            color: var(--white);
            padding: 12px 30px;
            border: none;
            cursor: pointer;
            font-size: 16px;
            text-decoration: none;
            border-radius: 4px;
            transition: background 0.3s;
        }
        .btn:hover {
            background-color: #3b2719;
        }
        .container {
            max-width: 1200px;
            margin: 40px auto;
            padding: 0 20px;
        }
        .section-title {
            text-align: center;
            font-size: 32px;
            color: var(--primary-brown);
            margin-bottom: 40px;
            letter-spacing: 1px;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }
        .card {
            background: var(--white);
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            transition: transform 0.3s;
        }
        .card:hover {
            transform: translateY(-5px);
        }
        .card-img {
            height: 250px;
            background-color: #dcdad5;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            color: var(--primary-brown);
            font-size: 20px;
        }
        .card-content {
            padding: 20px;
            text-align: center;
        }
        .card-title {
            font-size: 20px;
            margin-bottom: 10px;
            color: var(--primary-brown);
        }
        .card-price {
            font-size: 18px;
            color: #444;
            margin-bottom: 15px;
            font-weight: bold;
        }
        footer {
            background-color: var(--primary-brown);
            color: var(--white);
            text-align: center;
            padding: 40px 20px;
            margin-top: 60px;
        }
        footer p {
            margin-bottom: 10px;
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">Zhai.in</div>
        <nav>
            <a href="#products">Collection</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="hero">
        <h1>Elevate Your Everyday Style</h1>
        <p>Discover minimalist luxury streetwear, watches, and accessories by Zhai.in</p>
        <a href="#products" class="btn">Explore Collection</a>
    </section>

    <div class="container" id="products">
        <h2 class="section-title">Our Exclusive Products</h2>
        <div class="grid">
            <div class="card">
                <div class="card-img">Tshirt</div>
                <div class="card-content">
                    <div class="card-title">Zhai Oversized T-Shirt</div>
                    <div class="card-price">₹899</div>
                    <a href="mailto:mrdarshan317@gmail.com?subject=Order for Tshirt" class="btn">Order Now</a>
                </div>
            </div>
            <div class="card">
                <div class="card-img">Watch</div>
                <div class="card-content">
                    <div class="card-title">Zhai Luxury Watch</div>
                    <div class="card-price">₹1,699</div>
                    <a href="mailto:mrdarshan317@gmail.com?subject=Order for Watch" class="btn">Order Now</a>
                </div>
            </div>
            <div class="card">
                <div class="card-img">Chains</div>
                <div class="card-content">
                    <div class="card-title">Zhai Statement Chain</div>
                    <div class="card-price">₹299</div>
                    <a href="mailto:mrdarshan317@gmail.com?subject=Order for Chains" class="btn">Order Now</a>
                </div>
            </div>
            <div class="card">
                <div class="card-img">Caps</div>
                <div class="card-content">
                    <div class="card-title">Zhai Streetwear Cap</div>
                    <div class="card-price">₹349</div>
                    <a href="mailto:mrdarshan317@gmail.com?subject=Order for Caps" class="btn">Order Now</a>
                </div>
            </div>
            <div class="card">
                <div class="card-img">Rings</div>
                <div class="card-content">
                    <div class="card-title">Zhai Minimalist Ring</div>
                    <div class="card-price">₹199</div>
                    <a href="mailto:mrdarshan317@gmail.com?subject=Order for Rings" class="btn">Order Now</a>
                </div>
            </div>
            <div class="card">
                <div class="card-img">Bracelets</div>
                <div class="card-content">
                    <div class="card-title">Zhai Leather Bracelet</div>
                    <div class="card-price">₹249</div>
                    <a href="mailto:mrdarshan317@gmail.com?subject=Order for Bracelets" class="btn">Order Now</a>
                </div>
            </div>
            <div class="card">
                <div class="card-img">Perfume</div>
                <div class="card-content">
                    <div class="card-title">Zhai Amberwood Perfume</div>
                    <div class="card-price">₹999</div>
                    <a href="mailto:mrdarshan317@gmail.com?subject=Order for Perfume" class="btn">Order Now</a>
                </div>
            </div>
        </div>
    </div>

    <footer id="contact">
        <h3>Zhai.in</h3>
        <p>Contact Us: mrdarshan317@gmail.com</p>
        <p>&copy; 2026 Zhai.in. All Rights Reserved.</p>
    </footer>

</body>
</html>
