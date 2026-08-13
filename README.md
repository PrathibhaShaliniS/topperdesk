# topperdesk
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>TopperDisk</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

body{
    background:skyblue;
    color:skyblue;
}

/* Navigation */

header{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 8%;
    background:white;
    box-shadow:0 2px 10px rgba(0,0,0,0.1);
}

.logo{
    font-size:32px;
    font-weight:bold;
    color:#1565ff;
}

nav a{
    text-decoration:none;
    margin-left:25px;
    color:#333;
    font-weight:bold;
}

.login{
    background:#1565ff;
    color:white;
    padding:10px 20px;
    border-radius:25px;
}

/* Hero */

.hero{
    height:90vh;
    display:flex;
    justify-content:center;
    align-items:center;
    flex-direction:column;
    text-align:center;
    background:linear-gradient(135deg,#1565ff,#5ca9ff);
    color:white;
}

.hero h1{
    font-size:60px;
}

.hero p{
    margin-top:20px;
    font-size:22px;
    max-width:700px;
}

.hero button{
    margin-top:35px;
    padding:15px 35px;
    border:none;
    border-radius:30px;
    background:white;
    color:#1565ff;
    font-size:18px;
    cursor:pointer;
}

/* Sections */

section{
    padding:70px 10%;
}

.title{
    text-align:center;
    color:#1565ff;
    font-size:38px;
    margin-bottom:20px;
}

.subtitle{
    text-align:center;
    max-width:700px;
    margin:auto;
    margin-bottom:40px;
}

/* Cards */

.container{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:30px;
}

.card{
    background:white;
    padding:30px;
    border-radius:15px;
    box-shadow:0 5px 20px rgba(0,0,0,.08);
    text-align:center;
}

.card h3{
    color:#1565ff;
    margin-bottom:15px;
}

.card p{
    margin-bottom:20px;
}

.card button{
    padding:10px 25px;
    border:none;
    background:#1565ff;
    color:white;
    border-radius:25px;
    cursor:pointer;
}

/* Mentorship */

.banner{
    background:#1565ff;
    color:white;
    text-align:center;
    padding:60px 20px;
}

.banner h2{
    font-size:38px;
}

.banner p{
    margin:20px auto;
    max-width:700px;
}

.banner button{
    padding:15px 35px;
    border:none;
    border-radius:30px;
    background:white;
    color:#1565ff;
    cursor:pointer;
}

/* Footer */

footer{
    background:#0d1b3d;
    color:white;
    text-align:center;
    padding:35px;
}

footer a{
    color:white;
    text-decoration:none;
    margin:0 15px;
}

</style>

</head>

<body>

<header>

<div class="logo">
TopperDisk
</div>

<nav>

<a href="#">About Us</a>

<a href="#" class="login">Login</a>

</nav>

</header>

<!-- Hero -->

<div class="hero">

<h1>Welcome to TopperDisk</h1>

<p>

Your Ultimate Learning Companion.

Get quality study resources,
formula sheets,
expert mentorship,
and discussions with achievers.

</p>

<button>Get Started</button>

</div>

<!-- About -->

<section>

<h2 class="title">
About TopperDisk
</h2>

<p class="subtitle">

TopperDisk is an educational platform built to help students
prepare smarter by providing quality study resources,
mentorship, and an interactive learning community.

</p>

</section>

<!-- Features -->

<section>

<h2 class="title">
Our Resources
</h2>

<div class="container">

<div class="card">

<h3>📚 Notes</h3>

<p>

Access well-organized study notes prepared by experts.

</p>

<button>Browse Notes</button>

</div>

<div class="card">

<h3>📄 Formula Sheets</h3>

<p>

Quick revision sheets for important concepts.

</p>

<button>View Sheets</button>

</div>

<div class="card">

<h3>💬 Q/A Discussions</h3>

<p>

Interact with achievers and clear your doubts.

</p>

<button>Join Now</button>

</div>

</div>

</section>

<!-- Mentorship -->

<div class="banner">

<h2>

Expert Mentorship

</h2>

<p>

Book one-to-one mentorship sessions with experienced mentors
and build your personalized preparation strategy.

</p>

<button>

Book Mentorship

</button>

</div>

<!-- Footer -->

<footer>

<h3>TopperDisk</h3>

<br>

<a href="#">About Us</a>

<a href="#">Privacy Policy</a>

<a href="#">Contact</a>

<br><br>

<p>

© 2026 TopperDisk. All Rights Reserved.

</p>

</footer>

</body>
</html>
