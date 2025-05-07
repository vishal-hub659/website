# Ex.07 Restaurant Website
# Date:07/05/25
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
    <title>NEON RESTARUANT</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Delicious Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>WELCOME TO NEON RESTAURANT</h1>
        <nav>
            <ul>
                <li><a href="#about">About Us</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="team.html">Team</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    

    <section id="about">
        <h2>About Us</h2>
        <p>Welcome to Neon Restaurant, where we serve the finest dishes made from the freshest ingredients. Our chefs are dedicated to providing you with an unforgettable dining experience.</p>
    </section>
    <div class="image-row">
        <img src="pic1.png" alt="Image 1" width="420" height="250">
        <img src="pic 3.png" alt="Image 2" width="420" height="250">
        <img src="pic2.png" alt="Image 3" width="420" height="250">
    </div>
    

</body>
</html>

menu.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Menu</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Our Menu</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="team.html">Team</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section>
        <div class="menu-grid">
            <div class="menu-item">
                <img src="sandwich.png" alt="Chicken Sandwich" width="150">
                <p>Chicken Sandwich - 149 Rs</p>
            </div>
            <div class="menu-item">
                <img src="soup.png" alt="Tomato Soup" width="150">
                <p>Tomato Soup - 99 Rs</p>
            </div>
            <div class="menu-item">
                <img src="sushi.png" alt="Sushi" width="150">
                <p>Sushi - 399 Rs</p>
            </div>
            <div class="menu-item">
                <img src="burger.png" alt="Cheese Burger" width="150">
                <p>Cheese Burger - 299 Rs</p>
            </div>
            <div class="menu-item">
                <img src="pizza.png" alt="Pizza" width="150">
                <p>Pizza - 499 Rs</p>
            </div>
            <div class="menu-item">
                <img src="fries.png" alt="French Fries" width="150">
                <p>French Fries - 199 Rs</p>
            </div>
            <div class="menu-item">
                <img src="salad.png" alt="Salad" width="150">
                <p>Fresh Salad - 129 Rs</p>
            </div>
            <div class="menu-item">
                <img src="steak.png" alt="Steak" width="150">
                <p>Grilled Steak - 599 Rs</p>
            </div>
            <div class="menu-item">
                <img src="pasta.png" alt="Pasta" width="150">
                <p>Italian Pasta - 299 Rs</p>
            </div>
            <div class="menu-item">
                <img src="desert.png" alt="Dessert" width="150">
                <p>Chocolate Dessert - 199 Rs</p>
            </div>
            <div class="menu-item">
                <img src="icecream.png" alt="Ice Cream" width="150">
                <p>Ice Cream - 99 Rs</p>
            </div>
            <div class="menu-item">
                <img src="coffee.png" alt="Coffee" width="150">
                <p>Hot Coffee - 49 Rs</p>
            </div>
        </div>        
    </section>
</body>
</html>

team.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Team</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Meet Our Team</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section>
        <div class="team">
            <div class="team-member">
                <img src="myphoto.jpeg" alt="Owner" class="team-img">
                <p><b>V Rishon Anand</b></p>
                <p>1 Year of Experience</p>
            </div>
            <div class="team-member">
                <img src="arnold.png" alt="Chef Arnold" class="team-img">
                <p><b>Arnold</b></p>
                <p>Head Chef - Expert in Italian Cuisine</p>
            </div>
            <div class="team-member">
                <img src="chef.png" alt="Chef Johnson" class="team-img">
                <p><b>Dwayne Johnson</b></p>
                <p>Pastry Chef - Creating Delicious Desserts</p>
            </div>
            <div class="team-member">
                <img src="vad.png" alt="Waiter Vadivelu" class="team-img">
                <p><b>Vadivelu</b></p>
                <p>Friendly Waiter - Ensuring the Best Service</p>
            </div>
            <div class="team-member">
                <img src="robert.png" alt="Waiter Vadivelu" class="team-img">
                <p><b>Tony Stark</b></p>
                <p>Waiter - Dedicated to Customer Satisfaction</p>
            </div>
            <div class="team-member">
                <img src="hitler.png" alt="Waiter Vadivelu" class="team-img">
                <p><b>Adolf Hitler</b></p>
                <p>Grill Chef - Master of Barbecue</p>
            </div>
        </div>
    </section>
</body>
</html>

contact.html

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Contact Us</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="team.html">Team</a></li>
            </ul>
        </nav>
    </header>
    <section>
        <p>Email: neonrestaurant@gmail.com</p>
        <p>Phone: (123) 456-7890</p>
        <p>Address: 12345, Saveetha Engineering College, Chennai</p>
    </section>
    
</body>
</html>

styles.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.9;
    font-size: large;
    background-image: url('purple.png');
    background-size: cover; 
    background-position: center;
    background-repeat: no-repeat; 
    height: 100vh;
    color: rgb(248, 246, 246);
}


header {
    background: #ff6347; 
    color: rgb(246, 240, 245);
    padding: 10px 0;
    text-align: center;
    font-style: oblique;
    border-radius: 20px;
}



nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: rgb(15, 14, 14);
    text-decoration: none;
    font-weight: bold;
    font-size: larger;
}

section {
    padding: 20px;
    margin: 30px;
}



footer {
    text-align: center;
    padding: 10px 0;
    background: #88bc19;
    color: rgb(240, 240, 230);
    position: fixed;
    bottom: 0;
    width: 100%;
    

    
}

.menu-grid {
    display: grid;
    grid-template-columns: repeat(6, 1fr); 
    gap: 20px;
    margin: 20px auto;
    text-align: center;
}

.menu-item img {
    width: 150px;
    height: 150px; 
    object-fit: cover; 
    border: 2px solid #fff; 
    border-radius: 5px; 
    display: block; 
    margin: 0 auto; 
}

.menu-item p {
    margin-top: 10px; 
    font-size: 17px; 
    color: #c7ecde; 
    font-weight: 800;
}

.team {
    display: flex;
    justify-content: center;
    flex-wrap: wrap; 
    gap: 75x; 
    margin: 10px auto;
    max-width: 1200px; 
}

.team-member {
    text-align:center;
    width: 200px; 
}

.team-img {
    width: 150px; 
    height: 150px; 
    object-fit: cover; 
    border-radius: 50%;
    margin-bottom: 10px;
}

.team-member p {
    margin: 5px 0;
    font-size: 24px;
    color: #fcf3f3;
}
.image-row {
    display: flex; 
    justify-content: center; 
    gap: 25px;
    margin: 20px 0; 
}

.image-row img {
    border: 6px solid #0a0a0a; 
    border-radius: 20px; 
}
```
# OUTPUT:
![image](https://github.com/user-attachments/assets/59194c42-5e3e-42e3-a2f7-f79d7aacebbd)
![image](https://github.com/user-attachments/assets/18eab89b-a7fe-4737-93ef-4ce53b4e2e25)
![image](https://github.com/user-attachments/assets/2d206896-174a-4b31-b6bd-c82a4b7ebfea)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
