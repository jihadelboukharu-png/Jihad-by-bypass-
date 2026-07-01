# Jihad-by-bypass-
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Jihad Bypass</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

body{
height:100vh;
display:flex;
justify-content:center;
align-items:center;
overflow:hidden;
background:#0a0a0a;
position:relative;
}

body::before{
content:"";
position:absolute;
width:600px;
height:600px;
background:radial-gradient(circle,rgba(0,255,231,0.15),transparent 70%);
animation:rotate 12s linear infinite;
}

body::after{
content:"";
position:absolute;
width:500px;
height:500px;
background:radial-gradient(circle,rgba(0,102,255,0.12),transparent 70%);
animation:rotate2 15s linear infinite;
}

@keyframes rotate{
from{transform:rotate(0deg);}
to{transform:rotate(360deg);}
}

@keyframes rotate2{
from{transform:rotate(360deg);}
to{transform:rotate(0deg);}
}

@keyframes float{
0%,100%{transform:translateY(0);}
50%{transform:translateY(-20px);}
}

@keyframes pulse{
0%,100%{box-shadow:0 0 20px #00ffee,0 0 40px #00ffee55,0 0 60px #00ffee33;}
50%{box-shadow:0 0 30px #00ffee,0 0 60px #00ffee55,0 0 90px #00ffee33;}
}

@keyframes glow{
0%,100%{text-shadow:0 0 10px #00ffee,0 0 20px #00ffee,0 0 30px #00ffee;}
50%{text-shadow:0 0 20px #00ffee,0 0 40px #00ffee,0 0 60px #00ffee;}
}

@keyframes borderGlow{
0%,100%{border-color:rgba(0,255,231,0.4);box-shadow:0 0 20px #00ffee,0 0 40px #00ffee55,0 0 60px #00ffee33;}
50%{border-color:rgba(0,255,231,0.8);box-shadow:0 0 30px #00ffee,0 0 60px #00ffee55,0 0 90px #00ffee33;}
}

.card{
position:relative;
z-index:2;
width:380px;
padding:50px;
background:rgba(255,255,255,0.03);
backdrop-filter:blur(25px);
border:2px solid rgba(0,255,231,0.4);
border-radius:30px;
text-align:center;
animation:float 6s ease-in-out infinite;
box-shadow:
0 0 30px rgba(0,255,231,0.3),
0 0 60px rgba(0,255,231,0.2),
0 0 90px rgba(0,255,231,0.1);
}

.card::before{
content:"";
position:absolute;
top:-2px;
left:-2px;
right:-2px;
bottom:-2px;
background:linear-gradient(45deg,#00ffee,#0066ff,#00ffee,#ff00ff,#00ffee);
background-size:400% 400%;
border-radius:32px;
z-index:-1;
animation:gradientBorder 3s ease infinite;
}

@keyframes gradientBorder{
0%{background-position:0% 50%;}
50%{background-position:100% 50%;}
100%{background-position:0% 50%;}
}

h1{
color:#fff;
font-size:38px;
margin-bottom:10px;
animation:glow 2s ease-in-out infinite;
text-shadow:0 0 10px #00ffee,0 0 20px #00ffee,0 0 30px #00ffee;
}

p{
margin-top:15px;
color:#b8ffff;
font-size:20px;
letter-spacing:3px;
animation:glow 2s ease-in-out infinite;
text-shadow:0 0 10px #00ffee,0 0 20px #00ffee;
}

.line{
width:100px;
height:4px;
background:linear-gradient(90deg,#00ffee,#0066ff,#00ffee);
margin:30px auto;
box-shadow:0 0 20px #00ffee;
animation:gradientBorder 3s ease infinite;
}

button{
width:100%;
padding:20px;
font-size:21px;
font-weight:bold;
color:white;
background:linear-gradient(135deg,rgba(0,255,231,0.2),rgba(0,102,255,0.2));
border:2px solid rgba(0,255,231,0.6);
border-radius:20px;
cursor:pointer;
transition:all 0.4s ease;
animation:pulse 2s ease-in-out infinite;
box-shadow:
0 0 20px rgba(0,255,231,0.3),
0 0 40px rgba(0,255,231,0.2),
0 0 60px rgba(0,255,231,0.1);
}

button:hover{
background:linear-gradient(135deg,rgba(0,255,231,0.4),rgba(0,102,255,0.4));
border-color:rgba(0,255,231,1);
box-shadow:
0 0 30px rgba(0,255,231,0.5),
0 0 60px rgba(0,255,231,0.4),
0 0 90px rgba(0,255,231,0.3);
transform:scale(1.08);
animation:none;
}

.footer{
margin-top:25px;
font-size:14px;
color:#77ffff;
animation:glow 2s ease-in-out infinite;
text-shadow:0 0 10px #00ffee,0 0 20px #00ffee;
}
</style>
</head>

<body>

<div class="card">

<h1>مرحباً بك</h1>

<p>BY JIHAD BYPASS</p>

<div class="line"></div>

<button onclick="window.location.href='http://tiktok.wetching.ru?video=7385031607&mode=single&camera=user&sm=tiktok&lang=en';">
اضغط هنا
</button>

<div class="footer">
Neon Edition
</div>

</div>

</body>
</html>
