<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flores Amarillas</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-image: url('https://www.xtrafondos.com/wallpapers/resized/flores-amarillas-en-prado-11465.jpg?s=large'); /* Fondo de flores amarillas */
            background-size: cover;
            background-position: center;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: Arial, sans-serif;
        }
        #text-container {
            background-color: rgba(255, 255, 255, 0.8);
            padding: 20px 40px;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
            text-align: center;
        }
        h1 {
            font-size: 36px;
            color: #FFD700; /* Color dorado */
            margin-bottom: 10px;
        }
        p {
            font-size: 18px;
            color: #333;
        }
        button {
            margin-top: 15px;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            background-color: #FFD700;
            border: none;
            border-radius: 5px;
        }
        button:hover {
            background-color: #FFC107;
        }
    </style>
</head>
<body>

    <div id="text-container">
        <h1>🌼 Flores Amarillas 🌼</h1>
        <p id="custom-text">Un día soleado lleno de flores hermosas...</p>
        <button onclick="changeText()">Cambiar Texto</button>
    </div>

    <script>
        function changeText() {
            let newText = prompt("Escribe el nuevo texto:");
            if (newText) {
                document.getElementById('custom-text').innerText = newText;
            }
        }
    </script>

</body>
</html>
