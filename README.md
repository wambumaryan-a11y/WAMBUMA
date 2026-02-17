<!DOCTYPE html>
<html>
<head>
    <title>Food Website Paragraph Task</title>
</head>
<body>

<!-- Line 1: Bold -->
<p><b>Welcome to Delicious Bites, your number one destination for amazing food experiences.</b></p>

<!-- Line 2: Italic -->
<p><i>We specialize in fresh, organic, and locally sourced ingredients.</i></p>

<!-- Line 3: Underlined -->
<p><u>Our chefs prepare every dish with passion and creativity.</u></p>

<!-- Line 4: Superscript -->
<p>Our restaurant was established in 2024<sup>th</sup> and has served over 10<sup>3</sup> happy customers.</p>

<!-- Line 5: Subscript -->
<p>Our secret sauce formula includes H<sub>2</sub>O and special spices.</p>

<!-- Line 6: Strike -->
<p><strike>We used to offer frozen meals.</strike> Now we serve only fresh dishes.</p>

<!-- Line 7: Highlight -->
<p><mark>Today’s Special Offer: Get 20% off on all pasta dishes!</mark></p>

<!-- Line 8: Quotation -->
<p><q>Good food is the foundation of genuine happiness.</q></p>

<!-- Line 9: Indented Quotation -->
<blockquote>
    At Delicious Bites, we believe food brings people together.
    Every meal tells a story of culture, flavor, and tradition.
</blockquote>

<!-- Line 10: Footer -->
<footer>
    <p>© 2026 Delicious Bites | All Rights Reserved</p>
</footer>

<!-- Line 11: Line Breaks -->
<p>
Fresh Ingredients<br>
Fast Delivery<br>
Excellent Service<br>
Affordable Prices
</p>

<!-- Line 12: 3 lines with HR -->
<p>Breakfast Menu</p>
<hr>
<p>Lunch Menu</p>
<hr>
<p>Dinner Menu</p>

<!-- Line 13: Preformatted text -->
<pre>
Grilled Chicken
Veggie Burger
Seafood Pasta
</pre>

<!-- Line 14: Lists -->
<h3>Unordered List (5 items)</h3>
<ul>
    <li>Pizza</li>
    <li>Burger</li>
    <li>Pasta</li>
    <li>Salad</li>
    <li>Soup</li>
</ul>

<h3>Ordered List (5 items)</h3>
<ol>
    <li>Choose Meal</li>
    <li>Add to Cart</li>
    <li>Enter Address</li>
    <li>Make Payment</li>
    <li>Enjoy Food</li>
</ol>

<!-- Line 15: Nested List (6 items total) -->
<h3>Nested List</h3>
<ul>
    <li>Main Course
        <ul>
            <li>Steak</li>
            <li>Rice</li>
            <li>Chicken</li>
        </ul>
    </li>
    <li>Desserts
        <ul>
            <li>Ice Cream</li>
            <li>Cake</li>
            <li>Pudding</li>
        </ul>
    </li>
</ul>

<!-- Line 17: Table with 10 columns and 5 rows -->
<h3>Food Price Table</h3>
<table border="1">
    <tr>
        <th>Item</th>
        <th>Category</th>
        <th>Calories</th>
        <th>Price</th>
        <th>Rating</th>
        <th>Available</th>
        <th>Chef</th>
        <th>Spicy Level</th>
        <th>Prep Time</th>
        <th>Discount</th>
    </tr>
    <tr>
        <td>Pizza</td>
        <td>Fast Food</td>
        <td>300</td>
        <td>1000</td>
        <td>4.5</td>
        <td>Yes</td>
        <td>John</td>
        <td>Medium</td>
        <td>15 min</td>
        <td>10%</td>
    </tr>
    <tr>
        <td>Burger</td>
        <td>Fast Food</td>
        <td>250</td>
        <td>800</td>
        <td>4.2</td>
        <td>Yes</td>
        <td>Mary</td>
        <td>Low</td>
        <td>10 min</td>
        <td>5%</td>
    </tr>
    <tr>
        <td>Pasta</td>
        <td>Italian</td>
        <td>280</td>
        <td>1200</td>
        <td>4.7</td>
        <td>Yes</td>
        <td>David</td>
        <td>High</td>
        <td>20 min</td>
        <td>15%</td>
    </tr>
    <tr>
        <td>Salad</td>
        <td>Healthy</td>
        <td>150</td>
        <td>700</td>
        <td>4.3</td>
        <td>Yes</td>
        <td>Anna</td>
        <td>Low</td>
        <td>8 min</td>
        <td>0%</td>
    </tr>
    <tr>
        <td>Soup</td>
        <td>Starter</td>
        <td>120</td>
        <td>600</td>
        <td>4.0</td>
        <td>Yes</td>
        <td>Chris</td>
        <td>Medium</td>
        <td>12 min</td>
        <td>5%</td>
    </tr>
</table>

</body>
</html>

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Best Recipes 2026</title>

<style>
body{
  font-family: Arial, sans-serif;
  margin:0;
  background:#f4f4f4;
}

nav{
  display:flex;
  justify-content:space-around;
  padding:15px;
  background:#222;
}

nav a{
  color:white;
  text-decoration:none;
  padding:8px 18px;
  border:1px solid white;
  border-radius:6px;
}

.search{
  text-align:center;
  padding:20px;
}
.search input{
  width:60%;
  padding:10px;
}

.container{
  width:90%;
  margin:auto;
}

.paragraph{
  background:white;
  padding:25px;
  border-radius:10px;
  margin:20px 0;
}

/* FOOD IMAGES */
.images{
  display:grid;
  grid-template-columns: repeat(6,1fr);
  gap:10px;
}
.images img{
  width:100%;
  height:120px;
  object-fit:cover;
  border-radius:8px;
}

/* FOOD VIDEOS */
.videos{
  display:grid;
  grid-template-columns: repeat(4,1fr);
  gap:10px;
  margin-top:15px;
}
.videos iframe{
  width:100%;
  height:180px;
  border-radius:10px;
}

/* TABLES */
.tables{
  display:flex;
  gap:20px;
  margin:20px 0;
}
table{
  width:50%;
  background:white;
  border-collapse:collapse;
}
td,th{
  border:1px solid black;
  padding:10px;
}
</style>
</head>

<body>

<!-- NAV -->
<nav>
  <a href="#">Home</a>
  <a href="#">Contacts</a>
  <a href="#">About</a>
  <a href="#">Testimonials</a>
</nav>

<!-- SEARCH -->
<div class="search">
  <input type="text" placeholder="Search box">
</div>

<div class="container">

<h1> Ryan's online cook book</h1>

<div class="paragraph">
  <p>
    Welcome to our food website! Here you can find amazing meals,
    cooking ideas, and delicious recipes for everyone.
  </p>
</div>

<!-- FOOD IMAGES -->
<div class="images">
  <img src="https://images.unsplash.com/photo-1604908176997-125f25cc6f3d" alt="pizza">
  <img src="https://images.unsplash.com/photo-1546069901-ba9599a7e63c" alt="salad">
  <img src="https://images.unsplash.com/photo-1565299624946-b28f40a0ae38" alt="burger">
  <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836" alt="pasta">
  <img src="https://images.unsplash.com/photo-1529042410759-befb1204b468" alt="dessert">
  <img src="https://images.unsplash.com/photo-1604908176997-125f25cc6f3d" alt="chicken">
  
 
  
</div>


<!-- FOOD VIDEOS (YouTube embeds) -->
<div class="videos">
  
  <iframe src="https://www.youtube.com/embed/dA8Smj5tZOQ" allowfullscreen></iframe>
  <iframe src="https://www.youtube.com/embed/4aZr5hZXP_s" allowfullscreen></iframe>
  <iframe src="https://www.youtube.com/embed/kRCH8kD1GD0" allowfullscreen></iframe>

<iframe  src="https://www.youtube.com/embed/AmC9SmCBUj4?si" allowfullscreen></iframe>



 

</div>

</body>
</html>
