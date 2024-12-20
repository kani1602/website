# Ex.07 Restaurant Website
# Date:
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Website</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #575757;
        }
        .hero {
            background-image: url('restaurant-hero.jpg');
            background-size: cover;
            background-position: center;
            height: 400px;
            text-align: center;
            color: rgb(179, 59, 59);
            padding: 100px 0;
        }
        .hero h1 {
            font-size: 50px;
            margin: 0;
            color: #e67e22;
        }
        .menu {
            padding: 50px 20px;
            text-align: center;
        }
        .menu h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }
        .menu-item {
            display: inline-block;
            width: 30%;
            margin: 10px;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .menu-item img {
            width: 100%;
            border-radius: 8px;
        }
        .menu-item h3 {
            font-size: 24px;
            margin-top: 10px;
        }
        .menu-item p {
            color:red;
            font-size: 30px;
        }
        .contact {
            background-color: #333;
            color: white;
            padding: 40px;
            text-align: center;
        }
        .contact form {
            max-width: 600px;
            margin: 0 auto;
            background-color: #444;
            padding: 20px;
            border-radius: 8px;
        }
        .contact input,
        .contact textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 20px;
            border: none;
            border-radius: 5px;
            background-color: #fff;
            font-size: 16px;
        }
        .contact button {
            padding: 12px 20px;
            background-color: #e67e22;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 16px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Pizza Plaza</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#menu">Menu</a>
        <a href="#contact">Contact</a>
    </nav>
    <section class="hero" id="home">
        <h1>Welcome to Our Restaurant</h1>
        <p>𝓹𝓲𝔃𝔃𝓪 𝓹𝓵𝓪𝔃𝓪</p>
        <img src="res.1.jpg" style="width: 50%; height: 100%;">
    </section>
    <section class="menu" id="menu">
        <h2>Our Menu</h2>
        <div class="menu-item">
            <img src="1.png" alt="Dish 1">
            <h3>Dish 1</h3>
            <p>Chicken</p>
        </div>
        <div class="menu-item">
            <img src="2.png" alt="Dish 2">
            <h3>Dish 2</h3>
            <p>Panner</p>
        </div>
        <div class="menu-item">
            <img src="7.png" alt="Dish 3">
            <h3>Dish 3</h3>
            <p>Mushroom</p>
        </div>
        <div class="menu-item">
            <img src="4.png" alt="Dish 4">
            <h3>Dish 4</h3>
            <p>Double Cheese</p>
        </div>
        <div class="menu-item">
            <img src="3.png" alt="Dish 5">
            <h3>Dish 5</h3>
            <p>BBQ</p>
        </div>
        <div class="menu-item">
            <img src="5.png" alt="Dish 6">
            <h3>Dish 6</h3>
            <p>Mozzarella</p>
        </div>
        <div class="menu-item">
            <img src="8.png" alt="Dish 7">
            <h3>Dish 7</h3>
            <p>Macaroni</p>
        </div>
        <div class="menu-item">
            <img src="6.png" alt="Dish 8">
            <h3>Dish 8</h3>
            <p>Italian</p>
        </div>
    </section>
    <section class="contact" id="contact">
        <h2>Contact Us</h2>
        <form action="submit-form.php" method="POST">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" rows="4" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2024 Restaurant Name. All Rights Reserved.</p>
    </footer>
</body>
</html>

```

# OUTPUT:
![alt text](<Screenshot 2024-12-21 003815.png>)
![alt text](<Screenshot 2024-12-21 003841.png>)
![alt text](<Screenshot 2024-12-21 004652.png>)
![alt text](<Screenshot 2024-12-21 004707.png>)
![alt text](<Screenshot 2024-12-21 004717.png>)
![alt text](<Screenshot 2024-12-21 004023.png>)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
