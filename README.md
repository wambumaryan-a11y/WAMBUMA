<!DOCTYPE html>
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

/* NAVBAR */
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

/* SEARCH */
.search{
  text-align:center;
  padding:20px;
}
.search input{
  width:60%;
  padding:10px;
}

/* CONTENT */
.container{
  width:90%;
  margin:auto;
}

h1{
  margin-top:10px;
}

.paragraph{
  background:white;
  padding:25px;
  border-radius:10px;
  margin:20px 0;
}

/* IMAGE ROW */
.images{
  display:grid;
  grid-template-columns: repeat(6,1fr);
  gap:10px;
}
.images div{
  background:#ddd;
  height:80px;
  display:flex;
  align-items:center;
  justify-content:center;
}

/* VIDEO ROW */
.videos{
  display:grid;
  grid-template-columns: repeat(4,1fr);
  gap:10px;
  margin-top:15px;
}
.videos div{
  background:#bbb;
  height:100px;
  display:flex;
  align-items:center;
  justify-content:center;
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

<h1>Your Heading – Best Recipes 2026</h1>

<div class="paragraph">
  <p>
    This is your paragraph section. Add your description about recipes
    or website content here.
  </p>
</div>

<!-- IMAGES -->
<div class="images">
  <div>Image 1</div>
  <div>Image 2</div>
  <div>Image 3</div>
  <div>Image 4</div>
  <div>Image 5</div>
  <div>Image 6</div>
</div>

<!-- VIDEOS -->
<div class="videos">
  <div>Video 1</div>
  <div>Video 2</div>
  <div>Video 3</div>
  <div>Video 4</div>
</div>

<!-- TABLES -->
<div class="tables">
  <table>
    <tr><th>Table 1</th></tr>
    <tr><td>Data</td></tr>
    <tr><td>Data</td></tr>
  </table>

  <table>
    <tr><th>Table 2</th></tr>
    <tr><td>Data</td></tr>
    <tr><td>Data</td></tr>
  </table>
</div>

</div>

</body>
</html>
