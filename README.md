# memew
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anjayy Memeww Ekbeww</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            background-color: #ffcccb;
        }
        .container {
            margin-top: 50px;
        }
        .cake {
            font-size: 100px;
        }
        .message {
            font-size: 24px;
            font-weight: bold;
            margin-top: 20px;
        }
        .button {
            padding: 10px 20px;
            font-size: 18px;
            background-color: #ff6600;
            color: white;
            border: none;
            cursor: pointer;
            margin-top: 20px;
            border-radius: 5px;
        }
        .button:hover {
            background-color: #cc5200;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="cake">🎂🎉</div>
        <div class="message" id="message">Met Ultah Mewww! 🎈🎁</div>
        <button class="button" onclick="changeMessage()">Klik untuk Kejutan!</button>
    </div>

    <script>
        function changeMessage() {
            const messages = [
                "Anjayyy ark e rek makin tuaa!!", 
                "Semoga tetep awet muda.. tetep pancarin senyuman yang hangat itu", 
                "Apapun yang terjadi, tetaplah seperti ini.. seperti dirimu yang dulu", 
                "ditahun ke-17 hidupmu ini semua menjadi lebih baik^⁠_⁠^"
            ];
            const randomMessage = messages[Math.floor(Math.random() * messages.length)];
            document.getElementById("message").textContent = randomMessage;
        }
    </script>
</body>
</html>
