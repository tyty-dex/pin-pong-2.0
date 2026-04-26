<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Classic Ping-Pong Project</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #e0e0e0;
            background-color: #121212;
            margin: 0;
            padding: 40px;
            display: flex;
            justify-content: center;
        }
        .container {
            max-width: 800px;
            background: #1e1e1e;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
            border: 1px solid #333;
        }
        h1 {
            color: #00ff88;
            border-bottom: 2px solid #00ff88;
            padding-bottom: 10px;
            display: flex;
            align-items: center;
            gap: 15px;
        }
        h2 {
            color: #00d4ff;
            margin-top: 25px;
        }
        .features-list {
            list-style: none;
            padding: 0;
        }
        .features-list li::before {
            content: "⚡";
            margin-right: 10px;
        }
        .controls {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            background: #252525;
            padding: 20px;
            border-radius: 8px;
        }
        .control-item b {
            color: #ffcc00;
        }
        code {
            background: #000;
            padding: 4px 8px;
            border-radius: 4px;
            color: #f8f8f2;
            font-family: 'Courier New', Courier, monospace;
        }
        .command-block {
            background: #000;
            padding: 15px;
            border-left: 4px solid #00ff88;
            margin: 15px 0;
            display: block;
        }
        .badge {
            display: inline-block;
            background: #333;
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.9em;
            margin-right: 5px;
            border: 1px solid #444;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Classic Ping-Pong 🏓</h1>
    <p>Минималистичная аркада для двоих игроков на одном ПК. Динамичный ремейк легендарной классики, написанный на Python с использованием библиотеки Pygame.</p>

    <h2>🚀 Особенности</h2>
    <ul class="features-list">
        <li><b>PvP Мультиплеер:</b> Честное состязание на одной клавиатуре.</li>
        <li><b>Progressive Speed:</b> Мяч ускоряется с каждым ударом, проверяя вашу реакцию.</li>
        <li><b>Score System:</b> Автоматический подсчет очков и отображение счета на экране.</li>
        <li><b>Pixel Physics:</b> Точные коллизии мяча с ракетками и границами поля.</li>
    </ul>

    <h2>🎮 Управление</h2>
    <div class="controls">
        <div class="control-item">
            <strong>Игрок 1 (Слева)</strong><br>
            Вверх: <b>W</b> / Вниз: <b>S</b>
        </div>
        <div class="control-item">
            <strong>Игрок 2 (Справа)</strong><br>
            Вверх: <b>↑</b> / Вниз: <b>↓</b>
        </div>
    </div>

    <h2>🛠 Стек технологий</h2>
    <span class="badge">Python 3.x</span>
    <span class="badge">Pygame</span>
    <span class="badge">Logic & Physics</span>

    <h2>💻 Запуск проекта</h2>
    <p>Для старта игры выполните команду в терминале:</p>
    <code class="command-block">
        python main.py
    </code>
</div>

</body>
</html>
