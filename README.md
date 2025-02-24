#ninjasuprio
<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Marry Me?</title>
    <style>
        body {
            text-align: center;
            background: url('https://source.unsplash.com/1600x900/?love,romance') no-repeat center center/cover;
            font-family: Arial, sans-serif;
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        h1 {
            font-size: 3em;
            background: rgba(0, 0, 0, 0.5);
            padding: 10px;
            border-radius: 10px;
        }
        .buttons {
            margin-top: 20px;
        }
        button {
            font-size: 1.5em;
            padding: 10px 20px;
            margin: 10px;
            border: none;
            cursor: pointer;
            border-radius: 10px;
        }
        #yes {
            background-color: #28a745;
            color: white;
        }
        #no {
            background-color: #dc3545;
            color: white;
            position: absolute;
        }
    </style>
</head>
<body>
    <h1>Will You Marry Me? 💍❤️</h1>
    <div class="buttons">
        <button id="yes" onclick="alert('Yay! I love you! ❤️')">Yes</button>
        <button id="no" onmouseover="moveButton()">No</button>
    </div>
    <script>
        function moveButton() {
            let x = Math.random() * (window.innerWidth - 100);
            let y = Math.random() * (window.innerHeight - 50);
            document.getElementById("no").style.left = x + "px";
            document.getElementById("no").style.top = y + "px";
        }
    </script>
</body>
</html>

