# Ex.07 Restaurant Website
## Date:22/4/2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Lemon</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Logo and Navigation -->
    <header>
        <div class="logo">
            <img src="logo.jpeg" alt="Little Lemon Logo">
            <h1>Little Lemon</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Menu</a></li>
                <li><a href="#">Administration</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="overlay-text">
            <h2>30% Off This Weekend</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer pulvinar tempus quam.</p>
        </div>
        <img src="pasta.jpg" alt="Pasta Dish">
    </section>

    <!-- Features Section -->
    <section class="features">
        <div class="feature-card">
            <h3>Our New Menu</h3>
            <img src="asd/restapp/Screenshot 2025-04-23 003023.png" alt="Grilled Dish">
            <h1>"Farm-fresh veggies kissed by the flame".</h1>
            <h1>The aroma of flame-grilled goodness that makes your mouth water.</h1>
        </div>
        <div class="feature-card">
            <h3>Book a table</h3>
            <img src="salad.jpeg" alt="Salad Dish">
            <h1>"A touch of gourmet in every bite." or "Not just a salad, an experience."</h1>
            <h1>Looks as good as it tastes.</h1>
        </div>
        <div class="feature-card">
            <h3>Culinary Team</h3>
            <img src="chef.jpeg" alt="Chef in the Kitchen">
            <h1>Excellence in every bite, thanks to our chef's dedication.</h1>
            <h1>The chef is the creative mastermind behind the menu, designing dishes that showcase skill, innovation, and taste.</h1>
        </div>
    </section>
</body>
</html>

administration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - Multi-cusine restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="rest.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="administration">
        <h1>Meet Our Team</h1>
        <div class="team-grid">
            <div class="team-member">
                <h2>Lavanya</h2>
                <p>General Manager</p>
            </div>
            <div class="team-member">
                <h2>Hema</h2>
                <p>Head Chef</p>
            </div>
            <div class="team-member">
                <h2>Radha</h2>
                <p>Operations Manager</p>
            </div>
            <div class="team-member">
                <h2>Mohan</h2>
                <p>Marketing Manager</p>
            </div>
            <div class="team-member">
                <h2>Anu</h2>
                <p>HR Manager</p>
            </div>
            <div class="team-member">
                <h2>Raji</h2>
                <p>Head Waiter</p>
            </div>
        </div>
    </section>

    <footer>
        <p>Designed by RITHIKA K</p>
    </footer>
</body>
</html>
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - multi-cusine restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="rest.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="menu">
        <h1>Our Menu</h1>
        <div class="menu-grid">
            <div class="menu-item">
                <h2>Chicken Biryani</h2>
                <p>south asian mixed rice dish made with marinated chicken,basmati rice,and a blen of aromatic spices</p>
                <p class="price">rs.250</p>
            </div>
            <div class="menu-item">
                <h2>Panipuri</h2>
                <p>A flavorful explosion of crispy puris,tangy tamarid water,and spicy chutneys</p>
                <p class="price">rs.50</p>
            </div>
            <div class="menu-item">
                <h2>Parota with chicken</h2>
                <p>soft,flaky parotas served with tender chicken cooked in a rich,soicy gravy</p>
                <p class="price">rs.100</p>
            </div>
            <div class="menu-item">
                <h2>Pasta</h2>
                <p>class="rich and creamy fettucine padta tossed in a parmesan sauce</p> 
                <p class="price">rs.150</p>
            </div>
            <div class="menu-item">
                <h2>Chicken Nuggets</h2>
                <p>Chicken nuggets are a popular fast food item that are made from small pieces of deboned chicken that are battered </p>
                <p class="price">rs.200</p>
            </div>
            <div class="menu-item">
                <h2>Pulihora</h2>
                <p>A tangy and savory rice dish, infused with the flavors of tamarind, turmeric, and coriander.</p>
                <p class="price">rs.200</p>
            </div>
        <div class="menu-item">
            <h2>Masala dosa</h2>
            <p> A flavorful and crispy dosa filled with aromatic spiced potatoes, served with coconut chutney and sambar."</p>
            <p class="price">rs.70</p>
        </div>
        <div class="menu-item">
            <h2> Mamos</h2>
            <p>A selection of pasta, served with a variety of chutneys and sauces."</p>
            <p class="price">rs.120</p>
        </div>
        <div class="menu-item">
            <h2>Mamos</h2>
            <p>A selection of steamed and pan-fried momos, served with a variety of chutneys and sauces."</p>
            <p class="price">rs.170</p>
        </div>
        <div class="menu-item">
            <h2>French Fries</h2>
            <p>crispy golden fries", "thick-cut fries", "shoestring fries", "hand-cut fries", or "classic fries" depending on the style served. </p>
            <p class="price">rs.100</p>
        </div>
        <div class="menu-item">
            <h2>Gobi Munchurian</h2>
            <p>a dish made with fried cauliflower in a spicy, tangy sauce, commonly found in Indian-Chinese cuisine.</p>
            <p class="price">rs.60</p>
        </div>
        <div class="menu-item">
            <h2>Naan Butter</h2>
            <p>"Naan" (a type of Indian flatbread) and "butter chicken" (a creamy, tomato-based chicken curry)</p>
            <p class="price">rs.300</p>
        </div>
    </section>

    <footer>
        <p>Designed by Rithika</p>
    </footer>
</body>
</html>
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - multi-cusine restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="rest.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="contact">
        <h1>Contact Us</h1>
        <p>Address: 123 Restaurant St., City, Country</p>
        <p>Phone: +123 456 7890</p>
        <p>Email: contact@restaurant.com</p>
    </section>

    <footer>
        <p>Designed by Rithika k</p>
    </footer>
</body>
</html>
style.css

/* General Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background-color: #f9f9f9;
    color: #333;
}

/* Header Section */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: #222;
    color: #fff;
}

header .logo {
    display: flex;
    align-items: center;
}

header .logo img {
    height: 50px;
    margin-right: 10px;
}

nav ul {
    display: flex;
    list-style: none;
}

nav li {
    margin: 0 15px;
}

nav a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
}

/* Hero Section */
.hero {
    position: relative;
    text-align: center;
    color: #fff;
}

.hero img {
    width: 100%;
    height: auto;
    opacity: 0.8;
}

.overlay-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-size: 2rem;
}

.overlay-text h2 {
    font-size: 3rem;
    font-weight: bold;
}

/* Features Section */
.features {
    display: flex;
    justify-content: space-around;
    margin: 20px 0;
}

.feature-card {
    text-align: center;
    padding: 10px;
    background-color: #fdf0d5;
    border-radius: 10px;
    width: 30%;
}

.feature-card img {
    width: 100%;
    height: auto;
    border-radius: 10px;
}

h3 {
    margin: 10px 0;
    font-size: 1.5rem;
    color: #222;
}
```
## OUTPUT:
![Screenshot 2025-04-23 004011-1](https://github.com/user-attachments/assets/fd272349-4b1a-4c10-a96e-e3418baffd5e)
![Screenshot 2025-04-23 004050](https://github.com/user-attachments/assets/5c5880cb-f822-4268-aba5-3101ef495631)
![Screenshot 2025-04-23 004036-1](https://github.com/user-attachments/assets/60684078-c71a-415c-b135-27994238d9cd)
![Screenshot 2025-04-23 004011-1](https://github.com/user-attachments/assets/53f68f62-51b7-4dee-8803-8465d37f14ca)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
