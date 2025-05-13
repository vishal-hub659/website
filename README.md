# Ex.07 Restaurant Website
# Date:13.05.2025
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
home.html

<!DOCTYPE html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Courgette&family=Merienda:wght@300..900&display=swap" rel="stylesheet">
    <title>SRM RESTAURANT</title>
    <style>
        body {
            margin: 0;
            font-family: 'Merienda', cursive;
            background: url('homepage.webp') no-repeat center center fixed;
            background-size: cover;
            color: rgb(234, 245, 16);
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        header {
            text-align: center;
            padding: 50px 20px;
            background: rgba(0, 0, 0, 0.5);
            border-bottom: 2px solid goldenrod;
        }

        header h1 {
            font-size: 80px;
            letter-spacing: 10px;
            margin: 0;
            text-shadow: 2px 2px 8px black;
        }

        nav {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            background: rgba(0, 0, 0, 0.7); 
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.5);
            z-index: 1000;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 10px 20px;
            display: flex;
            justify-content: center;
        }

        nav li {
            margin: 0 20px;
        }

        nav a {
            text-decoration: none;
            color:azure;
            font-size: 18px;
            font-weight: 600;
            padding: 10px 20px;
            border-radius: 5px;
        }

        

        main {
            flex: 1;
            padding: 40px;
            text-align: center;
            background: rgba(255, 255, 255, 0.1); 
            margin: 20px auto;
            max-width: 900px;
            border-radius: 15px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.7);
            animation: fadeInUp 1.5s ease-in-out;
        }

        main p {
            font-size: 24px;
            font-weight: 400;
            line-height: 1.5;
            color:blue;
            text-shadow: 1px 1px 3px black;
        }

        footer {
            background: rgba(0, 0, 0, 0.8); 
            color: white;
            text-align: center;
            padding: 20px 0;
            border-top: 2px solid greenyellow;
            box-shadow: 0 -4px 6px rgba(0, 0, 0, 0.5);
        }

        footer p {
            margin: 5px 0;
            font-size: 16px;
        }

        footer a {
            color: goldenrod;
            text-decoration: none;
            margin: 0 10px;
            font-size: 18px;
            transition: color 0.3s ease-in-out;
        }

        footer a:hover {
            color: #d4af37;
        }

       
    </style>
</head>
<body>
    <header>
        <h1>SRM RESTAURANT!!!!!</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#" title="Home">Home</a></li>
            <li><a href="menu.html" title="menu">menu</a></li>
            <li><a href="admin.html" title="adminis">Administration</a></li>
            <li><a href="contact.html" title="Contact Us">Contact</a></li>
        </ul>
    </nav>
    <main>
        <p>Welcome to SRM Restaurant </p>
        <p>Family Restaurant</p>
    </main>
  
        
        
            
        
</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MENU</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg,yellow, #e0e0e0);
            color: #333;
        }
        header {
            background-color:crimson;
            color: white;
            padding: 20px 0;
            text-align: center;
            box-shadow: rgba(0, 0, 0, 0.3);
        }
        header h1 {
            margin: 0;
            font-size: 48px;
        }
        header p {
            font-size: 18px;
            margin-top: 5px;
            font-weight: lighter;
        }
        .menu-section {
            max-width: 1200px;
            margin: 40px auto;
            padding: 0 20px;
        }
        .menu-section h2 {
            text-align: center;
            margin-bottom: 20px;
            font-size: 32px;
            color: #2a008b;
            border-bottom: 3px solid #ddd;
            display: inline-block;
            padding-bottom: 5px;
        }
        .menu-grid {
            display: flex;
            gap: 30px;
        }
        .menu-item {
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .menu-item:hover {
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.15);
        }
        .menu-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .menu-item h3 {
            margin: 15px 0 10px;
            font-size: 18px;
            color: #333;
        }
        .menu-item p {
            color: #555;
            font-size: 12px;
            margin: 0 10px 15px;
        }
        .menu-item .price {
            font-weight: bold;
            font-size: 15px;
            color: #33008b;
            margin-bottom: 15px;
        }
        footer {
            text-align: center;
            padding: 15px 0;
            background-color: #333;
            color: white;
            margin-top: 40px;
        }
    </style>
</head>
<body>

<header>
    <h1>The yummy food</h1>
    <p>Your favorite spot for authentic non-veg meals</p>
</header>

<div class="menu-section">
    <h2>Chicken</h2>
    <div class="menu-grid">
        <div class="menu-item">
            <img src="c-biryani.jpg" alt="biriyani">
            <h3>biriyani</h3>
            <p>Fragrant rice cooked with chicken, spices, and herbs.</p>
            <div class="price">₹200</div>
        </div>
        <div class="menu-item">
            <img src="chicken.jpg" alt="chicken">
            <h3>chicken</h3>
            <p>Slow-cooked aromatic</p>
            <div class="price">₹250</div>
        </div>
    </div>
</div>

<div class="menu-section">
    <h2>meals</h2>
    <div class="menu-grid">
        <div class="menu-item">
            <img src="meals.jpg" alt="Indian meals">
            <h3>Indian meals</h3>
            <p>white rice with types of sidedish</p>
            <div class="price">₹180</div>
        </div>
    </div>
</div>

<div class="menu-section">
    <h2>Mutton</h2>
    <div class="menu-grid">
        <div class="menu-item">
            <img src="mutton.jpg" alt="mutton">
            <h3>mutton</h3>
            <p>mutton is marinated in flavorful spices.</p>
            <div class="price">₹220</div>
        </div>
        <div class="menu-item">
            <img src="m-briyani.jpg" alt="mutton briyani">
            <h3>mutton briyani</h3>
            <p>Fragrant rice cooked with mutton, spices, and herbs</p>
            <div class="price">₹280</div>
        </div>
    </div>
</div>

<div class="menu-section">
    <h2>sea food</h2>
    <div class="menu-grid">
        <div class="menu-item">
            <img src="seafoods.jpg" alt="seafood">
            <h3>seafood</h3>
            <p>seafood is marinated in flavorful spices.</p>
            <div class="price">₹220</div>
        </div>
        <div class="menu-item">
            <img src="fish.jpg" alt="fish fry">
            <h3>fish fry</h3>
            <p>spicy fish fry</p>
            <div class="price">₹280</div>
        </div>
    </div>
</div>
<div class="menu-section">
    <h2>savorry</h2>
    <div class="menu-grid">
        <div class="menu-item">
            <img src="savoury.jpg" alt="savouries">
            <h3>savouries</h3>
            <p> cooked with spices, and herbs.</p>
            <div class="price">₹180</div>
        </div>
        <div class="menu-item">
            <img src="tea.jpg" alt="tea">
            <h3>tea</h3>
            <p>With aromatic flavorful</p>
            <div class="price">₹35</div>
        </div>
        <div class="menu-item">
            <img src="coffee.jpg" alt="coffee">
            <h3>Coffee</h3>
            <p>With aromatic flavorful</p>
            <div class="price">₹30</div>
        </div>
        <div class="menu-item">
            <img src="cooldrinks.jpg" alt="cooldrinks">
            <h3>Cooldrinks</h3>
            <p>With aromatic flavorful</p>
            <div class="price">₹70</div>
        </div>
    </div>
</div>
<div class="menu-section">
    <h2>Dessert</h2>
    <div class="menu-grid">
        <div class="menu-item">
            <img src="dessert.jpg" alt="Sweets">
            <h3>Sweets</h3>
            <p>flavorful Desserts</p>
            <div class="price">₹150</div>
        </div>
        
    </div>
</div>
<footer>
    <p>&copy; 2024 Delicious Indian Bites. All rights reserved.</p>
</footer>

</body>
</html>

admin.html

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chefs</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Caveat:wght@700&family=Pacifico&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background-color:yellow;
        }

        header {
            text-align: center;
            background-color: #0e6ff5;
            padding: 20px 0;
        }

        header h1 {
            font-family: "Caveat", cursive;
            font-size: 50px;
            color: white;
            margin: 0;
        }


        .chefs-container {
            display: flex;
            gap: 20px;
            padding: 40px;
            margin: auto;
        }

        .chef-card {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            text-align: center;
        }

        .chef-card:hover {
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }

        .chef-card img {
            width: 100%;
            object-fit: contain; 
            max-height: 300px; 
        }

        .chef-details {
            padding: 20px;
        }

        .chef-details h1 {
            font-size: 20px;
            color: rgb(181, 101, 29);
            margin: 10px 0;
        }

        .chef-details h2,
        .chef-details h3 {
            font-size: 16px;
            color: rgb(85, 85, 85);
            margin: 5px 0;
        }

       
        footer {
            text-align: center;
            background-color:aliceblue;
            color:brown;
            padding: 10px 0;
            margin-top: 20px;
        }

        footer p {
            margin: 0;
        }
    </style>
</head>
<body>

  
    <header>
        <h1>Cooking chef</h1>
    </header>

    
    <div class="chefs-container">
        <div class="chef-card">
            <img src="chef_aarthi.jpg" alt="Chef Aarthi">
            <div class="chef-details">
                <h1>Miss Aarthi</h1>
                <h2>Designation: Pastry Chef</h2>
                <h3>Experience: 3 years</h3>
            </div>
        </div>
        
        <div class="chef-card">
            <img src="chef_bhat.jpg" alt="Chef Venkat">
            <div class="chef-details">
                <h1>Mr. Venkat</h1>
                <h2>Designation: Executive Chef</h2>
                <h3>Experience: 7 years</h3>
            </div>
        </div>
        <div class="chef-card">
            <img src="chef_koushik.jpg" alt="Chef koushik">
            <div class="chef-details">
                <h1>Mr. koushik</h1>
                <h2>Designation: Saucier Chef</h2>
                <h3>Experience: 2 years</h3>
            </div>
        </div>
        <div class="chef-card">
            <img src="chef_rangharaj.jpg" alt="Chef Rangharaj">
            <div class="chef-details">
                <h1>Mr M. Rangharaj</h1>
                <h2>Designation: Pastry Chef</h2>
                <h3>Experience: 5 years</h3>
            </div>
        </div>
        <div class="chef-card">
            <img src="chef_cheruba.jpg" alt="Chef Cheruba">
            <div class="chef-details">
                <h1>Miss Cheruba</h1>
                <h2>Designation: Pastry Chef</h2>
                <h3>Experience: 3 years</h3>
            </div>
        </div>
        
        <div class="chef-card">
            <img src="chef_dhamu.jpg" alt="Chef Dhamu">
            <div class="chef-details">
                <h1>Mr. Dhamu</h1>
                <h2>Designation: Sous Chef</h2>
                <h3>Experience: 27 years</h3>
            </div>
        </div>
   </div>
    <footer>
        <p>&copy; 2024 Foodie's Paradise. All rights reserved.</p>
    </footer>

</body>
</html>

contact.html

<html>
    <head>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&display=swap" rel="stylesheet">
        <title>Contact Us</title>
        <style>
            #n1{
                position: relative;
                color:chartreuse;
                font-size: 60px;
                padding-left: 380px;
                left: 0px;
                top: 190px;
                letter-spacing: 5px;
            }
            body{
                background-image: url("homepage.webp");
                background-repeat: no-repeat;
                background-size: 1700px 950px;
            }
            #n2{
                position:relative;
                color: aliceblue;
                font-size: 80px;
                padding-left: 480px;
                top: 140px;
                letter-spacing: 3px;
                font-family: "Dancing Script", cursive;
            }
            #n3{
                position: relative;
                color: aliceblue;
                font-size: 35px;
                top: 255px;
                padding-left: 240px;
            }
            #n4{
                position: relative;
                color:darkmagenta;
                font-size:31px;
                top: 205px;
                padding-left: 170px;
                letter-spacing: 2px;
            }
            #n5{
                position: relative;
                color: aliceblue;
                font-size: 35px;
                top: 60px;
                padding-left: 680px;
            }
            #n6{
                position: relative;
                color:crimson;
                font-size:35px;
                top: 8px;
                padding-left: 505px;
            }
            #n7{
                position: relative;
                color: aliceblue;
                font-size: 35px;
                bottom: 135px;
                padding-left: 1155px;
            }
            #n8{
                position: relative;
                color:darksalmon;
                font-size: 31px;
                bottom: 187px;
                padding-left: 950px;
                text-align: center;
            }

           
            a {
                color:hotpink;
                text-decoration: none;
                cursor: pointer;
            }

      
            a:hover {
                text-decoration: underline;
            }
            
        </style>
    </head>
    <body>
        <h1 id="n1">With Your Love And Kindness</h1>
        <h2 id="n2">Quality and Taste</h2>
        <h5 id="n3">Phone:</h5>
        <h5 id="n4">
            <a href="tel:+915544455444">+91 8877445522</a>
        </h5>
        <h5 id="n5">Email:</h5>
        <h5 id="n6">
            <a href="mailto:srmrestaurant@gmail.com"><b>srmrestaurant@gmail.com</b></a>
        </h5>
        <h5 id="n7">Location:</h5>
        <h5 id="n8">
            <a href="orm restarurant"><b> srm restaurant in chennai-600 035</b></a>
        </h5>
    </body>
</html>
```



# OUTPUT:
![Screenshot 2024-12-14 153031](https://github.com/user-attachments/assets/3cd8c098-98d7-4cd3-929e-9184cb79d75b)

![Screenshot 2024-12-14 153455](https://github.com/user-attachments/assets/76fdb987-e30e-4563-8c94-072d71f94f20)

![Screenshot 2024-12-14 153512](https://github.com/user-attachments/assets/220862b8-e50c-42fe-92d3-5456f46f461b)
![Screenshot 2024-12-14 153542](https://github.com/user-attachments/assets/3b4cec2b-4922-416c-af0a-f91dd67919f0)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
