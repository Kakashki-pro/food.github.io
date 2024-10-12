<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Клуб Столовки — Репутация</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            color: #333;
            margin: 0;
            padding: 20px;
        }
        h1 {
            color: #2c3e50;
            font-size: 1.8em;
            text-align: center;
            margin-bottom: 20px;
        }
        ul {
            background-color: #fff;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            list-style-type: none;
            margin: 0;
            max-width: 600px;
            margin: 0 auto; /* Центрирование на экране */
        }
        li {
            margin-bottom: 10px;
            font-size: 1.2em;
        }
        .highlight {
            font-weight: bold;
            color: #e74c3c;
        }
        /* Медиа-запросы для мобильных устройств */
        @media (max-width: 600px) {
            body {
                padding: 10px;
            }
            h1 {
                font-size: 1.5em;
            }
            ul {
                padding: 15px;
            }
            li {
                font-size: 1em;
            }
        }
    </style>
</head>
<body>

    <h1>Правила Репутации в Клубе Столовки</h1>

    <p>В нашем секретном клубе существует система репутации, которая показывает, как ты себя ведёшь за столом. Максимальная репутация — <span class="highlight">100</span>, минимальная — <span class="highlight">0</span>. Если твоя репутация опускается до нуля, тебя исключают из клуба. Вот основные правила:</p>

    <ul>
        <li><span class="highlight">0 репутации</span> — за обычное съеденное блюдо.</li>
        <li><span class="highlight">+10 репутации</span> — за взятие добавки.</li>
        <li><span class="highlight">+5 репутации</span> — за взятие дополнительного компота.</li>
        <li><span class="highlight">-15 репутации</span> — за выбрасывание еды (если еда <strong>невкусной</strong>).</li>
        <li><span class="highlight">-20 репутации</span> — за выбрасывание еды, если еда <strong>вкусной</strong>.</li>
        <li><span class="highlight">0 репутации</span> — за не выпитый компот.</li>
    </ul>

</body>
</html>
