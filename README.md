<!DOCTYPE html>
<html>
<head>
<title>Dream Decorations</title>

<style>

body{
margin:0;
font-family:Arial;
background:linear-gradient(to right,#ff9a9e,#fad0c4);
text-align:center;
}

header{
background:#ff4081;
color:white;
padding:20px;
font-size:30px;
font-weight:bold;
}

.hero{
padding:60px;
color:white;
}

.hero h1{
font-size:50px;
}

button{
background:#25D366;
color:white;
border:none;
padding:12px 22px;
font-size:16px;
border-radius:6px;
cursor:pointer;
}

/* scrolling motivation */

.scroll-text{
background:white;
color:#ff4081;
font-size:14px;
padding:6px;
white-space:nowrap;
overflow:hidden;
}

.scroll-text p{
display:inline-block;
padding-left:100%;
animation:scroll 12s linear infinite;
}

@keyframes scroll{
0%{transform:translateX(0);}
100%{transform:translateX(-100%);}
}

/* services */

.services{
display:flex;
justify-content:center;
gap:20px;
margin:40px;
flex-wrap:wrap;
}

.card{
background:white;
padding:20px;
border-radius:10px;
width:250px;
box-shadow:0 5px 10px rgba(0,0,0,0.2);
transition:0.4s;
cursor:pointer;
}

.card:hover{
transform:translateY(-10px) scale(1.05);
box-shadow:0 10px 20px rgba(0,0,0,0.3);
}

.card:active{
transform:scale(0.95);
box-shadow:0 0 20px #ff4081;
}

.card img{
width:100%;
border-radius:10px;
}

/* instagram */

.instagram{
margin-top:10px;
}

.instagram a{
color:#ff4081;
font-weight:bold;
text-decoration:none;
}

/* privacy */

.privacy{
max-width:800px;
margin:20px auto;
background:white;
padding:20px;
border-radius:10px;
box-shadow:0 4px 10px rgba(0,0,0,0.2);
font-size:14px;
line-height:1.6;
}

/* footer */

footer{
background:#333;
color:white;
padding:15px;
margin-top:30px;
}

/* balloons */

.balloon{
position:absolute;
bottom:-150px;
width:50px;
height:70px;
border-radius:50%;
animation:float 8s infinite;
}

.balloon:nth-child(1){left:10%;background:yellow;}
.balloon:nth-child(2){left:30%;background:blue;}
.balloon:nth-child(3){left:50%;background:green;}
.balloon:nth-child(4){left:70%;background:pink;}
.balloon:nth-child(5){left:90%;background:orange;}

@keyframes float{
0%{transform:translateY(0);}
100%{transform:translateY(-900px);}
}

</style>
</head>

<body>

<header>
🎉 DREAM DECORATIONS
</header>

<div class="scroll-text">
<p>🎂 Every birthday is a new beginning • Celebrate life • Make memories • Dream big • Enjoy your special day 🎉</p>
</div>

<div class="hero">
<h1>Make Your Birthday Special 🎂</h1>
<p>Beautiful Balloon Decorations | Theme Parties | Surprise Setup</p>

<a href="https://wa.me/918088230300?text=Hi%20I%20want%20to%20book%20birthday%20decoration">
<button>Book Your Decoration</button>
</a>

</div>

<h2>Our Services</h2>

<div class="services">

<div class="card">
<img src="https://images.unsplash.com/photo-1607083206968-13611e3d76db">
<h3>Balloon Decoration</h3>
<p>Colorful balloon arches and room decorations.</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1527529482837-4698179dc6ce">
<h3>Theme Party</h3>
<p>Cartoon, princess, superhero birthday themes.</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1513151233558-d860c5398176">
<h3>Surprise Setup</h3>
<p>Romantic and surprise birthday decorations.</p>
</div>

</div>

<h2>Contact Us</h2>

<div class="instagram">
📸 Instagram :
<a href="https://instagram.com/dream_decorate_blr" target="_blank">
dream_decorate_blr
</a>
</div>
<p>Email :dreamdecorate264@gmail.com</p>
<p>📞 Phone: 8088230300</p>
<p>📍 Location: Bangalore</p>

<h3>
<a href="#" onclick="togglePrivacy()" style="color:#ff4081;text-decoration:none;">
Privacy Policy
</a>
</h3>

<div id="privacyBox" class="privacy" style="display:none;">

<p>
Dream Decorations respects your privacy. Any information shared through WhatsApp or contact is used only for booking birthday decoration services.
</p>

<p>
We do not share your personal information with third parties.
</p>

<p>
For privacy concerns please contact <b>8088230300</b>.
</p>

</div>

<footer>
© 2026 Dream Decorations | All Rights Reserved
</footer>

<div class="balloon"></div>
<div class="balloon"></div>
<div class="balloon"></div>
<div class="balloon"></div>
<div class="balloon"></div>

<script>

function togglePrivacy(){
var box=document.getElementById("privacyBox");

if(box.style.display==="none"){
box.style.display="block";
}else{
box.style.display="none";
}

}

</script>

</body>
</html>
