<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For My Baby 💖</title>

<style>
body {
    margin: 0;
    font-family: 'Comic Sans MS', cursive;
    text-align: center;
    background: linear-gradient(to bottom, #ffe6f2, #fff0f5);
    overflow-x: hidden;
}

/* Envelope */
.envelope {
    width: 220px;
    height: 140px;
    background: #ff8fcf;
    margin: 150px auto;
    position: relative;
    border-radius: 15px;
    cursor: pointer;
    box-shadow: 0 10px 25px rgba(0,0,0,0.2);
    animation: bounce 2s infinite;
}

.envelope:before {
    content: "";
    position: absolute;
    top: -70px;
    left: 0;
    width: 0;
    height: 0;
    border-left: 110px solid transparent;
    border-right: 110px solid transparent;
    border-bottom: 70px solid #ff5ca8;
}

.open-text {
    color: white;
    font-size: 20px;
    padding-top: 50px;
    font-weight: bold;
}

@keyframes bounce {
    0% { transform: translateY(0px); }
    50% { transform: translateY(-12px); }
    100% { transform: translateY(0px); }
}

/* Hidden Content */
#content {
    display: none;
    padding: 15px;
}

h1 {
    color: #ff2e8b;
    font-size: 30px;
}

.stickers img {
    width: 90px;
    margin: 8px;
    animation: float 3s infinite ease-in-out;
}

@keyframes float {
    0% { transform: translateY(0px); }
    50% { transform: translateY(-15px); }
    100% { transform: translateY(0px); }
}

.box {
    background: white;
    padding: 20px;
    margin: 18px;
    border-radius: 20px;
    box-shadow: 0 6px 18px rgba(255,105,180,0.2);
}

button {
    background: #ff4da6;
    color: white;
    border: none;
    padding: 12px 18px;
    border-radius: 25px;
    font-size: 16px;
    margin: 6px;
    cursor: pointer;
}

button:hover {
    background: #ff1a8c;
}
</style>
</head>

<body>

<!-- Envelope -->
<div class="envelope" onclick="openLetter()">
    <div class="open-text">💌 Tap to Open Baby</div>
</div>

<!-- Main Surprise -->
<div id="content">

<h1>🎂 Happy Birthday My Baby, My LOML 💖</h1>

<!-- Cute Stickers -->
<div class="stickers">
    <img src="https://media.giphy.com/media/3oriO0OEd9QIDdllqo/giphy.gif">
    <img src="https://media.giphy.com/media/l0MYt5jPR6QX5pnqM/giphy.gif">
    <img src="https://media.giphy.com/media/26BRv0ThflsHCqDrG/giphy.gif">
    <img src="https://media.giphy.com/media/MDJ9IbxxvDUQM/giphy.gif">
</div>

<!-- Funny Wishes -->
<div class="box">
<h2>😂 Funny Birthday Wishes for My Kuchuuupuchuuuuuuuuuuuuuuuuu</h2>
<p>
Happy Birthday my baby 😚💖  
My cookie 🍪, my loml, my cutest kuchuuupuchuuuuuuuuuuuuuuuuu!!!  
You are getting older but don’t worry…  
you are still my most adorable human (and my personal drama king 😌😂).  
<br><br>
I love you more than food, sleep, and even my phone  
(and that is VERY serious love 😤💘)
</p>
</div>

<!-- Love Quiz -->
<div class="box">
<h2>💞 Official Love Quiz (Only for My Baby)</h2>

<p>1. Who is my LOML?</p>
<button onclick="alert('Correct answer 😍 It is YOU my baby 💖')">A) My Baby 💕</button>
<button onclick="alert('Noooo 😤 Only YOU!')">B) Pizza 🍕</button>
<button onclick="alert('Impossible 😭')">C) Sleep 😴</button>

<p><br>2. What are you to me?</p>
<button onclick="alert('YESSS! My everything 🥺💞')">A) My Everything 💗</button>
<button onclick="alert('Wrong answer cookie 😤')">B) Just a person</button>
<button onclick="alert('Hehe wrong 🤭')">C) My enemy</button>

<p><br>3. How much do I love you my cookie?</p>
<button onclick="alert('Infinity love for my kuchuuupuchuuuuuuuuuu 💘')">A) Infinity ♾️</button>
<button onclick="alert('Still wrong! I love you MORE 😭💖')">B) A little</button>
<button onclick="alert('Nopeee 😤')">C) Medium</button>
</div>

<!-- Love Letter -->
<div class="box">
<h2>💌 A Love Letter for My Baby, My Cookie 🍪</h2>
<p>
My dearest baby, my LOML, my sweet cookie, my kuchuuupuchuuuuuuuuuuuuuuuuu 💖🥺  
<br><br>
On your birthday, I just want to say thank you.  
Thank you for being in my life, for loving me, for caring for me, and for making my days so much brighter. ✨  
<br><br>
You are not just my boyfriend, you are my comfort, my happiness, my safe place, and my biggest blessing.  
Every moment with you feels special and magical. 💞  
<br><br>
I am so grateful for your love, your patience, your smile, and your presence in my life.  
You make my heart feel full in ways I can’t even explain. 🥹💗  
<br><br>
My baby, you are truly the love of my life.  
My everything. My forever. My heart. 💘  
<br><br>
I love you more than all the stars, more than all the flowers, and more than all the cookies in the world 🍪🌸  
(which is A LOT!!! 😭💖)  
<br><br>
Happy Birthday again my loml 💕  
Forever yours,  
Your loving person who loves you the most 💗
</p>
</div>

</div>

<script>
function openLetter() {
    document.querySelector('.envelope').style.display = 'none';
    document.getElementById('content').style.display = 'block';
}
</script>

</body>
</html>
