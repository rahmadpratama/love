<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Romantic Animation</title>
    <style>
        body {
            margin: 0;
            overflow: hidden;
            font-family: Arial, sans-serif;
        }

        .container {
            position: relative;
            width: 100vw;
            height: 100vh;
            background-image: url('p.jpg'); /* Ganti dengan path gambar Anda */
            background-size: cover;
            background-position: center;
            animation: backgroundScroll 20s linear infinite;
        }

        .animated-text {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            font-size: 36px;
            color: white;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.6);
            white-space: nowrap;
        }

        @keyframes backgroundScroll {
            0% {
                background-position: 0 0;
            }
            100% {
                background-position: 100% 100%;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="animated-text">🤍🫂🤍</div>
    </div>
</body>
</html>
