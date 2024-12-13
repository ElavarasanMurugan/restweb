# Ex.07 Restaurant Website
## Date: 13-12-2024

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

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title class="sp">
        Spice Bazaar 🌶️
    </title>
    <link
        href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&family=Roboto:wght@300;400;500&family=Gloock&display=swap"
        rel="stylesheet">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Audiowide|Sofia|Trirong">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link
        href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
        rel="stylesheet">
    <link rel="stylesheet" href="home.css">
</head>

<body>
    <div class="header">
        <div class="logo1">
            <img src="logo.png" class="img">
            <h1 class="spice">Spice Symphony</h1>
        </div>
        <div class="bar">
            <input placeholder="Search">
            <button type="button" id="search">Search
        </div>
    </div>
    <div class="contents">
        <nav class="nav-contents">
            <ul>
                <li><a href="home.html" class="hyper">Home</a></li>
                <li><a href="menu.html" class="hyper">Menu</a></li>
                <li><a href="admin.html" class="hyper">Administration</a></li>               
                <li><a href="contact.html" class="hyper">Contact Us</a></li>
            </ul>
        </nav>
    </div>

    <div class="image">
    </div>
    <div class="box">
    <div class="box2">
        <div class="collections">
        </div>
        <div class="words">
            <h2 class="order">Order Online</h2>
            <p class="good">Cravings delivered to your doorstep—order online now!</p>
        </div>
    </div>
    <div class="box2">
        <div class="collections2">
        </div>
        <div class="words">
            <h2 class="order">Dining</h2>
            <p class="good">Experience flavors worth gathering for—dine with us!x</p>
        </div>
    </div>
    <div class="box2">
        <div class="collections3">
        </div>
        <div class="words">
            <h2 class="order">Reserve a table</h2>
            <p class="good">Reserve your spot today and savor unforgettable moments!</p>
        </div>
    </div>
</div>
    <br><br>
    
    <footer>
        <h2><a href="name" class="terms">Terms and conditions </a> </h2>
        <h2><a href="name" class="terms">Cookie Policy </a> </h2>
        <h2><a href="name" class="terms">Privacy Policy </a></h2>
        <br><br>
        <h2> Copyright &copy; 2024 SPICY SYMPHONY </h2>
    </footer>
</body>


</html>

home.css

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.header {
    background-color:beige;
    padding: 5px 0;
    text-align: center;
    margin-top: -10px;
    display: block;
}

.logo1{
    display: flex;
    justify-content: center;
    align-items: center;
}

.img {
    height: 90px;
    width: auto;
    margin-right: 5px;
}

.spice{
    font-size: 40px;
    font-weight: 700;
    color:#3d2a1f; 
    font-family: Gloock; 
    text-transform: uppercase;
    letter-spacing: 2px;
}
input{
   margin-left: 50px;
    height: 25px;
    width: 300px;
    border-style:dotted;
    border-color:rgb(192, 146, 146);
    background-color: rgb(244, 244, 208);
    border-radius: 5px;
    padding-left: 2px;
}
button{
    margin-right: 3px;

    height: 25px;
    width: 60px;
    border-radius: 4px;
    text-align: center;
    border: none;
    background-color: #387051;
    color: white;
    font-family: Poppins;
    font-weight: 700;
    cursor:pointer;
    letter-spacing: 1px;

}

button:hover{
    color:lavender;
    text-decoration: dashed;
}
.bar{
    margin-bottom: 10px;
    text-align:center;
}

nav{
    color:white ;
    background-color:#705138;
}
li,ul{
    padding: 5px;
    padding-left: 120px;
    padding-right: 100px;
    display: inline-block;
    height: 50px;
    width: auto;
    font-size: 20px;
    font-family: Trirong;
    font-weight: bold;
    letter-spacing: 1px;
    cursor: pointer;
}
.hyper{
    color: white;
    text-decoration: none;
}
a:hover{
    color: burlywood;
}
.image{
    width: auto;
    height: 250px; 
    background-image:url(back.jpg); 
    background-size: cover; 
    background-position: center; 
    border-radius: 15px;
    margin-top: 40px;
    display: flex;
    border: 4px;
    margin-bottom: 40px;
}
.box2{
    border-color:rgb(241, 236, 236);
    border-style: solid;
    display: inline-block;
    margin-left: 180px;
    border-radius: 10px;
}

.collections{
    width: 320px;
    height: 200px; 
    background-image:url(cake.jpeg); 
    background-size:cover; 
    background-position: center; 
    border-radius: 10px;
    display: flex;
    border: 4px;
}
.words
{
    cursor: pointer;
    padding-top: 10px;
    padding-left: 10px;
    font-family: Trirong;
    padding-bottom: 20px;
    text-align: start;
}
.words p.good{
    max-width: 300px;
    white-space: wrap;
}
.box :hover{
    color:#705138;
}
.order{
    font-size: 20px;
}
.good{
    font-size: 15px;
}
.collections2{
    width: 320px;
    height: 200px; 
    background-image:url(table.jpeg); 
    background-size: cover; 
    background-position: center; 
    border-radius: 10px;
    display: flex;
    border: 4px;
}
.collections3{
    width: 320px;
    height: 200px; 
    background-image:url(reserved.jpeg); 
    background-size: cover; 
    background-position: center; 
    border-radius: 10px;
    display: flex;
    border: 4px;
}
footer{
    
    background-color: #705138;
    text-align: center;
    height: 70px;
    width: auto;
    padding-top: 10px;
    font-size: 13px;
    color: lavender;
    font:small-caps
}
h2{
    display: inline;
    margin-right: 50px;
}
.terms
{
    color:aliceblue;
    text-decoration: none;
}
.terms:hover{
    text-decoration: underline;
}


```

```
menu.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title class="sp">
        Spice Bazaar 🌶️
    </title>
    <link
        href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&family=Roboto:wght@300;400;500&family=Gloock&display=swap"
        rel="stylesheet">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Audiowide|Sofia|Trirong">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link
        href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
        rel="stylesheet">
    <link
        href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&family=Montserrat:ital,wght@0,100;1,100&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
        rel="stylesheet">
    <link
        href="https://fonts.googleapis.com/css2?family=Alumni+Sans+Pinstripe:ital@0;1&family=Dancing+Script:wght@400..700&family=Montserrat:ital,wght@0,100;1,100&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
        rel="stylesheet">

    <link rel="stylesheet" href="menu.css">
</head>

<body>
    <div class="header">
        <div class="logo">
            <img src="logo.png"class="img">
            <h1 class="spice">Spice Symphony</h1>
        </div>
        <div class="bar">
            <input placeholder="Search">
            <button type="button" id="search">Search
        </div>
    </div>
    <div class="contents">
        <nav class="nav-contents">
            <ul>
                <li><a href="home.html" class="hyper">Home</a></li>
                <li><a href="menu.html" class="hyper">Menu</a></li>
                <li><a href="admin.html" class="hyper">Administration</a></li>
                <li><a href="contact.html" class="hyper">Contact Us</a></li>
            </ul>
        </nav>
    </div>

    <div class="menus">
        <div class="items1">
        </div>
        <div class="words">
            <h2 class="order">Chicken Briyani</h2>
            <p class="good1">“In every grain of biryani lies a world of flavors, a burst of spices, and a journey into
                culinary bliss.it’s an invitation to savor the essence of tradition with every
                bite.”</p>
        </div>
    </div>
    <div class="menus">
        <div class="items2">
        </div>
        <div class="words">
            <h2 class="order">Sweet Potato Bliss</h2>
            <p class="good2">"Experience the cozy warmth of a baked Japanese sweet potato, paired with the creamy
                sweetness of tonka vanilla ice cream—a perfect blend of flavors."</p>
        </div>
    </div>
    <div class="menus">
        <div class="items3">
        </div>
        <div class="words">
            <h2 class="order">Momos</h2>
            <p class="good3">"Savory, steamed perfection—bite into the tender, juicy flavors of homemade momos, wrapped
                in a delicate dumpling skin."</p>
        </div>
    </div>
    <div class="menus">
        <div class="items4">
        </div>
        <div class="words">
            <h2 class="order1">Pizza</h2>
            <p class="good4">"Discover the ultimate pizza experience with every slice—melty cheese, fresh ingredients, and a perfectly baked crust that’s made to satisfy your every craving!"</p>
        </div>
    </div>
    <div class="menus">
        <div class="items5">
        </div>
        <div class="words">
            <h2 class="order">Spicy Garlic Shrimp Tango</h2>
            <p class="good5">"Savor the succulent taste of shrimp—delicately tender, perfectly seasoned, and a burst of flavor in every bite, leaving you craving for more."</p>
        </div>
    </div>
    <div class="menus">
        <div class="items6">
        </div>
        <div class="words">
            <h2 class="order">Pastalicious Bliss</h2>
            <p class="good6">"Indulge in the magic of pasta—every bite is a journey of flavor, comfort, and joy that brings people together like nothing else!" 🍝</p>
        </div>
    </div>
    <div class="menus">
        <div class="items7">
        </div>
        <div class="words">
            <h2 class="order">Paya Passion</h2>
            <p class="good7">"Experience the rich flavors of mutton paya—tender meat, aromatic spices, and a soul-warming broth that brings comfort in every bite."</p>
        </div>
    </div>
    <footer>
        <h2><a href="name" class="terms">Terms and conditions </a> </h2>
        <h2><a href="name" class="terms">Cookie Policy </a> </h2>
        <h2><a href="name" class="terms">Privacy Policy </a></h2>
        <br><br>
        <h2> Copyright &copy; 2024 SPICY SYMPHONY </h2>
    </footer>
</body>

</html>

menu.css

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.header {
    background-color:beige;
    padding: 5px 0;
    text-align: center;
    margin-top: -10px;
    display: block;
}

.logo {
    display: flex;
    justify-content: center;
    align-items: center;
}

.img {
    height: 90px;
    width: auto;
    margin-right: 5px;
}

.spice{
    font-size: 40px;
    font-weight: 700;
    color:#3d2a1f; 
    font-family: Gloock; 
    text-transform: uppercase;
    letter-spacing: 2px;
}
input{
   margin-left: 50px;
    height: 25px;
    width: 300px;
    border-style:dotted;
    border-color:rgb(192, 146, 146);
    background-color: rgb(244, 244, 208);
    border-radius: 5px;
    padding-left: 2px;
}
button{
    margin-right: 3px;
    height: 25px;
    width: 60px;
    border-radius: 4px;
    text-align: center;
    border: none;
    background-color: #387051;
    color: white;
    font-family: Poppins;
    font-weight: 700;
    cursor:pointer;
    letter-spacing: 1px;

}

button:hover{
    color:lavender;
    text-decoration: dashed;
}
.bar{
    margin-bottom: 10px;
    text-align:center;
}

nav{
    color:white ;
    background-color:#705138;
    margin-bottom: 40px;
}
li,ul{
    padding: 5px;
    padding-left: 120px;
    padding-right: 100px;
    display: inline-block;
    height: 50px;
    width: auto;
    font-size: 20px;
    font-family: Trirong;
    font-weight: bold;
    letter-spacing: 1px;
    cursor: pointer;
}
.hyper{
    color: white;
    text-decoration: none;
}
a:hover{
    color: burlywood;
}

.menus{
    border-color:rgb(241, 236, 236);
    border-style: solid;
    display: inline-block;
    margin-left: 50px;
    border-radius: 10px;
    margin-bottom: 20px;
}

.items1{
    width: 320px;
    height: 200px; 
    background-image:url(chicken\ briyani.jpeg); 
    background-size:cover; 
    background-position: center; 
    border-radius: 10px;
    display: flex;
    border: 4px;
}
.items2{
    width: 320px;
    height: 200px; 
    background-image:url(dessert.jpeg); 
    background-size:cover; 
    background-position: center; 
    border-radius: 10px;
    display: flex;
    border: 4px;
    padding-bottom: 100px;
}
.items3{
    width: 320px;
    height: 200px; 
    background-image:url(momos.jpeg); 
    background-size:cover; 
    background-position: center; 
    border-radius: 10px;
    display: flex;
    border: 4px;
}
.items4{
    width: 320px;
    height: 200px; 
    background-image:url(pizza.jpg); 
    background-size:cover; 
    background-position: center; 
    border-radius: 10px;
    display: flex;
    border: 4px;
}
.items5{
    width: 320px;
    height: 200px; 
    background-image:url(shrimp.jpeg); 
    background-size:cover; 
    background-position: center; 
    border-radius: 10px;
    display: flex;
    border: 4px;
}
.items6{
    width: 320px;
    height: 200px; 
    background-image:url(chinese.jpg); 
    background-size:cover; 
    background-position: center; 
    border-radius: 10px;
    display: flex;
    border: 4px;
}
.items7{
    width: 320px;
    height: 200px; 
    background-image:url(paya.jpeg); 
    background-size:cover; 
    background-position: center; 
    border-radius: 10px;
    display: flex;
    border: 4px;
}
.words
{
    padding-top: 10px;
    padding-left: 10px;
    font-family: Trirong;
    padding-bottom: 20px;
    text-align: start;
}
.words:hover{
    cursor: pointer;
    color:darkcyan;
}
.order{
    font-size: 20px;
}
.order1{
    font-size: 20px;
}
.words p.good1{
    max-width: 310px;
    font-size: 15px;
}
.words p.good2{
    max-width: 300px;
    font-size: 15px;
}
.words p.good3{
    max-width: 300px;
    font-size: 15px;
}
.words p.good4{
    white-space:pre wrap;
    max-width: 300px;
    font-size: 15px;
}
.words p.good5{
    max-width: 300px;
    font-size: 15px;
}
.words p.good6{
    max-width: 300px;
    font-size: 15px;
}
.words p.good7{
    max-width: 300px;
    font-size: 15px;
}
footer{
    
    background-color: #705138;
    text-align: center;
    height: 70px;
    width: auto;
    padding-top: 10px;
    font-size: 13px;
    color: lavender;
    font:small-caps
}
h2{
    display: inline;
    margin-right: 50px;
}
.terms
{
    color:aliceblue;
    text-decoration: none;
}
.terms:hover{
    text-decoration: underline;
}


```

```
admin.html


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title class="sp">
        Spice Bazaar 🌶️
    </title>
    <link
        href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&family=Roboto:wght@300;400;500&family=Gloock&display=swap"
        rel="stylesheet">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Audiowide|Sofia|Trirong">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link
        href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
        rel="stylesheet">
    <link
        href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&family=Montserrat:ital,wght@0,100;1,100&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
        rel="stylesheet">
    <link
        href="https://fonts.googleapis.com/css2?family=Alumni+Sans+Pinstripe:ital@0;1&family=Dancing+Script:wght@400..700&family=Montserrat:ital,wght@0,100;1,100&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
        rel="stylesheet">

    <link rel="stylesheet" href="admin.css">
</head>

<body>
    <div class="header">
        <div class="logo">
            <img src="logo.png" class="img">
            <h1 class="spice">Spice Symphony</h1>
        </div>
        <div class="bar">
            <input placeholder="Search">
            <button type="button" id="search">Search
        </div>
    </div>
    <div class="contents">
        <nav class="nav-contents">
            <ul>
                <li><a href="home.html" class="hyper">Home</a></li>
                <li><a href="menu.html" class="hyper">Menu</a></li>
                <li><a href="admin.html" class="hyper">Administration</a></li>
                <li><a href="contact.html" class="hyper">Contact Us</a></li>
            </ul>
        </nav>
    </div>
    <div class="admins">
        <div class="photo1">
        </div>
        <div class="names">
            <h2 class="order">Founder</h2>
        </div>
    </div>
    <div class="admins">
        <div class="photo2">
        </div>
        <div class="names">
            <h2 class="order">Manager</h2>
        </div>
    </div>
    <div class="admins">
        <div class="photo3">
        </div>
        <div class="names">
            <h2 class="order">Head Chef</h2>
        </div>
    </div>
    
    <br><br><br><br><br>
    <footer>
        <h2><a href="name" class="terms">Terms and conditions </a> </h2>
        <h2><a href="name" class="terms">Cookie Policy </a> </h2>
        <h2><a href="name" class="terms">Privacy Policy </a></h2>
        <br><br>
        <h2> Copyright &copy; 2024 SPICY SYMPHONY </h2>
    </footer>
</body>

</html>

admin.css

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.header {
    background-color:beige;
    padding: 5px 0;
    text-align: center;
    margin-top: -10px;
    display: block;
}

.logo {
    display: flex;
    justify-content: center;
    align-items: center;
}

.img {
    height: 90px;
    width: auto;
    margin-right: 5px;
}

.spice{
    font-size: 40px;
    font-weight: 700;
    color:#3d2a1f; 
    font-family: Gloock; 
    text-transform: uppercase;
    letter-spacing: 2px;
}
input{
   margin-left: 50px;
    height: 25px;
    width: 300px;
    border-style:dotted;
    border-color:rgb(192, 146, 146);
    background-color: rgb(244, 244, 208);
    border-radius: 5px;
    padding-left: 2px;
}
button{
    margin-right: 3px;
    height: 25px;
    width: 60px;
    border-radius: 4px;
    text-align: center;
    border: none;
    background-color: #387051;
    color: white;
    font-family: Poppins;
    font-weight: 700;
    cursor:pointer;
    letter-spacing: 1px;

}

button:hover{
    color:lavender;
    text-decoration: dashed;
}
.bar{
    margin-bottom: 10px;
    text-align:center;
}

nav{
    color:white ;
    background-color:#705138;
    margin-bottom: 40px;
}
li,ul{
    padding: 5px;
    padding-left: 120px;
    padding-right: 100px;
    display: inline-block;
    height: 50px;
    width: auto;
    font-size: 20px;
    font-family: Trirong;
    font-weight: bold;
    letter-spacing: 1px;
    cursor: pointer;
}
.hyper{
    color: white;
    text-decoration: none;
}
a:hover{
    color: burlywood;
}
.admins{
    margin-left: 11%;
    border-color:rgb(241, 236, 236);
    display: inline-block;
    margin-top: 5%;
    border-radius: 10px;
    margin-bottom: 20px;
}
.photo1{
    width: 270px;
    height: 300px; 
    background-image:url(founder.jpeg); 
    background-size:cover; 
    background-position: center; 
    border-radius: 10px;
    display: flex;
    border: 4px;
}
.photo2{
    width: 270px;
    height: 300px; 
    background-image:url(manager.jpeg); 
    background-size:cover; 
    background-position: center; 
    border-radius: 10px;
    display: flex;
    border: 4px;
}
.photo3{

    width: 270px;
    height: 300px; 
    background-image:url(chef2.jpeg); 
    background-size:cover; 
    background-position: center; 
    border-radius: 10px;
    display: flex;
    border: 4px;
}
.names
{
    margin-left: 30px;
    padding-top: 10px;
    padding-left: 10px;
    font-family: Trirong;
    text-align: center;
}
.order{
    font-size: 20px;
}
.words:hover{
    color: red;
}
footer{
    margin-top: 108px;
    background-color: #705138;
    text-align: center;
    height: 70px;
    width: auto;
    padding-top: 10px;
    font-size: 13px;
    color: lavender;
    font:small-caps
}
h2{
    display: inline;
    margin-right: 50px;
}
.terms
{
    color:aliceblue;
    text-decoration: none;
}
.terms:hover{
    text-decoration: underline;
}

.details-ul{
    font-family: Alumni Sans Pinstripe;
    font-size: 25px;
    margin-top: 10px;
    margin-right: 50px;
    display: inline-block;

}


```

```
contact.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title class="sp">
        Spice Bazaar 🌶️
    </title>
    <link
        href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&family=Roboto:wght@300;400;500&family=Gloock&display=swap"
        rel="stylesheet">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Audiowide|Sofia|Trirong">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link
        href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap"
        rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&family=Montserrat:ital,wght@0,100;1,100&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">
        <link href="https://fonts.googleapis.com/css2?family=Alumni+Sans+Pinstripe:ital@0;1&family=Dancing+Script:wght@400..700&family=Montserrat:ital,wght@0,100;1,100&family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="contact.css">
</head>

<body>
    <div class="header">
        <div class="logo">
            <img src="logo.png" class="img">
            <h1 class="spice">Spice Symphony</h1>
        </div>
        <div class="bar">
            <input placeholder="Search">
            <button type="button" id="search">Search
        </div>
    </div>
    <div class="contents">
        <nav class="nav-contents">
            <ul>
                <li><a href="home.html" class="hyper">Home</a></li>
                <li><a href="menu.html" class="hyper">Menu</a></li>
                <li><a href="admin.html" class="hyper">Administration</a></li>
                <li><a href="contact.html" class="hyper">Contact Us</a></li>
            </ul>
        </nav>
    </div>

    <div class="ender">
        <div class="location">
            <h2 class="tag">Location</h2><br>
            <h3 class="iden">Spice Symphony 24,</h3>
            <h3 class="iden"> Usman Road ,</h3>
            <h3 class="iden">T. Nagar, Chennai,</h3>
            <h3 class="iden">Tamil Nadu - 600017.</h3>
        </div>
        <div class="location2">
            <h2 class="tag">Hours</h2>
            <h3 class="iden">Mon,Tue,Wed,Thur</h3>
            <h3 class="iden"> 10.00 AM - 8.00 PM,</h3>
            <br>
            <h3 class="iden">Fri,Sat</h3>
            <h3 class="iden">10.00 AM - 9.00 PM</h3>
            <br>
            <h3 class="iden">Sun</h3>
            <h3 class="iden">11.00 AM - 4.00 PM</h3>
        </div>
        <div class="location3">
            <h2 class="tag">Find us on</h2>
            <h3 class="iden">Instagram  :</h3>
            <h3 class="iden"> @SpicySymphonyVibes</h3>
            <br>
            <h3 class="iden">X :</h3>
            <h3 class="iden">@SpicyEatsSymphony </h3>
            <br>
            <h3 class="iden">Facebook :</h3>
            <h3 class="iden">@SymphonyOfSpice</h3>
        </div>
    </div>
    <div class="details">
        <ul class="details-ul">
            <li class="details-ul"><b> 📞</b> : +91 8825492139,</li>
            <li  class="details-ul"></li>
            <li  class="details-ul"></li>
            <li class="details-ul"><b> 📧 </b> : SpicyEatsSymphony@gmail.com</li> 
        </ul>
    </div>
    <br><br><br><br><br><br>
    <footer>
        <h2><a href="name" class="terms">Terms and conditions </a> </h2>
        <h2><a href="name" class="terms">Cookie Policy </a> </h2>
        <h2><a href="name" class="terms">Privacy Policy </a></h2>
        <br><br>
        <h2> Copyright &copy; 2024 SPICY SYMPHONY </h2>
    </footer>
</body>

</html>

contact.css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

.header {
    background-color:beige;
    padding: 5px 0;
    text-align: center;
    margin-top: -10px;
    display: block;
}

.logo {
    display: flex;
    justify-content: center;
    align-items: center;
}

.img {
    height: 90px;
    width: auto;
    margin-right: 5px;
}

.spice{
    font-size: 40px;
    font-weight: 700;
    color:#3d2a1f; 
    font-family: Gloock; 
    text-transform: uppercase;
    letter-spacing: 2px;
}
input{
   margin-left: 50px;
    height: 25px;
    width: 300px;
    border-style:dotted;
    border-color:rgb(192, 146, 146);
    background-color: rgb(244, 244, 208);
    border-radius: 5px;
    padding-left: 2px;
}
button{
    margin-right: 3px;
    height: 25px;
    width: 60px;
    border-radius: 4px;
    text-align: center;
    border: none;
    background-color: #387051;
    color: white;
    font-family: Poppins;
    font-weight: 700;
    cursor:pointer;
    letter-spacing: 1px;

}

button:hover{
    color:lavender;
    text-decoration: dashed;
}
.bar{
    margin-bottom: 10px;
    text-align:center;
}

nav{
    color:white ;
    background-color:#705138;
    margin-bottom: 40px;
}
li,ul{
    padding: 5px;
    padding-left: 120px;
    padding-right: 100px;
    display: inline-block;
    height: 50px;
    width: auto;
    font-size: 20px;
    font-family: Trirong;
    font-weight: bold;
    letter-spacing: 1px;
    cursor: pointer;
}
.hyper{
    color: white;
    text-decoration: none;
}
a:hover{
    color: burlywood;
}
.tag{
    font-family: Trirong;
    text-align: center;
    font-size: 20px;
    margin-bottom: 10px;
    text-transform: uppercase;
}

.location{
    border-radius: 20px;
    display: inline-block;
    color: black ;
    margin-top: 60px;
    padding-left: 40px;
}
.iden{
    font-family: Montserrat;
    font-size: 20px;
    padding-top: 5px;
}
.ender{
    display: flex;
    width: 100%;
    height: 400px;
    background-color: #f4f4f4;
}
.location2{
    border-radius: 20px;
    display: inline-block;
    color: black ;
    margin-top: 50px;
    padding-left: 27%;
}
.location3{
    border-radius: 20px;
    display: inline-block;
    color: black ;
    margin-top: 50px;
    padding-left: 20%;
}
footer{
    
    background-color: #705138;
    text-align: center;
    height: 70px;
    width: auto;
    padding-top: 10px;
    font-size: 13px;
    color: lavender;
    font:small-caps
}
h2{
    display: inline;
    margin-right: 50px;
}
.terms
{
    color:aliceblue;
    text-decoration: none;
}
.terms:hover{
    text-decoration: underline;
}

.details-ul{
    font-family: Alumni Sans Pinstripe;
    font-size: 25px;
    margin-top: 10px;
    margin-right: 50px;
    display: inline-block;
}
```
## OUTPUT:
![alt text](<Screenshot (98).png>)

![alt text](<Screenshot (99).png>)

![alt text](<Screenshot (100).png>)

![alt text](<Screenshot (101).png>)

![alt text](<Screenshot (102).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
