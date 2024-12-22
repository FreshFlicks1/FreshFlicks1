<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fresh Flicks | Electric Water Flossers</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #333;
            padding: 10px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 16px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .product {
            background: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            padding: 15px;
            text-align: center;
            width: 300px;
        }
        .product img {
            width: 100%;
            height: auto;
            border-bottom: 1px solid #ddd;
            padding-bottom: 15px;
            margin-bottom: 15px;
        }
        .product h3 {
            font-size: 18px;
            margin: 10px 0;
        }
        .product p {
            color: #555;
            font-size: 14px;
            margin: 10px 0;
        }
        .product .price {
            color: #4CAF50;
            font-size: 20px;
            margin: 10px 0;
        }
        .product button {
            background: #4CAF50;
            color: white;
            border: none;
            padding: 10px 15px;
            cursor: pointer;
            border-radius: 5px;
            font-size: 16px;
        }
        .product button:hover {
            background: #45a049;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<header>
    <h1>Fresh Flicks</h1>
    <p>High-Quality Electric Water Flossers for Your Dental Care</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#products">Products</a>
    <a href="#about">About Us</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container">
    <section id="products">
        <h2>Our Products</h2>
        <div class="products">
            <div class="product">
                <img src="water-flosser1.jpg" alt="Water Flosser Model A">
                <h3>Water Flosser Model A</h3>
                <p>Compact and powerful for everyday use.</p>
                <p class="price">$49.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="water-flosser2.jpg" alt="Water Flosser Model B">
                <h3>Water Flosser Model B</h3>
                <p>Advanced settings and higher pressure.</p>
                <p class="price">$69.99</p>
                <button>Add to Cart</button>
            </div>
            <div class="product">
                <img src="water-flosser3.jpg" alt="Water Flosser Model C">
                <h3>Water Flosser Model C</h3>
                <p>Portable design for travel convenience.</p>
                <p class="price">$59.99</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </section>
</div>

<footer>
    <p>&copy; 2024 Fresh Flicks. All rights reserved.</p>
</footer>

</body>
</html>
