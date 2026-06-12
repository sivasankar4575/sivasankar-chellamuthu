<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Website UI Redesign</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:#f8fafc;
    color:#1f2937;
}

/* Navigation */
nav{
    background:#2563eb;
    color:white;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:15px 30px;
}

nav ul{
    list-style:none;
    display:flex;
    gap:20px;
}

nav ul li{
    cursor:pointer;
}

/* Hero Section */
.hero{
    text-align:center;
    padding:80px 20px;
    background:white;
}

.hero h1{
    font-size:40px;
    margin-bottom:15px;
}

.hero p{
    font-size:18px;
    margin-bottom:20px;
}

.btn{
    background:#2563eb;
    color:white;
    border:none;
    padding:12px 25px;
    border-radius:8px;
    cursor:pointer;
}

/* Products */
.products{
    padding:40px 20px;
}

.products h2{
    text-align:center;
    margin-bottom:20px;
}

.product-grid{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:20px;
}

.card{
    background:white;
    padding:20px;
    border-radius:10px;
    box-shadow:0 2px 5px rgba(0,0,0,0.1);
    text-align:center;
}

.card img{
    width:100%;
    height:150px;
    object-fit:cover;
    border-radius:8px;
}

/* Reviews */
.reviews{
    padding:40px 20px;
    text-align:center;
}

.review-box{
    background:white;
    padding:20px;
    margin:10px auto;
    max-width:600px;
    border-radius:10px;
    box-shadow:0 2px 5px rgba(0,0,0,0.1);
}

/* Footer */
footer{
    background:#2563eb;
    color:white;
    text-align:center;
    padding:15px;
    margin-top:20px;
}

/* Responsive Design */
@media(max-width:768px){

    nav{
        flex-direction:column;
        text-align:center;
    }

    nav ul{
        flex-direction:column;
        margin-top:10px;
    }

    .hero h1{
        font-size:28px;
    }

    .product-grid{
        grid-template-columns:1fr;
    }
}
</style>
</head>

<body>

<nav>
    <h2>MyStore</h2>
    <ul>
        <li>Home</li>
        <li>Products</li>
        <li>About</li>
        <li>Contact</li>
    </ul>
</nav>

<section class="hero">
    <h1>Welcome to Our Store</h1>
    <p>Shop Smart, Live Better</p>
    <button class="btn">Shop Now</button>
</section>

<section class="products">
    <h2>Featured Products</h2>

    <div class="product-grid">

        <div class="card">
            <img src="https://via.placeholder.com/250x150" alt="Product">
            <h3>Product 1</h3>
            <p>₹999</p>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/250x150" alt="Product">
            <h3>Product 2</h3>
            <p>₹1499</p>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/250x150" alt="Product">
            <h3>Product 3</h3>
            <p>₹1999</p>
        </div>

        <div class="card">
            <img src="https://via.placeholder.com/250x150" alt="Product">
            <h3>Product 4</h3>
            <p>₹2499</p>
        </div>

    </div>
</section>

<section class="reviews">
    <h2>Customer Reviews</h2>

    <div class="review-box">
        ⭐⭐⭐⭐⭐ <br>
        "Excellent products and fast delivery!"
    </div>

    <div class="review-box">
        ⭐⭐⭐⭐⭐ <br>
        "Very easy to use website."
    </div>
</section>

<footer>
    <p>© 2026 MyStore. All Rights Reserved.</p>
</footer>

</body>
</html>
