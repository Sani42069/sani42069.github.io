
<html>
<head>
    <title>Valentine Proposal 💖</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            background-color: #ffccd5;
            margin-top: 100px;
        }

        h1 {
            color: #d6336c;
            font-size: 40px;
        }

        .btn {
            padding: 12px 25px;
            font-size: 18px;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            margin: 20px;
            transition: 0.3s;
        }

        #yes {
            background-color: #ff4d6d;
            color: white;
        }

        #no {
            background-color: #6c757d;
            color: white;
            position: absolute;
        }

        #message {
            font-size: 24px;
            color: #880e4f;
            margin-top: 30px;
        }
    </style>
</head>
<body>

    <h1>Will You Be My Valentine? 💘</h1>

    <button id="yes" class="btn">Yes 💖</button>
    <button id="no" class="btn">No 😢</button>

    <div id="message"></div>

    <script>
        const yesBtn = document.getElementById("yes");
        const noBtn = document.getElementById("no");
        const message = document.getElementById("message");

        yesBtn.addEventListener("click", function() {
            message.innerHTML = "🎉 Congratulations! 💖<br>Welcome to my life! ❤️✨";
        });

        noBtn.addEventListener("mouseover", function() {
            const x = Math.random() * window.innerWidth;
            const y = Math.random() * window.innerHeight;
            noBtn.style.left = x + "px";
            noBtn.style.top = y + "px";
        });
    </script>

</body>
</html>
