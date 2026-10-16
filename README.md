<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>I'm Sorry ❤️</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background:linear-gradient(135deg,#ffd6e0,#ffe8f0,#fff5f7);
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    padding:30px;
}

.container{
    max-width:800px;
    background:#fff;
    border-radius:25px;
    padding:45px;
    box-shadow:0 20px 50px rgba(0,0,0,.15);
    text-align:center;
}

h1{
    color:#ff4d79;
    margin-bottom:10px;
    font-size:2.3rem;
}

h2{
    color:#ff6699;
    margin:20px 0;
}

p{
    font-size:18px;
    line-height:1.9;
    color:#555;
    margin:18px 0;
}

.highlight{
    color:#ff3366;
    font-weight:bold;
}

.quote{
    font-size:22px;
    color:#ff4d79;
    font-weight:bold;
    margin:30px 0;
}

button{
    margin-top:30px;
    padding:16px 40px;
    border:none;
    border-radius:50px;
    background:#ff4d79;
    color:white;
    font-size:18px;
    cursor:pointer;
    transition:.3s;
}

button:hover{
    transform:scale(1.05);
    background:#ff1f5b;
}

#surprise{
    display:none;
    margin-top:35px;
    padding:25px;
    background:#fff0f5;
    border-radius:20px;
    animation:fadeIn 1s ease;
}

#surprise h2{
    color:#ff3366;
}

#surprise p{
    color:#555;
}

.hearts{
    font-size:30px;
    margin-top:20px;
}

.footer{
    margin-top:30px;
    color:#888;
    font-style:italic;
}

@keyframes fadeIn{
    from{
        opacity:0;
        transform:translateY(20px);
    }
    to{
        opacity:1;
        transform:translateY(0);
    }
}
</style>

</head>

<body>

<div class="container">

<h1>💖 To the Most Beautiful Smile in My World 💖</h1>

<h2>I'm Truly Sorry ❤️</h2>

<p>
If you're reading this, it means I wanted to do something a little different
to tell you something that I should have said better...
</p>

<p class="highlight">
I'm sorry.
</p>

<p>
I know I made a mistake.
It may have seemed like a small thing to me at that moment,
but I understand that it hurt you
and that's what matters.
I never wanted to be the reason you felt upset or disappointed.
</p>

<p>
You deserve to be listened to,
understood
and treated with care.
If I failed to do that,
then I'm genuinely sorry.
</p>

<p>
One thing I've realized is that
no argument,
no misunderstanding
and no silly mistake
is ever more important than <span class="highlight">YOU.</span>


</p>

<h2>❤️ There's something I don't say enough... ❤️</h2>

<p class="quote">
I absolutely love your smile.
</p>

<p>
It's my favorite part of every conversation.

You look unbelievably cute when you smile
and seeing that smile disappear because of something I did
honestly hurts me more than I can explain.
</p>

<p>
I know an apology doesn't magically fix everything,
and I'm not expecting you to forgive me instantly.

I just want you to know that
I'm taking responsibility for what happened
and I'm willing to make it right—
not just with words,
but with my actions.
</p>

<p>
Thank you for being patient with me,
and for being someone so incredibly special in my life.
</p>

<p>
If you're still upset,
I'll understand.

If you need time,
I'll respect that.

But please don't ever doubt
how much you mean to me.
</p>

<h2>❤️ Just one little request... ❤️</h2>

<p>
Whenever your heart feels ready...
click the button below.
</p>

<button onclick="forgiveMe()">
💖 Click to Forgive Me 💖
</button>

<div id="surprise">

<h2>🥹 Thank You ❤️</h2>

<p>
I won't lie...
seeing this button being clicked
already makes me smile.
</p>

<p>
Thank you for giving my apology a place in your heart.
</p>

<p>
I know trust is built through actions,
not promises.

So I'll let my actions show you
how much you mean to me.
</p>

<p class="quote">
Please give me that beautiful smile again. 😊❤️
</p>

<p>
Because my day feels brighter,
my heart feels lighter
and everything feels a little more complete
when you're smiling.
</p>

<p>
No matter how many little storms come our way,
I'll always choose <span class="highlight">US.</span>
</p>

<p>
Keep smiling...

Keep missing me just a little...

Because I'm definitely missing you much more. ❤️
</p>

<div class="hearts">
❤️ 💕 🌹 🥰 🌸 💖
</div>

</div>

<div class="footer">
Forever cheering for your smile. ❤️
</div>

</div>

<script>
function forgiveMe() {
    const surprise = document.getElementById("surprise");

    surprise.style.display = "block";

    surprise.scrollIntoView({
        behavior: "smooth"
    });

    // Confetti hearts
    for(let i=0;i<30;i++){
        let heart=document.createElement("div");
        heart.innerHTML="❤️";
        heart.style.position="fixed";
        heart.style.left=Math.random()*100+"vw";
        heart.style.top="-20px";
        heart.style.fontSize=(20+Math.random()*20)+"px";
        heart.style.animation="fall "+(3+Math.random()*3)+"s linear forwards";
        document.body.appendChild(heart);

        setTimeout(()=>{
            heart.remove();
        },6000);
    }
}
</script>

<style>
@keyframes fall{
    to{
        transform:translateY(110vh) rotate(360deg);
        opacity:0;
    }
}
</style>

</body>
</html>
