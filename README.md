<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Мой сайт</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #667eea, #764ba2);
      color: white;
    }
    header {
      padding: 2rem;
      text-align: center;
      background: rgba(0, 0, 0, 0.2);
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 1.5rem;
      padding: 1rem;
      background: rgba(0, 0, 0, 0.15);
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #ffd700;
    }
    main {
      max-width: 900px;
      margin: 2rem auto;
      padding: 2rem;
      background: rgba(255, 255, 255, 0.1);
      border-radius: 12px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.2);
    }
    h2 {
      margin-top: 0;
      color: #ffd700;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: rgba(0, 0, 0, 0.2);
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Добро пожаловать на мой сайт</h1>
  </header>

  <nav>
    <a href="#">Главная</a>
    <a href="#">Обо мне</a>
    <a href="#">Проекты</a>
    <a href="#">Контакты</a>
  </nav>

  <main>
    <h2>О сайте</h2>
    <p>Этот сайт создан для демонстрации красивого интерфейса с помощью GitHub Pages. Здесь можно разместить любую информацию: о себе, своих проектах или услугах.</p>

    <h2>Проекты</h2>
    <ul>
      <li>Проект 1 — описание проекта</li>
      <li>Проект 2 — описание проекта</li>
      <li>Проект 3 — описание проекта</li>
    </ul>
  </main>

  <footer>
    © 2025 bipolaroc4ka. Все права защищены.
  </footer>
</body>
</html>
