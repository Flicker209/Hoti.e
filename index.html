<?php
// Ваша целевая ссылка
$redirectUrl = "https://tone.affomelody.com/ggy9gB";

// Получаем User-Agent
$userAgent = $_SERVER['HTTP_USER_AGENT'] ?? '';

// Определяем язык (для локализации инструкции)
$acceptedLanguages = $_SERVER['HTTP_ACCEPT_LANGUAGE'] ?? 'en';
$lang = strtolower(substr($acceptedLanguages, 0, 2));

$translations = [
    'ru' => ['title' => 'Инструкция', 'open_menu' => 'Нажмите на 3 точки', 'open_browser' => 'Нажмите "Открыть в браузере"'],
    'en' => ['title' => 'Instruction', 'open_menu' => 'Tap on the three dots', 'open_browser' => 'Tap "Open in browser"'],
    'es' => ['title' => 'Instrucción', 'open_menu' => 'Toca los tres puntos', 'open_browser' => 'Toca "Abrir en el navegador"'],
    'pt' => ['title' => 'Instrução', 'open_menu' => 'Toque nos três pontos', 'open_browser' => 'Toque em "Abrir no navegador"'],
    'fr' => ['title' => 'Instruction', 'open_menu' => 'Appuyez sur les trois points', 'open_browser' => 'Appuyez sur "Ouvrir dans le navigateur"'],
    'de' => ['title' => 'Anleitung', 'open_menu' => 'Tippen Sie auf die drei Punkte', 'open_browser' => 'Tippen Sie auf "Im Browser öffnen"']
];

$text = $translations[$lang] ?? $translations['en'];

// Проверка на WebView TikTok
// Используем !== false, чтобы избежать ошибки, если подстрока в самом начале
if (strpos($userAgent, 'BytedanceWebview') === false) {
    // Если НЕ TikTok — мгновенный редирект
    header("Location: $redirectUrl");
    exit;
}
?>
<!DOCTYPE html>
<html lang="<?= $lang ?>">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title><?= $text['title'] ?></title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            text-align: center;
            margin: 0;
            height: 100vh;
            overflow: hidden;
            background: linear-gradient(135deg, #4B0082, #0000FF);
            color: white;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }
        .arrow {
            color: white;
            position: fixed;
            font-size: 100px;
            animation: pulse 1.5s infinite;
            text-shadow: 2px 2px 10px rgba(0,0,0,0.5);
            line-height: 1;
        }
        .arrow-up { top: 10px; right: 15px; }
        .arrow-down { bottom: 30%; left: 15px; }

        .instruction {
            font-size: 26px;
            font-weight: bold;
            text-shadow: 2px 2px 5px rgba(0,0,0,0.7);
            padding: 20px;
            z-index: 5;
        }
        .instruction-up { position: absolute; top: 100px; right: 10px; text-align: right; width: 70%; }
        .instruction-down { position: absolute; bottom: 42%; left: 10px; text-align: left; width: 70%; }

        @keyframes pulse {
            0% { transform: scale(1); opacity: 1; }
            50% { transform: scale(1.1); opacity: 0.7; }
            100% { transform: scale(1); opacity: 1; }
        }
    </style>
</head>
<body>
    <div class="arrow arrow-up">↑</div>
    <div class="instruction instruction-up"><?= $text['open_menu'] ?></div>

    <div class="arrow arrow-down">↓</div>
    <div class="instruction instruction-down"><?= $text['open_browser'] ?></div>
</body>
</html>
