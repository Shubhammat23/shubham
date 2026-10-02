<!DOCTYPE html>
<html>
<head>
    <title>For You ❤️</title>
    <style>
        body {
            margin: 0;
            overflow: hidden;
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
            text-align: center;
            color: #fff;
        }

        h1 {
            margin-top: 100px;
            font-size: 40px;
        }

        p {
            font-size: 20px;
        }

        button {
            padding: 12px 25px;
            font-size: 18px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            margin: 10px;
        }

        #yesBtn {
            background-color: #28a745;
            color: white;
        }

        #noBtn {
            background-color: #dc3545;
            color: white;
            position: absolute;
        }

        #question {
            display: none;
            margin-top: 50px;
        }

        .flower {
            position: absolute;
            font-size: 24px;
            animation: fall linear infinite;
        }

        @keyframes fall {
            0% { transform: translateY(-100px); }
            100% { transform: translateY(100vh); }
        }
    </style>
</head>
<body>

    <h1>Hey Beautiful 🫶</h1>
    <p>How was your day? 💫</p>

    <button onclick="showQuestion()">Click for a surprise 👀</button>

    <div id="question">
        <h2>Did you miss me today? 😌</h2>
        <button id="yesBtn" onclick="showLove()">Yes ❤️</button>
        <button id="noBtn">No 😏</button>
    </div>

    <script>
        function showQuestion() {
            document.getElementById("question").style.display = "block";
        }

        const noBtn = document.getElementById("noBtn");

        noBtn.addEventListener("mouseover", () => {
            const x = Math.random() * (window.innerWidth - 100);
            const y = Math.random() * (window.innerHeight - 50);
            noBtn.style.left = x + "px";
            noBtn.style.top = y + "px";
        });

        function showLove() {
            document.body.innerHTML = "<h1 style='margin-top:200px;'>I knew it 😍❤️</h1>";
            startFlowers();
        }

        function startFlowers() {
            setInterval(() => {
                let flower = document.createElement("div");
                flower.classList.add("flower");
                flower.innerHTML = "🌸";
                flower.style.left = Math.random() * window.innerWidth + "px";
                flower.style.animationDuration = (Math.random() * 3 + 2) + "s";
                document.body.appendChild(flower);

                setTimeout(() => {
                    flower.remove();
                }, 5000);
            }, 200);
        }
    </script>

</body>
</html>
