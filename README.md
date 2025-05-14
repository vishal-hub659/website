# Ex.07: Restaurant Website
# Date:14.05.2025
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# STEPS:
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
<html>
    <head>
        <title>Sprinkle Restaurant</title>
        <style>
             body{
            background-image: url(restaurant-background.jpg);
            background-repeat: no-repeat;
            background-size: 1550px 850px;
        }    
        #name h1{
            color: #ff0800 ;
            text-shadow: rgb(80, 11, 255);
            position: absolute;
            top: 40px;
            left: 400px;
            font-weight: 300px;
            font-size: 50px;
            letter-spacing: 20px;
            font-family: cursive;
        }
        .navbar{
                top: 150px;
                position: absolute;
                left: 0px;
                width: 1550px;
            }
            .navbar ul {
                text-decoration: none;
                text-align: center;
            }
            .navbar li {   
                display: inline-block;
                text-decoration: none;
                font-size: 50px;
                height: 50px;
                padding-top: 30px;
            }
            .navbar a {
                text-decoration: none;
                padding: 40px 100px;
                color: rgb(255, 247, 0);
            }
            .navbar a:hover {
                color: rgb(0, 0, 0);          
              }
        </style>
    </head>
    <body>
        <div id="name">
            <h1>Sprinkle Restaurant</h1>
        </div>
        <div class="navbar">
            <ul type="none">
                <li><a href="HOME.html" title="Home">Home</a></li>
                <li><a href="MENU.html" title="Menu">Menu</a></li>
                <li><a href="CHEFS.html" title="Chefs">Chefs</a></li>
                <li><a href="Contact us.html"title="About us">About us</a></li>
            </ul>
    </body>
</html>
```
# HOME.html
```
<html>
    <head>
        <title>Welcome to Sprinkle Restaurant</title>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Arima:wght@100..700&family=Knewave&family=Oswald:wght@200..700&family=Pacifico&family=Princess+Sofia&display=swap" rel="stylesheet">
        <style>
            body {
                background-image: url(nwe.avif);
                background-repeat: no-repeat;
                background-size: cover;
                margin: 0;
                padding: 0;
                color: #000000;
                display: flex;
                justify-content: center; /* Centers horizontally */
                align-items: center; /* Centers vertically */
                height: 100vh; /* Full viewport height */
            }

            /* Box moved to the center */
            .container {
                width: 35%;
                height: auto;
                padding: 20px;
                background-color: rgba(193, 193, 193, 0.919); /* Light white background with slight transparency */
                border-radius: 20px;
                box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
                text-align: center;
            }

            #header h1 {
                font-size: 38px;
                color: #333;
                font-family: "Pacifico", cursive;
                margin: 0;
            }

            #header h2 {
                font-size: 40px;
                color: #222;
                font-family: "Princess Sofia", cursive;
                margin-top: 10px;
            }

            #working-hours {
                font-size: 28px;
                font-family: "Arima", sans-serif;
                color: #2C3E50;
                margin: 20px 0 10px;
            }

            #timing {
                font-size: 26px;
                font-family: "Oswald", sans-serif;
                color: #16A085;
                margin-bottom: 15px;
            }

            #tagline {
                font-size: 20px;
                font-family: "Pacifico", cursive;
                color: #7D3C98;
                margin-top: 15px;
            }

            .divider {
                width: 50%;
                height: 3px;
                background-color: #7F8C8D;
                margin: 15px auto;
            }
        </style>
    </head>
    <body>
        <div class="container">
            <div id="header">
                <h1>Welcome To</h1>
                <h2>Sprinkle Restaurant</h2>
            </div>
            <div class="divider"></div>
            <div id="working-hours">
                Delightful Dishes, Every Time!
            </div>
            <div id="timing">
                Serving From: <br> <strong>7 AM to 11 PM</strong>
            </div>
            <div id="tagline">
                "Where Taste Meets Perfection!"
            </div>
        </div>
    </body>
</html>

```
# MENU.html
```
<!DOCTYPE html>
<html>
<head>
    <title>Sprinkle Restaurant Menu</title>
    <style>
        body {
            font-family: "Georgia", serif;
            background-color: #eae7dc;
            color: #333;
            margin: 0;
            padding: 40px;
        }
        .menu-header {
            text-align: center;
            margin-bottom: 60px;
        }
        .menu-header h1 {
            font-size: 80px;
            color: #d35400;
        }
        .menu-header p {
            font-size: 32px;
            color: #555;
        }
        .menu-section {
            margin-bottom: 60px;
        }
        .menu-section h2 {
            font-size: 48px;
            border-bottom: 5px solid #d35400;
            padding-bottom: 15px;
            margin-bottom: 30px;
            color: #2c3e50;
        }
        .menu-item {
            display: flex;
            justify-content: space-between;
            padding: 20px 0;
            border-bottom: 2px solid #ccc;
        }
        .menu-item span {
            font-size: 32px;
        }
        .menu-item .price {
            font-weight: bold;
            color: #2c3e50;
        }
        .menu-item:last-child {
            border-bottom: none;
        }
        .menu-images {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
            gap: 30px;
            margin-top: 60px;
        }
        .menu-images img {
            width: 100%;
            height: auto;
            border-radius: 15px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
        }
    </style>
</head>
<body>
    <div class="menu-header">
        <h1>Sprinkle Restaurant</h1>
        <p>Delightful Cuisine for Every Taste</p>
    </div>

    <div class="menu-section">
        <h2>Appetizers</h2>
        <div class="menu-item">
            <span>Garlic Bread</span>
            <span class="price">₹400</span>
        </div>
        <div class="menu-item">
            <span>Bruschetta</span>
            <span class="price">₹600</span>
        </div>
        <div class="menu-item">
            <span>Caesar Salad</span>
            <span class="price">₹650</span>
        </div>
    </div>

    <div class="menu-section">
        <h2>Main Courses</h2>
        <div class="menu-item">
            <span>Grilled Salmon</span>
            <span class="price">₹1450</span>
        </div>
        <div class="menu-item">
            <span>Ribeye Steak</span>
            <span class="price">₹2000</span>
        </div>
        <div class="menu-item">
            <span>Vegetable Stir-fry</span>
            <span class="price">₹1100</span>
        </div>
    </div>

    <div class="menu-section">
        <h2>Fast Foods</h2>
        <div class="menu-item">
            <span>Burger</span>
            <span class="price">₹250</span>
        </div>
        <div class="menu-item">
            <span>Pizza (Medium)</span>
            <span class="price">₹700</span>
        </div>
        <div class="menu-item">
            <span>French Fries</span>
            <span class="price">₹150</span>
        </div>
        <div class="menu-item">
            <span>Hot Dog</span>
            <span class="price">₹200</span>
        </div>
    </div>

    <div class="menu-section">
        <h2>Junk Foods</h2>
        <div class="menu-item">
            <span>Nachos</span>
            <span class="price">₹300</span>
        </div>
        <div class="menu-item">
            <span>Chicken Wings</span>
            <span class="price">₹500</span>
        </div>
        <div class="menu-item">
            <span>Onion Rings</span>
            <span class="price">₹200</span>
        </div>
        <div class="menu-item">
            <span>Mozzarella Sticks</span>
            <span class="price">₹350</span>
        </div>
    </div>

    <div class="menu-section">
        <h2>Desserts</h2>
        <div class="menu-item">
            <span>Cheesecake</span>
            <span class="price">₹500</span>
        </div>
        <div class="menu-item">
            <span>Chocolate Lava Cake</span>
            <span class="price">₹600</span>
        </div>
        <div class="menu-item">
            <span>Ice Cream Sundae</span>
            <span class="price">₹400</span>
        </div>
    </div>

    <div class="menu-section">
        <h2>Beverages</h2>
        <div class="menu-item">
            <span>Coffee</span>
            <span class="price">₹225</span>
        </div>
        <div class="menu-item">
            <span>Tea</span>
            <span class="price">₹185</span>
        </div>
        <div class="menu-item">
            <span>Fresh Juice</span>
            <span class="price">₹300</span>
        </div>
    </div>

    <div class="menu-images">
        <img src="C:\PRIVATE\Web Application Development\61XhetEHp4L-removebg-preview.png" alt="Dish 1">
        <img src="C:\PRIVATE\Web Application Development\cHJpdmF0ZS9sci9pbWFnZXMvd2Vic2l0ZS8yMDI0LTAyL3Jhd3BpeGVsX29mZmljZV8zMF9hX2RyYXdpbmdfb2ZfYV9idXJnZXJfaW5fdGhlX3N0eWxlX29mX2JvbGRfb181NWI2OWI5ZC02YjQ2LTRkZDctYWFlMy0wMDkzOTUwODc5ZDdfMS5wbmc-removebg-pre.png" alt="Dish 2">
        <img src="C:\PRIVATE\Web Application Development\images-removebg-preview.png" alt="Dish 3">
        <img src="C:\PRIVATE\Web Application Development\pink-cake-with-strawberry-the-theme-of-food-and-dessert-isolated-object-transparent-background-ai-generated-free-png.jpg" alt="Dish 4">
    </div>
</body>
</html>

```
# CHEFS.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chefs</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400..700&family=Lora:wght@400..700&display=swap" rel="stylesheet">
    <style>
        body {
            background-color: white;
            background-image: url('chef bg.jpg'); /* Your background image */
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
        }

        /* Sprinkle Restaurant Heading */
        #restaurant-title {
            text-align: center;
            font-size: 60px; /* Larger font for restaurant name */
            color: #2E8B57; /* Greenish color for restaurant */
            font-family: 'Lora', serif;
            margin-top: 60px; /* Increased space from top */
            margin-bottom: 50px; /* Added space below for balance */
        }

        #chefs {
            text-align: center;
            font-size: 48px; /* Slightly smaller font size for section title */
            color: brown;
            margin-top: 40px; /* Increased space between restaurant title and chef heading */
            font-family: "Lora", serif;
        }

        /* Grid Layout */
        .chef-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr); /* 3 columns */
            gap: 40px; /* Increased gap between items */
            margin: 30px 50px; /* Adjusted margin */
        }

        .chef-container {
            display: flex;
            align-items: center;
            justify-content: center;
            border-bottom: 2px solid #ddd;
            padding-bottom: 30px; /* Increased padding */
        }

        .chef-container img {
            width: 250px; /* Increased image width */
            height: auto;
            border-radius: 10px;
            margin-right: 30px; /* Increased margin between image and text */
        }

        .chef-details {
            font-family: 'Courier New', Courier, monospace;
            text-align: left;
        }

        .chef-details h1 {
            font-size: 30px; /* Increased font size for chef name */
            margin: 8px 0; /* Adjusted margin */
        }

        .chef-details h2, .chef-details h3 {
            font-size: 22px; /* Increased font size for passion and experience */
            margin: 6px 0; /* Adjusted margin */
        }

        footer {
            text-align: center;
            margin-top: 40px;
            font-size: 16px; /* Slightly larger footer font */
            color: #888;
        }
    </style>
</head>
<body>
    <!-- Restaurant Title -->
    <div id="restaurant-title">
        <h1>Sprinkle Restaurant</h1>
    </div>

    <div id="chefs">
        <h1>Our Administration and Chefs</h1>
    </div>

    <div class="chef-grid">
        <!-- Chef 1 -->
        <div class="chef-container" id="chef1">
            <img src="chef 1.jpg" alt="Chef VJ">
            <div class="chef-details">
                <h1>Chef VJ</h1>
                <h2>Passion: Head</h2>
                <h3>Experience: 13 years</h3>
            </div>
        </div>

        <!-- Chef 2 -->
        <div class="chef-container" id="chef2">
            <img src="chef 2.jpg" alt="Chef AK">
            <div class="chef-details">
                <h1>Chef AK</h1>
                <h2>Passion: Executive Manager</h2>
                <h3>Experience: 7 years</h3>
            </div>
        </div>

        <!-- Chef 3 -->
        <div class="chef-container" id="chef3">
            <img src="chef 3.jpg" alt="Chef D">
            <div class="chef-details">
                <h1>Chef D</h1>
                <h2>Passion: Saucier Chef</h2>
                <h3>Experience: 8 years</h3>
            </div>
        </div>

        <!-- Chef 4 -->
        <div class="chef-container" id="chef4">
            <img src="chef 4.jpg" alt="Chef MSD">
            <div class="chef-details">
                <h1>Chef MSD</h1>
                <h2>Passion: Pastry Chef</h2>
                <h3>Experience: 7 years</h3>
            </div>
        </div>

        <!-- Chef 5 -->
        <div class="chef-container" id="chef5">
            <img src="chef 5.jpg" alt="Chef Chris">
            <div class="chef-details">
                <h1>Chef Chris</h1>
                <h2>Passion: Pantry Chef</h2>
                <h3>Experience: 4 years</h3>
            </div>
        </div>

        <!-- Chef 6 -->
        <div class="chef-container" id="chef6">
            <img src="Chef6.jpg" alt="Chef Rash">
            <div class="chef-details">
                <h1>Chef Rash</h1>
                <h2>Passion: Butcher Chef</h2>
                <h3>Experience: 4 years</h3>
            </div>
        </div>
    </div>

    <footer>
        <p>© 2024 All Rights Reserved.</p>
    </footer>
</body>
</html>

```
# OUTPUT:


![1 main](https://github.com/user-attachments/assets/1f01ed93-3fa4-418d-8e4e-2331775e77be)


![1 final (2)](https://github.com/user-attachments/assets/773852fa-0cde-460a-a680-969485a1be90)


![2 finalized](https://github.com/user-attachments/assets/f00fd770-7bda-4fe8-b557-c40cd3121671)


![3 finalized](https://github.com/user-attachments/assets/1f4d504d-0cd7-41ea-99e7-779944844aa9)


![4 finalized](https://github.com/user-attachments/assets/5ecabd93-507e-4cce-91b0-05a32ebd6ec2)


# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
