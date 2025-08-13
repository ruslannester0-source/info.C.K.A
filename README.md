

<html lang="uk">
<head>
  <meta charset="UTF-8" />
</head>
<body style="background-color:black; color:white; text-align:center;">
  <h1>Це головна сторінка</h1>
  <a href="page2.html">
  </a>
</body>
</html>

<img width="1066" height="422" alt="2025-08-03_232617" src="https://github.com/user-attachments/assets/eb9891c5-fc6b-43fb-b3f1-e39e211ae529" />

<img width="1113" height="814" alt="Знімок екрана 2025-08-03 232703" src="https://github.com/user-attachments/assets/dee3097e-b483-47f8-a8e7-31f05ad02454" />

<img width="1139" height="310" alt="Знімок екрана 2025-08-03 232658" src="https://github.com/user-attachments/assets/c91371cf-2868-49f6-9a9d-617bacdcdf08" />

<img width="876" height="717" alt="Знімок екрана 2025-08-03 232636" src="https://github.com/user-attachments/assets/12cceb97-8156-4019-81cf-3133112e8639" />

<img width="1495" height="645" alt="Знімок екрана 2025-08-03 232631" src="https://github.com/user-attachments/assets/6d74990d-2955-497c-bfaf-0aa50300ae0b" />

<img width="1459" height="571" alt="Знімок екрана 2025-08-03 232625" src="https://github.com/user-attachments/assets/35d37874-9a35-467d-84b8-a9d2984a4713" />


<html lang="uk">
<head>
  <meta charset="UTF-8">
  <title>Кнопки Вгору / Вниз</title>
  <style>
    body {
      background-color: black;
      color: white;
      font-family: Arial, sans-serif;
      padding: 50px;
    }

    .content {
      height: 2000px; /* Щоб було що прокручувати */
    }

    /* Кнопка вгору */
    .scroll-up {
      position: fixed;
      bottom: 30px;
      right: 30px;
      padding: 10px 20px;
      font-size: 16px;
      cursor: pointer;
      background-color: #333;
      color: white;
      border: none;
      border-radius: 5px;
    }

    .scroll-up:hover {
      background-color: #555;
    }

    /* Кнопка вниз */
    .scroll-down {
      position: fixed;
      bottom: 30px;
      left: 30px;
      padding: 10px 20px;
      font-size: 16px;
      cursor: pointer;
      background-color: #333;
      color: white;
      border: none;
      border-radius: 5px;
    }

    .scroll-down:hover {
      background-color: #555;
    }
  </style>
</head>
<body>

  <div class="content">
    <h1>Прокрути сторінку</h1>
    <p>...довгий контент для демонстрації...</p>
  </div>

  <!-- Кнопки -->
  <button class="scroll-up" onclick="scrollToTop()">⬆ Вгору</button>
  <button class="scroll-down" onclick="scrollToBottom()">⬇ Вниз</button>

  <!-- JavaScript -->
  <script>
    function scrollToTop() {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    }

    function scrollToBottom() {
      window.scrollTo({ top: document.body.scrollHeight, behavior: 'smooth' });
    }
  </script>
</body>
</html>

