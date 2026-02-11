
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
