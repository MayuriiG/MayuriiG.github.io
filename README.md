# MayuriiG.github.io

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Luxury Home</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family: 'Inter', sans-serif;
    background:#f6f4f1;
    color:#222;
}

/* NAVBAR */
header{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:25px 80px;
    background:white;
}

.logo{
    font-family:'Playfair Display', serif;
    font-size:22px;
    letter-spacing:2px;
}

nav a{
    text-decoration:none;
    color:#444;
    margin-left:30px;
    font-size:14px;
}

nav a:hover{
    color:black;
}

/* HERO SECTION */
.hero{
    height:75vh;
    background: url('https://images.unsplash.com/photo-1616627981449-0e8e19e4e9fa') center/cover no-repeat;
    display:flex;
    align-items:center;
    padding-left:100px;
    color:white;
}

.hero-content{
    max-width:500px;
}

.hero h1{
    font-family:'Playfair Display', serif;
    font-size:50px;
    margin-bottom:20px;
}

.hero p{
    font-size:16px;
    margin-bottom:25px;
    line-height:1.6;
}

.btn{
    padding:10px 22px;
    border:1px solid white;
    text-decoration:none;
    color:white;
    font-size:14px;
}

/* PRODUCTS */
.products{
    padding:80px 100px;
    display:flex;
    gap:30px;
}

.card{
    position:relative;
    width:33%;
    overflow:hidden;
}

.card img{
    width:100%;
    height:400px;
    object-fit:cover;
    transition:0.4s;
}

.card:hover img{
    transform:scale(1.05);
}

.card-content{
    position:absolute;
    bottom:0;
    left:0;
    width:100%;
    padding:25px;
    background:linear-gradient(to top, rgba(0,0,0,0.7), transparent);
    color:white;
}

.card-content h3{
    font-family:'Playfair Display', serif;
    font-size:20px;
    margin-bottom:10px;
}

.card-content p{
    font-size:13px;
    opacity:0.9;
}
</style>
</head>

<body>

<header>
    <div class="logo">ITALIC</div>
    <nav>
        <a href="#">Home</a>
        <a href="#">Women</a>
        <a href="#">Men</a>
        <a href="#">Beauty</a>
        <a href="#">Login</a>
    </nav>
</header>

<section class="hero">
    <div class="hero-content">
        <h1>Home Must-haves</h1>
        <p>Upgrade your home essentials with our refined collection of towels and decor designed for timeless elegance.</p>
        <a href="#" class="btn">Shop Now</a>
    </div>
</section>

<section class="products">
    
    <div class="card">
        <img src="https://images.unsplash.com/photo-1582719478250-c89cae4dc85b">
        <div class="card-content">
            <h3>Berries Osmanthus Candle</h3>
            <p>Rich and delicate notes for a refined atmosphere.</p>
        </div>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1598300056393-4aac492f4344">
        <div class="card-content">
            <h3>Romi Cashmere Throw</h3>
            <p>Premium softness crafted for everyday comfort.</p>
        </div>
    </div>

    <div class="card">
        <img src="https://images.unsplash.com/photo-1520975922323-4b7cbb8c7f3b">
        <div class="card-content">
            <h3>Enzo Italian Leather Belt</h3>
            <p>Luxury craftsmanship with timeless design.</p>
        </div>
    </div>

</section>

</body>
</html>
