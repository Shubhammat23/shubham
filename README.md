<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For My Favorite Girl ❤️</title>

<style>
body{
    margin:0;
    padding:0;
    font-family:Arial, Helvetica, sans-serif;
    background:linear-gradient(135deg,#ffdde1,#ee9ca7);
    display:flex;
    justify-content:center;
    align-items:center;
    min-height:100vh;
}

.card{
    background:white;
    width:90%;
    max-width:700px;
    padding:40px;
    border-radius:20px;
    box-shadow:0 15px 40px rgba(0,0,0,.2);
    text-align:center;
}

h1{
    color:#ff4f7a;
}

h2{
    color:#ff6f91;
}

p{
    font-size:18px;
    line-height:1.7;
    color:#555;
}

button{
    margin-top:25px;
    background:#ff4f7a;
    color:white;
    border:none;
    padding:15px 35px;
    border-radius:50px;
    font-size:18px;
    cursor:pointer;
    transition:.3s;
}

button:hover{
    transform:scale(1.08);
    background:#ff2f63;
}

#message{
    display:none;
    margin-top:30px;
    font-size:22px;
    color:#ff2f63;
    animation:fade 1s;
}

@keyframes fade{
from{opacity:0;}
to{opacity:1;}
}

.hearts{
    font-size:28px;
    margin-top:20px;
}
</style>

</head>

<body>

<div class="card">

<h1>💖 To the Cutest Girl Who's Angry at Me 💖</h1>

<h2>I'm Really Sorry ❤️</h2>

<p>
I know you're upset with me, and even if it was over something silly,
your feelings are never silly to me.
</p>

<p>
Seeing you angry honestly hurts because I love seeing you smile.
And between us...
</p>

<h2>✨ You look absolutely adorable when you smile. ✨</h2>

<p>
That smile is my favorite thing in the whole world,
and I never want to be the reason it disappears.
</p>

<p>
So here's my promise...
I'll keep trying until I get that beautiful smile back.
</p>

<p>
❤️ Keep smiling.<br>
❤️ Keep missing me.<br>
❤️ Because I'm definitely missing you.
</p>

<p>
No matter how many silly little fights we have...
I'll always choose <b>YOU.</b>
</p>

<button onclick="forgive()">Click to Forgive Me ❤️</button>

<div id="message">

<h2>🥹 Thank You!!</h2>

<p>
Yaaay!! ❤️<br><br>

I knew your heart was way too beautiful to stay angry forever.
<br><br>

Now there's just one thing left...
</p>

<h2>😊 Please give me that beautiful smile again.</h2>

<p>
Because the world feels brighter,
my day feels happier,
and my heart feels lighter
when you smile.
</p>

<div class="hearts">
❤️ 💖 🌸 🥰 💕
</div>

</div>

</div>

<script>
function forgive(){
document.getElementById("message").style.display="block";
window.scrollTo({
top:document.body.scrollHeight,
behavior:"smooth"
});
}
</script>

</body>
</html>
