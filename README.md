
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Motherboard Store</title>

<style>

body{
font-family: Arial, sans-serif;
margin:0;
background:#f4f4f4;
}

header{
background:#111;
color:white;
padding:20px;
text-align:center;
}

nav a{
color:white;
margin:10px;
text-decoration:none;
font-size:18px;
}

.products{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:20px;
padding:40px;
}

.card{
background:white;
padding:20px;
border-radius:10px;
width:250px;
text-align:center;
box-shadow:0 0 10px rgba(0,0,0,0.1);
transition:0.3s;
}

.card:hover{
transform:scale(1.05);
}

.card img{
width:100%;
border-radius:10px;
}

button{
background:#007BFF;
color:white;
border:none;
padding:10px 15px;
cursor:pointer;
border-radius:5px;
margin-top:10px;
}

button:hover{
background:#0056b3;
}

footer{
background:#111;
color:white;
text-align:center;
padding:15px;
margin-top:20px;
}

</style>

</head>

<body>

<header>
<h1>Motherboard Store</h1>

<nav>
<a href="#">Home</a>
<a href="#">Products</a>
<a href="#">Contact</a>
</nav>

</header>

<section class="products">

<div class="card">
<img src="https://via.placeholder.com/250">
<h2>Gaming Motherboard</h2>
<p>High performance motherboard for gaming PCs.</p>
<button>Buy Now</button>
</div>

<div class="card">
<img src="https://via.placeholder.com/250">
<h2>Intel Motherboard</h2>
<p>Compatible with latest Intel processors.</p>
<button>Buy Now</button>
</div>

<div class="card">
<img src="https://via.placeholder.com/250">
<h2>AMD Ryzen Motherboard</h2>
<p>Best motherboard for Ryzen CPUs.</p>
<button>Buy Now</button>
</div>

<div class="card">
<img src="https://via.placeholder.com/250">
<h2>Budget Motherboard</h2>
<p>Affordable motherboard for office PCs.</p>
<button>Buy Now</button>
</div>

</section>

<footer>
<p>© 2026 Motherboard Store</p>
</footer>

</body>
</html>
