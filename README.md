<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trendza Shopping</title>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700&family=Roboto:wght@400;500&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            background-color: #fdfdfd;
            color: #333;
        }
        header {
            font-family: 'Montserrat', sans-serif;
            background-color: #ff6f61;
            color: white;
            text-align: center;
            padding: 25px;
            font-size: 2.2rem;
            letter-spacing: 1px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }
        main {
            max-width: 900px;
            margin: 40px auto;
            background: white;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.08);
        }
        .product-title {
            font-family: 'Montserrat', sans-serif;
            font-size: 1.8rem;
            margin-bottom: 15px;
            text-align: center;
        }
        .product-image img {
            width: 100%;
            max-width: 450px;
            display: block;
            margin: 0 auto 25px auto;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
        }
        .price {
            font-size: 1.6rem;
            font-weight: bold;
            color: #ff6f61;
            text-align: center;
            margin-bottom: 25px;
        }
        .buy-button {
            display: block;
            width: fit-content;
            margin: 0 auto;
            padding: 14px 28px;
            background-color: #ff6f61;
            color: white;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1rem;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.15);
            transition: all 0.3s ease;
        }
        .buy-button:hover {
            background-color: #e85b50;
            transform: scale(1.05);
            box-shadow: 0 6px 16px rgba(0,0,0,0.2);
        }
        .product-details {
            margin-top: 40px;
            padding: 20px;
            background-color: #fafafa;
            border-radius: 10px;
            box-shadow: 0 1px 4px rgba(0,0,0,0.05);
        }
        .product-details h2 {
            font-size: 1.4rem;
            margin-bottom: 15px;
            color: #444;
            font-family: 'Montserrat', sans-serif;
        }
        .product-details ul {
            list-style-type: disc;
            padding-left: 25px;
        }
        .product-details li {
            margin-bottom: 10px;
            line-height: 1.5;
            color: #555;
        }
    </style>
</head>
<body>
    <header>Trendza</header>
    <main>
        <div class="product-title">Topeak JoeBlow Sport III Floor Pump</div>
        <div class="product-image">
            <img src="https://i.postimg.cc/yNWq1MvF/product.jpg" alt="Product Image">
        </div>
        <div class="price">RM 500</div>
        <a href="#" class="buy-button">Buy Now</a>
        <div class="product-details">
            <h2>Product Details</h2>
            <ul>
                <li>High-efficiency floor pump suitable for all types of bicycles</li>
                <li>Pressure gauge with accurate readings up to 160 psi</li>
                <li>Durable steel barrel construction</li>
                <li>Ergonomic dual-density handle for comfort</li>
                <li>Includes Presta and Schrader valve compatible head</li>
            </ul>
        </div>
    </main>
</body>
</html>
