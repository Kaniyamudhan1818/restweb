# Ex.07 Restaurant Website
## Date:15.05.2025

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
~~~
restweb.html

<!-- Save this file as index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Name</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #08325b;
            color: #333;
        }
        header {
            background-color: #0f4d7d;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
            display: block;
        }
        nav a:hover {
            background-color: #0a3979;
        }
        .banner {
            background-color:#093462;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 2em;
            text-shadow: 2px 2px 4px #000;
        }
        .content {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: relative;
        }
    </style>
</head>
<body>
    <header>
        <h1>KANIYAMUDHAN'S RESTAURANT</h1>
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>
    <div class="banner">
        WELCOME TO KANIYAMUDHAN'S RESTAURANT
    </div>
    <div class="content">
        <h2>About Us</h2>
        <p>Welcome to our restaurant! We offer variety of delicious food !!</p>
    </div>
    <footer>
        <p>&copy; 2024 restaurant</p>
    </footer>
</body>
</html>

index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Home</title>
    <style>
        /* Basic Styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #084065;
            color: white;
            text-align: center;
            padding: 20px;
        }

        h1 {
            margin: 0;
        }

        .intro {
            text-align: center;
            margin-top: 20px;
        }

        .intro p {
            font-size: 1.2em;
            color: #0c406e;
        }

        .gallery {
            display: flex;
            justify-content: space-around;
            margin: 20px;
            flex-wrap: wrap;
        }

        .gallery img {
            width: 250px;
            height: 150px;
            object-fit: cover;
            border-radius: 8px;
            margin: 10px;
        }

        footer {
            background-color: #0e3f71;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>KANIYAMUDHAN'S RESTAURANT</h1>
        <p>Delicious Food, Amazing Atmosphere</p>
    </header>

    <div class="intro">
        <h2>Our Best Dishes</h2>
        <p>Take a look at some of our most popular dishes!</p>
    </div>

    <div class="gallery">
        <!-- Image 1 -->
        <img src="ab.jpg" alt="SPECIAL AMBUR BIRIYANI">
        <!-- Image 2 -->
        <img src="fal.jpeg" alt="FALOODA">
        <!-- Image 3 -->
        <img src="cn.jpg" alt="CHICKEN NOODLES">
        <!-- Image 4 -->
        <img src="shaw.jpeg" alt="SHAWARMA">
        <!-- Image 5 -->
        <img src="grill.jpg" alt="GRILLED CHICKEN">
    </div>

    <footer>
        <p>Designed by kaniyamudhan</p>
    </footer>

</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Menu</title>
    <style>
        /* Simple Styling */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #133372;
            color: white;
            text-align: center;
            padding: 20px;
        }

        section {
            padding: 20px;
            margin: 20px;
            background-color: rgb(18, 71, 121);
            border-radius: 8px;
        }

        h2 {
            color: #11467a;
            text-align: center;
        }

        .menu-item {
            display: flex;
            align-items: center;
            margin-bottom:-10px;
            padding: -10px;
            border-bottom: 1px solid #ddd;
        }

        .menu-item:last-child {
            border-bottom: none;
        }

        .menu-item img {
            width: 100px;
            height: 100px;
            margin-right: 20px;
            border-radius: 8px;
        }

        .menu-item h3 {
            margin: 0;
            color: #333;
        }

        .menu-item p {
            margin: 2px;
            color: #777;
        }

        .price {
            font-weight: bold;
            color: #183c84;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>KANIYAMUDHAN'S RESTAURANT- Menu</h1>
    </header>

    <section>
        <h2>Our Menu</h2>
        
        <div class="menu-item">
            <img src="cn.jpg" alt="Chicken noodles">
            <div>
                <h3>Chicken noodles</h3>
                <p>Classic chinese chicken noodles with tomato & chilli sauce.</p>
                <span class="price">Rs.120</span>
            </div>
        </div>

        <div class="menu-item">
            <img src="shaw.jpeg" alt="Shawarma">
            <div>
                <h3>Shawarma</h3>
                <p> Juicy Shawarma.</p>
                <span class="price">Rs.90</span>
            </div>
        </div>

        <div class="menu-item">
            <img src="grill.jpg" alt="Grilled Chicken ">
            <div>
                <h3>Grilled chicken</h3>
                <p>Spicy grill with mint chuttney and mayonese </p>
                <span class="price">Rs.440 per kg</span>
            </div>
        </div>

        <div class="menu-item">
            <img src="ab.jpg" alt="Special ambur biriyani">
            <div>
                <h3>Special ambur biriyani</h3>
                <p>Spicy and tasty biriyani</p>
                <span class="price">Rs.150</span>
            </div>
        </div>

        <div class="menu-item">
            <img src="fal.jpeg" alt="Falooda">
            <div>
                <h3>Falooda </h3>
                <p>Chill falooda with fruits.</p>
                <span class="price">Rs.90</span>
            </div>
        </div>

        
    </section>

   

</body>
</html>

admin.html 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Administration</title>
    <style>
        /* Basic Styling */
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #14447c;
            color: white;
            text-align: center;
            padding: 20px;
        }

        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        h2 {
            text-align: center;
            color: #333;
        }

        .admin-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .admin-item {
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 15px;
            width: 200px;
            text-align: center;
            margin: 10px;
        }

        .admin-item img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 10px;
        }

        .admin-item h3 {
            margin: 0;
            color: #333;
        }

        .admin-item p {
            color: #777;
            margin: 5px 0;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Restaurant Administration</h1>
    </header>

    <section>
        <h2>Meet Our Team</h2>

        <div class="admin-list">
            <!-- Admin 1 -->
            <div class="admin-item">
                <img src="siva.jpg" alt="Maniyarasan">
                <h3>Maniyarasan</h3>
                <p>Founder</p>
            </div>

            <!-- Admin 2 -->
            <div class="admin-item">
                <img src="" alt="kaniyamudhan">
                <h3>kaniyamudhan</h3>
                <p>Head Chef</p>
            </div>

            <!-- Admin 3 -->
            <div class="admin-item">
                <img src="akash.jpg" alt="Akash">
                <h3>Akash</h3>
                <p> Manager</p>
            </div>

            <!-- Admin 4 -->
            <div class="admin-item">
                <img src="sach.jpg" alt="hariesh">
                <h3>hariesh</h3>
                <p>Customer Service Lead</p>
            </div>

            <!-- Admin 5 -->
            <div class="admin-item">
                <img src="" alt="sachin">
                <h3>sachin</h3>
                <p> chef</p>
            </div>

           
        </div>

    </section>

    

</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Restaurant</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            color: #333;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #020409;
            color: white;
            text-align: center;
            padding: 20px;
        }

        section {
            padding: 30px;
            margin: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #333;
        }

        p {
            font-size: 1.1em;
        }

        .contact-info {
            margin-top: 20px;
        }

        .contact-info p {
            margin: 10px 0;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .contact-info h3 {
            margin-bottom: 15px;
            color: #02050b;
        }

        a {
            text-decoration: none;
            color: #040b13;
        }
    </style>
</head>
<body>

    <header>
        <h1>KANIYAMUDHAN'S RESTAURANT- Contact Us</h1>
    </header>

    <section>
        <h2>Get in Touch with Us</h2>
        <p>If you have any questions or feedback, we would love to hear from you! Please find our contact details below.</p>

        <div class="contact-info">
            <h3>Restaurant Details:</h3>
            <p><strong>Address:</strong> NO.34/2  OPPOSITE  TO  NOYYAL  HOSTEL , SAVEETHA  UNIVERSITY , CHENNAI</p>
            <p><strong>Phone:</strong> 9876643210,7890664321</p>
            <p><strong>Email:</strong> <a href="mailto:contact@restaurant.com">contact@kaniyamudhan'srestaurant.com</a></p>
        </div>

        <h3>Business Hours:</h3>
        Monday - Friday : 4.00 pm - 12.00 am
~~~    


## OUTPUT:
![image](https://github.com/user-attachments/assets/2a76cdff-ad4d-4817-b9d7-9b40f9928c0d)
![image](https://github.com/user-attachments/assets/36e8a105-a739-4376-b0df-1eebb2dfd9f8)
![image](https://github.com/user-attachments/assets/f6e002e3-aa0b-4f4d-b1bf-60c254db95d9)
![image](https://github.com/user-attachments/assets/2a3f58f8-aee0-47b9-882e-bd7e6e78849f)
![image](https://github.com/user-attachments/assets/61abe7a7-ae29-4d7c-ba32-92e0ec8db949)






## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
