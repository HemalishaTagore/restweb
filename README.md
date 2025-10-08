# Ex.07 Restaurant Website
## Date:08/10/2025

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
home.html
<html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>RESTAURANT</title>
    <link rel="stylesheet" href="home1.css">
</head>
<body>
    <div class="restbg">
        <div class="type">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>

        <div class="title">SOLARA DINE RESTAURANT</div>

        <div class="front">
            <img src="front.jpg" width="650">
        </div>

        <p>SAVOR THE MOMENT</p>
        <div class="text1">
            Life's too short for ordinary meals
        </div>

        <footer>&copy; HEMALISHA T |25017673</footer>
    </div>
</body>
</html>

home1.css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.restbg {
    background-image: url("front.jpg");
    background-size: cover;
    background-position: center;
    min-height: 100vh;
    font-family: Georgia, serif;
}

.type {
    text-align: center;
    padding: 20px;
    font-weight: bold;
    word-spacing: 60px;
}

.type a {
    text-decoration: none;
    color: #ebcd95;
    font-size: 18px;
}

.title {
    color: #ebcd95;
    width: fit-content;
    margin: 1.5cm auto;
    padding: 10px 30px;
    font-size: 45px;
    border-radius: 10px;
    font-size: 97px;
}

.img1 {
    text-align: center;
}

p {
    color:#ebcd95;
    font-weight: bold;
    text-align: center;
    margin: 10px auto;
    width: fit-content;
    padding: 8px 20px;
    border-radius: 10px;
}

.text1 {
    color:#ebcd95;
    font-weight: bold;
    text-align: center;
    width: fit-content;
    margin: 10px auto;
    padding: 8px 20px;
    border-radius: 10px;
}

footer {
    text-align: center;
    padding: 10px;
    position: relative;
    margin-top: 40px;
    color: #ebcd95;
}
menu.html
<!DOCTYPE html>
<html>
    <head>
        <title>Solara | Menu</title>
        <link rel="stylesheet" href="menu1.css">
    </head>
    <body>
        <div class="background">
            <div class="contents">
                <a href="home.html">HOME</a>
                <a href="menu.html">MENU</a>
                <a href="admin.html">ADMIN</a>
                <a href="contact.html">CONTACT</a>
            </div>

            <div class="menu">
                <h1><b>MENU</b></h1>
            </div>

            <div class="menugrid">
                <div class="menuitem">
                    <img src="Solara Caesar.jpg" alt="Solara Caesar">
                    <h1>Solara Caesar</h1>
                    <p>₹320</p>
                </div>

                <div class="menuitem">
                    <img src="Citrus Quinoa Salad.jpg" alt="Citrus Quinoa Salad">
                    <h1>Citrus Quinoa Salad</h1>
                    <p>₹350</p>
                </div>

                <div class="menuitem">
                    <img src="Sun-kissed Lava Cake.jpg" alt="Sun-kissed Lava Cake">
                    <h1>Sun-kissed Lava Cake</h1>
                    <p>₹280</p>
                </div>

                <div class="menuitem">
                    <img src="trophical fruit tart.jpg" alt="Tropical Fruit Tart">
                    <h1>Tropical Fruit Tart</h1>
                    <p>₹270</p>
                </div>

                <div class="menuitem">
                    <img src="Golden Lava Cake.jpg" alt="Golden Lava Cake">
                    <h1>Golden Lava Cake</h1>
                    <p>₹300</p>
                </div>

                <div class="menuitem">
                    <img src="Sunrise Bruschetta.jpg" alt="Sunrise Bruschetta">
                    <h1>Sunrise Brusch</h1>
                </div>
                <footer>&copy; HEMALISHA T |25017673</footer>

menu1.css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Georgia', serif;
}

.background {
    background-image: url("all.jpg");
    background-size: cover;
    background-position: center;
    min-height: 100vh;
}

.contents {
    display: flex;
    justify-content: center;
    gap: 25px;
    background-color: rgba(0, 0, 0, 0.6);
    padding: 15px;
}

.contents a {
    color: #ebcd95;
    text-decoration: none;
    font-size: 18px;
    font-weight: bold;
    transition: color 0.3s;
}

.contents a:hover {
    color: white;
}

.menu {
    text-align: center;
    padding: 20px;
}

.menu h1 {
    color: #ebcd95;
    font-size: 40px;
}

.menugrid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 25px;
    justify-items: center;
    padding: 20px;
}

.menuitem {
    background-color: #ebcd95;
    border-radius: 10px;
    text-align: center;
    padding: 15px;
    width: 90%;
    box-shadow: 0 0 10px rgba(0,0,0,0.2);
    transition: transform 0.3s ease;
}

.menuitem:hover {
    transform: scale(1.05);
}

.menuitem img {
    width: 100%;
    height: 150px;
    object-fit: cover;
    border-radius: 10px;
}

.menuitem h1 {
    font-size: 20px;
    margin: 10px 0;
    color: #333;
}

.menuitem p {
    font-size: 16px;
    color: #555;
}

footer {
    color: #ebcd95;
    text-align: center;
    padding: 10px;
    margin-top: 30px;
    background-color: rgba(0, 0, 0, 0.6);
}
contact.html
<html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contact</title>
    <link rel="stylesheet" href="contact1.css">
</head>
<body>
    <div class="restbg">
        <div class="type">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>

        <div class="title">CONTACT US</div>

        <div class="contact">
            <p><strong>Restaurant:</strong>SAVORA DINE RESTAURANT</p>
            <p><strong>Address:</strong> 47 Bay View Avenue, Besant Nagar Beach Road,
Chennai, Tamil Nadu – 600090</p>
            <p><strong>Phone:</strong> +91 6374876341</p>
            <p><strong>Email:</strong> solararestaurant@gmail.com</p>
        </div>

        <footer>&copy; HEMALISHA T | 25017673</footer>
    </div>
</body>
</html>

contact1.css
* { margin: 0; padding: 0; box-sizing: border-box; }

.restbg {
    background-image: url("all.jpg");
    background-size: cover;
    background-position: center;
    min-height: 100vh;
    font-family: Georgia, serif;
}

.type {
    text-align: center;
    padding: 20px;
    font-weight: bold;
    word-spacing: 60px;
}

.type a {
    text-decoration: none;
    color: #ebcd95;
    font-size: 18px;
}

.title {
    text-align: center;
    color: #ebcd95;
    font-size: 40px;
    width: fit-content;
    margin: 20px auto;
    padding: 10px 30px;
    border-radius: 10px;
}

.contact {
    color: #ebcd95;
    padding: 20px;
    margin: 50px auto;
    width: 700px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.3);
    text-align: left;
}

.contact p {
    font-size: 16px;
    margin: 10px 0;
}

footer {
    color: #ebcd95;
    text-align: center;
    padding: 10px;
}
admin.html
<html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Admin</title>
    <link rel="stylesheet" href="admin1.css">
</head>
<body>
    <div class="restbg">
        <div class="type">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>

        <div class="title">OUR ADMINISTRATION TEAM</div>

        <div class="grid">
            <div class="admin"><img src="mine.jpg"><h3>Hemalisha</h3><br>CEO</div>
            <div class="admin"><img src="dharshan raval.jpg"><h3>Marketing Manager</h3></div>
            <div class="admin"><img src="tharun naik.jpg"><h3>HR Manager</h3></div>
            <div class="admin"><img src="zayn malik.jpg"><h3>Excutive chief</h3></div>
            <div class="admin"><img src="vijay.jpg"><h3>Customer Service Manager</h3></div>
        </div>

        <footer>&copy; HEMALISHA T |25017673</footer>
    </div>
</body>
</html>

admin1.css
* { margin: 0; padding: 0; box-sizing: border-box; }

.restbg {
    background-image: url("all.jpg");
    background-size: cover;
    background-position: center;
    min-height: 100vh;
    font-family: Georgia, serif;
}

.type {
    text-align: center;
    padding: 20px;
    font-weight: bold;
    word-spacing: 60px;
}

.type a {
    text-decoration: none;
    color: #ebcd95;
    font-size: 18px;
}

.title {
    text-align: center;
    color: #ebcd95;
    margin: 20px auto;
    padding: 10px 30px;
    border-radius: 10px;
    font-size: 40px;
    width: fit-content;
}

.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 25px;
    padding: 30px;
}

.admin {
    background-color: #ebcd95;
    border-radius: 15px;
    text-align: center;
    padding: 15px;
}

.admin img {
    width: 100%;
    height: 250px;
    object-fit: cover;
    border-radius: 10px;
}

footer {
    color: #ebcd95;
    text-align: center;
    padding: 10px;
}

```


## OUTPUT:


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
