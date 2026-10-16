<html lang="en">
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title> To the Most Beautiful Smile in My World.... 
    Sorry Duggu ki mummy ❤️</title>

<style>

*{
    box-sizing:border-box;
}

body{
    margin:0;
    padding:20px;
    font-family:'Segoe UI', Arial, sans-serif;
    background:linear-gradient(135deg,#ffd6e0,#ffeef3,#fff);
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:flex-start;
}


.container{

    width:100%;
    max-width:750px;
    background:white;
    border-radius:25px;
    padding:35px 25px;
    margin:20px auto;

    box-shadow:
    0 15px 40px rgba(0,0,0,0.15);

    text-align:center;
}



h1{

    color:#ff477e;
    font-size:32px;
    margin-bottom:15px;

}


h2{

    color:#ff6699;
    margin:25px 0;

}


p{

    color:#555;
    font-size:18px;
    line-height:1.8;
    margin:18px 0;

}


.highlight{

    color:#ff3366;
    font-weight:bold;

}


.quote{

    font-size:23px;
    color:#ff477e;
    font-weight:bold;

}



button{

    margin-top:30px;
    background:#ff477e;
    color:white;

    border:none;
    border-radius:50px;

    padding:16px 35px;

    font-size:18px;

    cursor:pointer;

    transition:0.3s;

}


button:hover{

    transform:scale(1.07);
    background:#ff1f63;

}



#surprise{

    display:none;

    margin-top:35px;

    padding:25px;

    background:#fff2f6;

    border-radius:20px;

    animation:appear 1s ease;

}



.hearts{

    font-size:30px;
    margin-top:20px;

}



.footer{

    margin-top:30px;

    font-style:italic;

    color:#888;

}



.typing{

    overflow:hidden;

    white-space:nowrap;

    animation:
    typing 3s steps(40),
    blink .7s infinite;

    border-right:3px solid #ff477e;

}


@keyframes typing{

from{
width:0;
}

to{
width:100%;
}

}


@keyframes blink{

50%{
border-color:transparent;
}

}



@keyframes appear{

from{

opacity:0;
transform:translateY(30px);

}

to{

opacity:1;
transform:translateY(0);

}

}



.floating-heart{

position:fixed;

top:-20px;

font-size:25px;

animation:fall linear forwards;

}



@keyframes fall{

to{

transform:translateY(110vh) rotate(360deg);

opacity:0;

}

}



@media(max-width:768px){


body{

padding:12px;

}


.container{

padding:25px 18px;

}



h1{

font-size:26px;

}


h2{

font-size:22px;

}


p{

font-size:16px;

line-height:1.7;

}


.quote{

font-size:20px;

}


button{

width:100%;

}



}



</style>

</head>


<body>


<div class="container">


<h1 class="typing">
💖 To the Most Beautiful Smile in My World....
    Duggu ki mummy 💖
</h1>


<h2>
I'm Truly Sorry ❤️
</h2>


<p>

I wanted to do something special instead of just saying a simple sorry.

So here I am, trying to tell you what I should have said properly...

</p>



<p class="highlight">

I'm sorry.

</p>



<p>

I know I made a mistake.

Maybe it felt like a small thing to me at that moment,
but I understand that it affected you and your feelings matter to me.

I never wanted to be the reason behind your sadness or your silence.

</p>



<p>

You deserve to be heard, understood and care for.

If my actions made you feel otherwise,
I genuinely apologise.

</p>




<h2>
❤️ One thing I want you to know ❤️
</h2>



<p>

No silly misunderstanding, argument or a mistake
is more important than the bond we share.

I would rather accept my mistake than let something small create distance between us.

</p>



<p class="quote">

Your smile is my favourite thing. 😊

</p>



<p>

You look incredibly cute when you smile,
and honestly, I hate seeing you angry because I miss that beautiful smile.

Seeing you happy makes everything feel better.

</p>




<p>

I know saying sorry cannot instantly fix everything.

I don't expect you to forget it immediately.

I just want you to know that I understand my mistake
and I'll try to be better through my actions.

</p>



<p>

Thank you for being patient with me
and for being such a special person in my life.

</p>



<p>

If you are still upset, I understand.

If you need some time, I'll respect that.

But please remember...

You mean a lot to me.

</p>




<h2>
🌸 A small request 🌸
</h2>


<p>

Whenever your heart feels ready...

click the button below.

</p>



<button onclick="forgiveMe()">

❤️ Click to Forgive Me ❤️

</button>




<div id="surprise">


<h2>
🥹 Thank You ❤️
</h2>


<p>

This little click means more than you know.

I'll remember this moment and make sure my actions show how much I value you.

</p>


<p class="quote">

Can I please have that beautiful smile back? 😊

</p>



<p>

Keep smiling...

Keep being the amazing person you are...

And maybe miss me just a little...

Because I definitely miss you. ❤️

</p>


<div class="hearts">

❤️ 💕 🌸 🥰 🌹

</div>



</div>




<div class="footer">

No matter how many small storms come our way,
I'll always choose understanding, patience and us.

<br><br>

Your very sorry idiot ❤️

</div>



</div>



<script>


function forgiveMe(){


document.getElementById("surprise").style.display="block";


document.getElementById("surprise")
.scrollIntoView({

behavior:"smooth"

});



for(let i=0;i<35;i++){


let heart=document.createElement("div");


heart.innerHTML="❤️";


heart.className="floating-heart";


heart.style.left=Math.random()*100+"vw";


heart.style.animationDuration=
(3+Math.random()*3)+"s";


document.body.appendChild(heart);



setTimeout(()=>{

heart.remove();

},6000);



}



}


</script>



</body>

</html>
