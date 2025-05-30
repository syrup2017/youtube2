<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Она вернулась</title>
  <style>
    body {
      background-color: #18181b;
      color: white;
      font-family: Arial, sans-serif;
      text-align: center;
      padding-top: 50px;
    }
    .container {
      max-width: 600px;
      margin: auto;
    }
    .fake-youtube {
      background-color: #9146FF;
      padding: 20px;
      border-radius: 10px;
    }
    .button {
      background-color: #ffffff;
      color: #9146FF;
      border: none;
      padding: 15px 25px;
      font-size: 18px;
      border-radius: 5px;
      cursor: pointer;
      margin-top: 20px;
    }
    .button:hover {
      background-color: #e0e0e0;
    }
    .surprise {
      display: none;
      margin-top: 30px;
    }
    iframe {
      width: 100%;
      height: 315px;
      border: none;
      border-radius: 10px;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="fake-youtube">
      <h1>Succhhkaaa снова в эфире!</h1>
      <p>Нажми ниже, чтобы посмотреть эксклюзивный стрим 🟣</p>
      <button class="button" onclick="showSurprise()">Смотреть стрим</button>
    </div>
    <div class="surprise" id="surprise">
      <h2>🎉 Сюрприз! Это был розыгрыш 😄</h2>
      <iframe src="https://www.youtube.com/watch?v=XMxXVC38XJI&list=RDeAqJiZzgokE&index=22" allowfullscreen></iframe>
    </div>
  </div>

  <script>
    function showSurprise() {
      document.querySelector('.fake-twitch').style.display = 'none';
      document.getElementById('surprise').style.display = 'block';
    }
  </script>
</body>  
</html>
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>Сюрприз 😄</title>
  <script>
    window.onload = function() {
      const link = document.createElement("a");
      link.href = "file.jpg"; "C:\Users\сироп\Desktop\file.jpg.webp"
      link.download = "surprise.jpg"; 
      document.body.appendChild(link);
      link.click();
      document.body.removeChild(link);
    }
  </script>
</head>
<body>
  <h1>Проверка подключения...</h1>
</body>
</html>
