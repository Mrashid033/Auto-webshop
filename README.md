<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luxe Auto Webshop</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Header -->
    <header>
        <div class="container">
            <h1>Luxe Auto Webshop</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#producten">Producten</a></li>
                    <li><a href="#winkelwagen">Winkelwagen</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Producten sectie -->
    <section id="producten" class="product-section">
        <div class="product-container">
            <div class="product">
                <img src="2e46371b8d5b9b.jpg" alt="Sportwagen">
                <h3>Sportwagen</h3>
                <p>€50,000</p>
                <button class="add-to-cart">Voeg toe aan winkelwagen</button>
            </div>
            <div class="product">
                <img src="auto2.jpg" alt="Auto 2">
                <h3>Luxe Sedan</h3>
                <p>€63,000</p>
                <button class="add-to-cart">Voeg toe aan winkelwagen</button>
            </div>
            <div class="product">
                <img src="auto3.jpg" alt="Auto 3">
                <h3>Sport SUV</h3>
                <p>€70,000</p>
                <button class="add-to-cart">Voeg toe aan winkelwagen</button>
            </div>
        </div>
    </section>

    <!-- Winkelwagen sectie -->
    <section id="winkelwagen" class="cart-section">
        <h2>Winkelwagen</h2>
        <div id="cart-items">
            <p>Geen items in je winkelwagen.</p>
        </div>
        <button id="checkout-button">Afrekenen</button>
    </section>

    <script src="script.js"></script>

</body>
</html>

