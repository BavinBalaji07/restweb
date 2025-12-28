# Ex.06 Restaurant Website
## Date:28-12-2025

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
home

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sunday Samayal</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Sunday Samayal</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <section id="home" class="home">      
        <h1>Welcome to Sunday Samayal</h1>
        <p>Where every wierd combo meets you</p>
    </section>
     <section id="story"class="story">
            <h2>Our Story</h2>
            <p>
               Sunday Samayal was founded by the honoured chancellor Bavin Balaji who started his business carrier in a tea stall.
            </p>
        </section>
    <footer>
        <p>&copy; 2025 Sunday Samayal. All Rights Reserved.</p>
    </footer>
</body>
</html>


contact

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
     <header>
        <h1>Sunday Samayal</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <section id="contact" class="story">
             <h2>People's all time available one and only service</h2>
            <p>We are located at CAPE TOWN,Bermuda.</p>
            <p><strong>Phone:</strong>9600575588</p>
            <p><strong>Email:</strong> reservations@SUNDAYSAMAYAL.com</p>
            <br>
            <p><strong>Hours:</strong></p>
            <p>Monday - Thursday: 8:00 AM - 10:00 PM</p>
            <p>Friday - Sunday: 5:00 PM - 12:00 PM</p>
    </section>
    <footer>
        <p>&copy; 2025 Sunday Samayal. All Rights Reserved.</p>
    </footer>
</body>
</html>



menu

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
    <h1>Sunday Samayal</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <section id="menu" class="story">
        <h2>All time Special</h2>
        <div class="menu">
            <div class="items">
                <h3>Mutton Biryani</h3>
                <img src="mutton.jpg" alt="Muttton Biryani" align="center">
                         </div>
            <div class="items">
                <h3>Mutton Sukka </h3>
                <img src="sukka.jpg" alt="Mutton Sukka" align="center">
                
            </div>
            <div class="items">
                <h3>Mutton Kebab</h3>
                <img src="kebab.jpg" alt="Mutton Kebab" align="center">
                
            </div>
            <div class="items">
                <h3>Mutton Ghee Roast</h3>
                <img src="roast.jpg" alt="Mutton Ghee Roast" align="center">
                
            </div>
            <div class="items">
                <h3>Mutton Mandi Set</h3>
                <img src="mandi.jpg" alt="Special Mandi" align="center">
                
            </div>
            <div class="items">
                <h3>Madurai's top class Mutton Dosa</h3>
                <img src="dosa.jpg" alt="Mutton Dosa" align="center">
                
            </div>
            <div class="items">
                <h3>Dindigul Style Biryani(C&M)</h3>
                <img src="dindigul.jpg" alt="Dindigul Thalapakatty Biryani" align="center">
              
            </div>
            <div class="items">
                <h3>Mutton Kola Urundai</h3>
                <img src="kola.jpg" alt="Tasty Meat Balls" align="center">
                
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; 2025 Sunday Samayal. All Rights Reserved.</p>
    </footer>
</body>
</html>


about

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - Sunday Samayal</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
       <h1>Sunday Samayal</h1>
        <nav>
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
    <section id="about">
        <h2>Staff Members</h2>
        <div class="menu">
            <div class="staff">
                <img src="emma.jpeg" alt="Emma Stone - Head Chef" style="width:200px;height:auto;">
                <h3>Emma</h3>
            </div>
            <div class="staff">
                <img src="andrew.jpeg" alt="Andrew Garfield - Co Chef" style="width:200px;height:auto;">
                <h3>Andrew</h3>
            </div>
            <div class="staff">
                <img src="tobey.jpeg" alt="Peter - Restaurant Manager" style="width:200px;height:auto;">
                <h3>Tobey</h3>
            </div>
            <div class="staff">
                 <img src="miles .jpeg" alt="Miles Morales - Curry Specialist" style="width:200px;height:auto;">           
                 <h3>Miles</h3>
                </div>
            <div class="staff">
               <img src="tom.jpeg" alt="Tom - Marketing Specialist" style="width:200px;height:auto;">
                 <h3>Tom</h3>
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; 2025 Sunday Samayal. All Rights Reserved.</p>
    </footer>
</body>
</html>

style.css
body{
            font-family: 'Times New Roman', Times, serif;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
            color: #000000;
        }
        header{
            background-color: #000000;
            color: white;
            font-family: 'brush script mt', cursive;
            font-size: 1.2em;
            padding: 0.1em 2em;
            display: flex;
            position: sticky;
            justify-content: space-between;
            align-items: center;     
        }
        nav ul{
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            gap: 2rem;
        }
        nav a{
            color: white;
            text-decoration: none;
            font-size: 1.5em;
        }
        .home{
            background: url('rest.jpeg') center/cover no-repeat;
            height: 100vh;
            padding: 0.1em 0em;
            text-align: center;
            align-content: center;
            color:#ffffff;
            font-size: 2em;
            font-family:'Playfair Display', serif;
            font-style:italic;
            text-shadow: 2px 2px 6px #000;
        }
        section{
            text-align: center;
            font-size: 1.5em;
            font-family: 'Playfair Display', serif;
            font-style: bold;
            padding: 2em;
        }
        .menu {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 2em;
        }
        .items {
            background-color: #fb5118;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.815);
            padding: 1em;
            width: 250px;
        }
        .items img{
            width: 100%;
            border-radius: 10px;
        }
        .story{
        max-width: 1200px;
        margin: 0 auto;
        padding: 20px;
        }
        .staff{
            background-color: #9f9e9e;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.815);
            padding: 1em;
            width: 250px;
        }
        footer {
        background-color: #000000;
        color: white;
        text-align: center;
        padding: 0.5em;
        }
~~~


## OUTPUT:
![alt text](Bavin/restapp/static/1.png)
![alt text](Bavin/restapp/static/2.png)
![alt text](Bavin/restapp/static/3.png)
![alt text](Bavin/restapp/static/4.png)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
