<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Churros & Co. </title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #6B4F31; /* Coffee brown color */
            color: white;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        nav {
            background-color: #333;
            overflow: hidden;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            float: left;
            text-align: center;
        }
        nav a:hover {
            background-color: #575757;
        }
        main {
            padding: 20px;
        }
        section {
            background: white;
            margin-bottom: 20px;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #6B4F31;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
        }
        table, th, td {
            border: 1px solid #ddd;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
        .menu-item img {
            max-width: 100px;
            margin-right: 15px;
            border-radius: 8px;
        }
        .menu-item {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 8px;
            transition: background-color 0.3s ease;
        }
        .menu-item:hover {
            background-color: #f1f1f1;
        }
        .menu-item-description {
            flex-grow: 1;
        }
        form input, form textarea, form button {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        footer {
            background-color: #6B4F31;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to Churros & Co.</h1>
        <p>Your favorite place for delicious churros and freshly brewed coffee!</p>
    </header>

    <nav>
        <a href="#churros">Churro Varieties</a>
        <a href="#coffee">Coffee Blends</a>
        <a href="#menu">Menu</a>
        <a href="#reservation">Reservation</a>
        <a href="#contact">Contact</a>
    </nav>

    <main>

        <!-- Churro Varieties -->
        <section id="churros">
            <h2>Churro Varieties</h2>
            <p>We offer a wide variety of churros to satisfy every taste. Whether you prefer classic cinnamon sugar or something more adventurous, we have something for everyone!</p>
            <div class="menu-item">
                <img src="images/Cinnamon-Sugar-Churros.jpg" alt="Cinnamon Sugar Churro">
                <div class="menu-item-description">
                    <h3>Cinnamon Sugar Churros</h3>
                    <p>The classic churro, crispy on the outside and soft on the inside, coated in cinnamon sugar.</p>
                </div>
                <span>$2.50</span>
            </div>
            <div class="menu-item">
                <img src="images/Chocolate-Filled-Churros.jpg" alt="Chocolate-Filled Churro">
                <div class="menu-item-description">
                    <h3>Chocolate-Filled Churros</h3>
                    <p>Delicious churros filled with rich, molten chocolate. Perfect for those who love a sweet indulgence.</p>
                </div>
                <span>$3.00</span>
            </div>
            <div class="menu-item">
                <img src="images/Caramel-Drizzled-Churros.webp" alt="Caramel Churro">
                <div class="menu-item-description">
                    <h3>Caramel Drizzled Churros</h3>
                    <p>Fresh churros drizzled with a smooth caramel sauce, offering a rich and buttery flavor.</p>
                </div>
                <span>$3.50</span>
            </div>
            <div class="menu-item">
                <img src="images/Matcha-Churros.jpeg" alt="Matcha Churro">
                <div class="menu-item-description">
                    <h3>Matcha Churros</h3>
                    <p>For a unique twist, try our green tea flavored churros. A perfect balance of sweetness and earthiness.</p>
                </div>
                <span>$3.75</span>
            </div>
        </section>

        <!-- Coffee Blends -->
        <section id="coffee">
            <h2>Coffee Blends</h2>
            <p>Our coffee is brewed from the finest beans, ensuring a rich, aromatic experience. Here's a selection of our popular blends:</p>
            <div class="menu-item">
                <img src="images/Espresso.jpg" alt="Espresso">
                <div class="menu-item-description">
                    <h3>Espresso</h3>
                    <p>A strong, concentrated coffee brewed by forcing hot water through finely-ground coffee beans.</p>
                </div>
                <span>$2.00</span>
            </div>
            <div class="menu-item">
                <img src="images/Cappuccino.jpg" alt="Cappuccino">
                <div class="menu-item-description">
                    <h3>Cappuccino</h3>
                    <p>A classic espresso-based drink, topped with steamed milk and foam. Perfect for coffee lovers.</p>
                </div>
                <span>$3.50</span>
            </div>
            <div class="menu-item">
                <img src="images/Vanilla_Latte.jpg" alt="Latte">
                <div class="menu-item-description">
                    <h3>Vanilla Latte</h3>
                    <p>A smooth espresso drink with steamed milk and a touch of vanilla syrup.</p>
                </div>
                <span>$3.75</span>
            </div>
            <div class="menu-item">
                <img src="images/cold-brew.jpg" alt="Cold Brew">
                <div class="menu-item-description">
                    <h3>Cold Brew</h3>
                    <p>Chilled coffee brewed over an extended period for a smooth, less acidic taste.</p>
                </div>
                <span>$3.00</span>
            </div>
        </section>

        <!-- Menu -->
        <section id="menu">
            <h2>Menu & Pricing</h2>
            <table>
                <tr>
                    <th>Item</th>
                    <th>Description</th>
                    <th>Price</th>
                </tr>
                <tr>
                    <td>Cinnamon Sugar Churro</td>
                    <td>Classic churro coated with cinnamon and sugar.</td>
                    <td>$2.50</td>
                </tr>
                <tr>
                    <td>Chocolate-Filled Churro</td>
                    <td>Crispy churro filled with rich chocolate.</td>
                    <td>$3.00</td>
                </tr>
                <tr>
                    <td>Espresso</td>
                    <td>A strong shot of espresso.</td>
                    <td>$2.00</td>
                </tr>
                <tr>
                    <td>Cappuccino</td>
                    <td>Espresso, steamed milk, and foam.</td>
                    <td>$3.50</td>
                </tr>
                <tr>
                    <td>Matcha Churros</td>
                    <td>Green tea flavored churros, crispy and sweet.</td>
                    <td>$3.75</td>
                </tr>
            </table>
        </section>

        <!-- Reservation Form -->
        <section id="reservation">
            <h2>Make a Reservation</h2>
            <form action="#" method="post">
                <label for="name">Your Name:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Your Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="date">Date:</label>
                <input type="date" id="date" name="date" required>
                <label for="time">Time:</label>
                <input type="time" id="time" name="time" required>
                <button type="submit">Book Now</button>
            </form>
        </section>

        <!-- Contact Info -->
        <section id="contact">
            <h2>Contact Us</h2>
            <p>For inquiries or feedback, feel free to reach out:</p>
            <p><strong>Email:</strong> info@churrosandco.com</p>
            <p><strong>Phone:</strong> (123) 456-7890</p>
            <p>Follow us on social media:  
                <a href="#">Instagram</a> | <a href="#">Facebook</a>
            </p>
        </section>

    </main>

    <footer>
        <p>© 2024 Churros & Co. | All Rights Reserved</p>
    </footer>

</body>
</html>
