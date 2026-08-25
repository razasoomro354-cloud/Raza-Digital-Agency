<!DOCTYPE html>
<html>
<head>
<title>Raza Digital Agency</title>

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial;
}

body{
background:#050505;
color:white;
}

header{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px;
background:#0b0b0b;
box-shadow:0 0 20px #00ff88;
position:sticky;
top:0;
}

.logo{
font-size:28px;
color:#00ff88;
font-weight:bold;
text-shadow:0 0 15px #00ff88;
}

nav a{
color:white;
text-decoration:none;
margin:10px;
}

nav a:hover{
color:#00ff88;
}


.hero{
height:90vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
background:linear-gradient(#050505,#101010);
}


.hero h1{
font-size:55px;
color:#00ff88;
text-shadow:0 0 20px #00ff88;
}


.hero p{
font-size:20px;
margin:20px;
color:#ccc;
}


.btn{
background:#00ff88;
color:black;
padding:15px 35px;
border-radius:40px;
text-decoration:none;
font-weight:bold;
box-shadow:0 0 20px #00ff88;
}


section{
padding:60px 20px;
}


.title{
text-align:center;
font-size:35px;
color:#00ff88;
margin-bottom:40px;
}


.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}


.card{
background:#111;
padding:25px;
border-radius:15px;
border:1px solid #00ff88;
box-shadow:0 0 15px #00ff88;
}


.card h2{
color:#00ff88;
}


.price{
font-size:30px;
color:#00ff88;
margin:15px;
}


input,textarea{
width:90%;
padding:15px;
margin:10px;
background:#111;
border:1px solid #00ff88;
color:white;
border-radius:10px;
}


button{
padding:15px 40px;
background:#00ff88;
border:none;
border-radius:30px;
font-weight:bold;
}


.whatsapp{

position:fixed;
right:20px;
bottom:20px;
background:#25D366;
color:white;
padding:15px 20px;
border-radius:50px;
text-decoration:none;
font-weight:bold;
box-shadow:0 0 20px #25D366;

}


footer{
background:#111;
padding:20px;
text-align:center;
}


@media(max-width:700px){

.hero h1{
font-size:35px;
}

nav{
display:none;
}

}

</style>

</head>


<body>


<header>

<div class="logo">
Raza Digital Agency
</div>

<nav>
<a href="#home">Home</a>
<a href="#services">Services</a>
<a href="#pricing">Pricing</a>
<a href="#contact">Contact</a>
</nav>

</header>



<section class="hero" id="home">

<div>

<h1>
We Build Modern Websites
</h1>

<p>
Professional Website Development For Your Business
</p>


<a class="btn" href="#contact">
Get Started
</a>

</div>

</section>



<section id="services">

<h1 class="title">
Our Services
</h1>


<div class="cards">


<div class="card">
<h2>
Website Development
</h2>
<p>
Modern responsive websites for businesses.
</p>
</div>


<div class="card">
<h2>
Landing Pages
</h2>
<p>
High quality pages to increase sales.
</p>
</div>


<div class="card">
<h2>
Website Design
</h2>
<p>
Beautiful UI designs with modern look.
</p>
</div>


</div>

</section>



<section id="pricing">

<h1 class="title">
Pricing
</h1>


<div class="cards">


<div class="card">
<h2>Basic</h2>
<div class="price">
Rs 5000
</div>
<p>
One page website
</p>
</div>


<div class="card">
<h2>Standard</h2>
<div class="price">
Rs 10000
</div>
<p>
Business website
</p>
</div>


<div class="card">
<h2>Premium</h2>
<div class="price">
Rs 20000
</div>
<p>
Full professional website
</p>
</div>


</div>

</section>



<section id="contact">

<h1 class="title">
Contact Us
</h1>


<center>

<input placeholder="Your Name">

<br>

<input placeholder="Email">

<br>

<textarea placeholder="Your Message"></textarea>

<br>

<button>
Send
</button>


</center>


</section>



<footer>

<p>
WhatsApp: 03127347728
</p>

<p>
© 2026 Raza Digital Agency
</p>

</footer>



<a class="whatsapp" href="https://wa.me/923127347728">
WhatsApp
</a>


</body>
</html>
