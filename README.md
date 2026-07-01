<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Senglirbelles | Online Boutique</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

body{
    background:#fff;
    color:#333;
}

header{
    background:linear-gradient(135deg,#ffb6c1,#ffffff,#add8e6);
    padding:60px 20px;
    text-align:center;
}

header h1{
    font-size:48px;
    color:#ff4081;
}

header p{
    font-size:20px;
    margin-top:10px;
}

.btn{
    display:inline-block;
    margin-top:20px;
    background:#ff4081;
    color:white;
    padding:12px 25px;
    text-decoration:none;
    border-radius:30px;
    transition:.3s;
}

.btn:hover{
    background:#e91e63;
}

section{
    padding:60px 20px;
    text-align:center;
}

.products{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
    margin-top:30px;
}

.card{
    background:white;
    border-radius:15px;
    box-shadow:0 5px 15px rgba(0,0,0,.1);
    overflow:hidden;
}

.card img{
    width:100%;
    height:250px;
    object-fit:cover;
}

.card h3{
    margin:15px;
}

.card p{
    color:#ff4081;
    font-weight:bold;
    margin-bottom:15px;
}

footer{
    background:#add8e6;
    color:white;
    text-align:center;
    padding:20px;
}
</style>
</head>

<body>

<header>
<h1>Senglirbelles</h1>
<p>Fashion that makes every woman shine ✨</p>

<a href="#collection" class="btn">
Shop Now
</a>
</header>

<section id="collection">

<h2>Featured Collection</h2>

<div class="products">

<div class="card">
<img src="https://images.unsplash.com/photo-1524504388940-b1c1722653e1?w=600" alt="">
<h3>Elegant Dress</h3>
<p>₹1,499</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1496747611176-843222e1e57c?w=600" alt="">
<h3>Stylish Outfit</h3>
<p>₹1,999</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1483985988355-763728e1935b?w=600" alt="">
<h3>Premium Collection</h3>
<p>₹2,299</p>
</div>

</div>

</section>

<section>

<h2>About Us</h2>

<p style="max-width:700px;margin:auto;margin-top:20px;line-height:1.8;">
Welcome to <strong>Senglirbelles</strong>, where elegance meets style.
We believe every woman deserves to feel beautiful and confident.
Discover trendy, premium-quality fashion carefully selected just for you.
</p>

</section>

<footer>

<p>© 2026 Senglirbelles. All Rights Reserved.</p>

</footer>

</body>
</html>
