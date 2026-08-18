<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flowing Studio</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: #000000;
            color: #ffffff;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px;
        }
        .logo { width: 120px; height: 120px; margin-bottom: 20px; object-fit: contain; }
        .studio-name { font-size: 24px; font-weight: 600; letter-spacing: 1px; margin-bottom: 25px; }
        .message { font-size: 16px; color: #bbbbbb; margin-bottom: 50px; font-weight: 300; }
        .tg-button {
            display: inline-block;
            text-decoration: none;
            background-color: #ffffff;
            color: #000000;
            padding: 12px 28px;
            border-radius: 50px;
            font-size: 16px;
            font-weight: 500;
            transition: all 0.3s ease;
            border: 1px solid transparent;
        }
        .tg-button:hover { 
            background-color: #1a1a1a; 
            color: #ffffff; 
            border: 1px solid #ffffff; 
            transform: scale(1.05); 
        }

        /* Адаптация для больших экранов (ПК) */
        @media (min-width: 768px) {
            .logo { width: 160px; height: 160px; }
            .studio-name { font-size: 32px; }
            .message { font-size: 20px; }
            .tg-button { padding: 16px 36px; font-size: 18px; }
        }
    </style>
</head>
<body>
    <img src="logo.png" alt="Flowing Studio Logo" class="logo">
    <div class="studio-name">Flowing Studio</div>
    <p class="message">К сожалению, пока что нет игр в разработке...</p>
    <a href="https://t.me/FlowingStudio" class="tg-button" target="_blank">
        Перейти в наш Telegram
    </a>
</body>
</html>
