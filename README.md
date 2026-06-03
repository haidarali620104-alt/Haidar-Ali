<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CryptoNova - Premium Crypto Platform</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    background:linear-gradient(135deg,#06142d,#0b1f47,#0f4dff);
    color:white;
    overflow-x:hidden;
}

/* Navbar */
nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:25px 8%;
}

.logo{
    font-size:28px;
    font-weight:700;
    color:#4fc3ff;
}

nav ul{
    display:flex;
    list-style:none;
    gap:35px;
}

nav a{
    color:white;
    text-decoration:none;
    transition:.3s;
}

nav a:hover{
    color:#4fc3ff;
}

.btn{
    background:#2196f3;
    padding:12px 25px;
    border:none;
    border-radius:30px;
    color:white;
    cursor:pointer;
    font-weight:600;
    transition:.3s;
}

.btn:hover{
    transform:translateY(-3px);
    box-shadow:0 10px 25px rgba(33,150,243,.5);
}

/* Hero */
.hero{
    min-height:90vh;
    display:flex;
    align-items:center;
    justify-content:space-between;
    padding:0 8%;
}

.hero-text{
    max-width:600px;
}

.hero-text h1{
    font-size:65px;
    line-height:1.1;
    margin-bottom:20px;
}

.hero-text span{
    color:#4fc3ff;
}

.hero-text p{
    color:#d9e6ff;
    margin-bottom:30px;
}

.hero-image{
    width:450px;
    height:450px;
    border-radius:50%;
    background:radial-gradient(circle,#4fc3ff,#0f4dff);
    display:flex;
    align-items:center;
    justify-content:center;
    font-size:130px;
    box-shadow:0 0 80px rgba(79,195,255,.6);
}

/* Stats */
.stats{
    display:flex;
    justify-content:center;
    gap:30px;
    padding:40px 8%;
    flex-wrap:wrap;
}

.card{
    background:rgba(255,255,255,.08);
    backdrop-filter:blur(10px);
    border:1px solid rgba(255,255,255,.1);
    padding:30px;
    border-radius:20px;
    text-align:center;
    width:250px;
}

.card h2{
    color:#4fc3ff;
}

/* Features */
.features{
    padding:100px 8%;
    text-align:center;
}

.features h2{
    font-size:42px;
    margin-bottom:50px;
}

.feature-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.feature{
    background:rgba(255,255,255,.08);
    padding:30px;
    border-radius:20px;
    transition:.4s;
}

.feature:hover{
    transform:translateY(-10px);
}

.feature h3{
    color:#4fc3ff;
    margin-bottom:10px;
}

/* CTA */
.cta{
    padding:100px 8%;
    text-align:center;
}

.cta-box{
    background:rgba(255,255,255,.08);
    padding:60px;
    border-radius:25px;
    backdrop-filter:blur(10px);
}

.cta h2{
    font-size:42px;
    margin-bottom:20px;
}

/* Footer */
footer{
    text-align:center;
    padding:30px;
    color:#cfdfff;
}

@media(max-width:900px){
    .hero{
        flex-direction:column;
        text-align:center;
        gap:50px;
        padding-top:50px;
    }

    .hero-text h1{
        font-size:48px;
    }

    .hero-image{
        width:300px;
        height:300px;
        font-size:90px;
    }

    nav ul{
        display:none;
    }
}
</style>
</head>
<body>

<nav>
    <div class="logo">CryptoNova</div>

    <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Markets</a></li>
        <li><a href="#">Features</a></li>
        <li><a href="#">Pricing</a></li>
    </ul>

    <button class="btn">Get Started</button>
</nav>

<section class="hero">
    <div class="hero-text">
        <h1>Trade Crypto With <span>Confidence</span></h1>
        <p>
            Secure, fast and premium cryptocurrency trading platform.
            Buy, sell and manage your digital assets with advanced tools.
        </p>

        <button class="btn">Start Trading</button>
    </div>

    <div class="hero-image">
        ₿
    </div>
</section>

<section class="stats">
    <div class="card">
        <h2>$12B+</h2>
        <p>Trading Volume</p>
    </div>

    <div class="card">
        <h2>5M+</h2>
        <p>Active Users</p>
    </div>

    <div class="card">
        <h2>150+</h2>
        <p>Supported Coins</p>
    </div>
</section>

<section class="features">
    <h2>Premium Features</h2>

    <div class="feature-grid">

        <div class="feature">
            <h3>Ultra Security</h3>
            <p>Multi-layer protection and cold wallet storage.</p>
        </div>

        <div class="feature">
            <h3>Live Analytics</h3>
            <p>Real-time charts and market insights.</p>
        </div>

        <div class="feature">
            <h3>Fast Transactions</h3>
            <p>Instant deposits and withdrawals worldwide.</p>
        </div>

        <div class="feature">
            <h3>24/7 Support</h3>
            <p>Dedicated premium customer assistance.</p>
        </div>

    </div>
</section>

<section class="cta">
    <div class="cta-box">
        <h2>Join The Future of Finance</h2>
        <p>Create your account and start trading today.</p>
        <br>
        <button class="btn">Create Account</button>
    </div>
</section>

<footer>
    © 2026 CryptoNova. All Rights Reserved.
</footer>

</body>
</html>
