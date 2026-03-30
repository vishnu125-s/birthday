<!DOCTYPE html>
<html>
<head>
    <title>Happy Birthday</title>

    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">

    <style>
        body {
            margin: 0;
            text-align: center;
            font-family: 'Poppins', sans-serif;
            color: white;
            overflow: hidden;

            /* Full colorful animated background */
            background: linear-gradient(270deg, red, orange, yellow, green, cyan, blue, violet);
            background-size: 1400% 1400%;
            animation: bg 10s ease infinite;
        }

        @keyframes bg {
            0% {background-position:0% 50%;}
            50% {background-position:100% 50%;}
            100% {background-position:0% 50%;}
        }

        h1 {
            font-size: 70px;
            margin-top: 40px;
            text-shadow: 3px 3px 15px black;
        }

        h2 {
            font-size: 50px;
            margin-top: 10px;
            text-shadow: 3px 3px 15px black;
        }

        p {
            font-size: 25px;
            width: 70%;
            margin: auto;
            line-height: 1.8;
            text-shadow: 2px 2px 10px black;
        }

        /* Cake Center */
        .cake {
            width: 220px;
            margin: 20px auto;
            animation: bounce 2s infinite;
        }

        @keyframes bounce {
            0% { transform: translateY(0); }
            50% { transform: translateY(-15px); }
            100% { transform: translateY(0); }
        }

        /* Balloons */
        .balloon {
            position: fixed;
            width: 120px;
            animation: float 5s infinite;
        }

        .left { left: 10px; top: 30%; }
        .right { right: 10px; top: 40%; }

        @keyframes float {
            0% { transform: translateY(0); }
            50% { transform: translateY(-30px); }
            100% { transform: translateY(0); }
        }

        /* Confetti dots */
        .dot {
            position: fixed;
            width: 10px;
            height: 10px;
            background: white;
            border-radius: 50%;
            animation: fall 5s linear infinite;
        }

        @keyframes fall {
            0% { top: -10px; }
            100% { top: 100%; }
        }

        .tamil {
            font-size: 30px;
            color: yellow;
            margin-top: 15px;
            text-shadow: 0 0 10px black;
        }

    </style>
</head>

<body>

    <!-- Balloons -->
    <img class="balloon left" src="https://cdn-icons-png.flaticon.com/512/3468/3468374.png">
    <img class="balloon right" src="https://cdn-icons-png.flaticon.com/512/3468/3468374.png">

    <!-- Cake -->
    <img class="cake" src="https://cdn-icons-png.flaticon.com/512/3468/3468369.png">

    <!-- Text -->
    <h1>🎉 Happy Birthday 🎂</h1>
    <h2>Swetha 💖</h2>

    <p>
        Wishing you a very Happy Birthday 🥳<br><br>
        May your life be filled with happiness 😊<br>
        and success ✨<br><br>
        Keep smiling always 💫
    </p>

    <!-- Tamil line -->
    <div class="tamil">
        இனிய பிறந்தநாள் வாழ்த்துக்கள் 🎂
    </div>

</body>
</html>