<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For My Favorite Person</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@600&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
<style>
    :root {
        --bg-color: #fff5f5;
        --card-bg: #ffffff;
        --primary-color: #d63384;
        --text-color: #4a4a4a;
        --accent-color: #ff8da1;
    }
    * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
    }
    body {
        font-family: 'Inter', sans-serif;
        background-color: var(--bg-color);
        color: var(--text-color);
        line-height: 1.6;
        padding: 20px;
        display: flex;
        justify-content: center;
        align-items: center;
        min-height: 100vh;
    }
    .container {
        max-width: 600px;
        width: 100%;
        background: var(--card-bg);
        padding: 40px 30px;
        border-radius: 20px;
        box-shadow: 0 10px 30px rgba(214, 51, 132, 0.08);
        text-align: center;
        position: relative;
        overflow: hidden;
    }
    .container::before {
        content: "❤";
        position: absolute;
        top: -30px;
        left: 20px;
        font-size: 10rem;
        color: rgba(255, 141, 161, 0.12);
        z-index: 0;
    }
    .content {
        position: relative;
        z-index: 1;
    }
    h1 {
        font-family: 'Dancing Script', cursive;
        font-size: 3rem;
        color: var(--primary-color);
        margin-bottom: 10px;
    }
    .heart {
        color: var(--primary-color);
        font-size: 2rem;
        margin: 15px 0;
        animation: heartbeat 1.2s infinite;
    }
    @keyframes heartbeat {
        0% { transform: scale(1); }
        20% { transform: scale(1.1); }
        40% { transform: scale(1); }
        60% { transform: scale(1.15); }
        80%, 100% { transform: scale(1); }
    }
    p {
        font-size: 1.1rem;
        margin-bottom: 20px;
        font-weight: 300;
    }
    .highlight {
        font-weight: 600;
        color: var(--primary-color);
    }
    .poem {
        text-align: left;
        background: #fffafb;
        padding: 20px;
        border-radius: 12px;
        border-left: 4px solid var(--accent-color);
        margin: 25px 0;
        font-style: italic;
    }
    .footer {
        font-size: 0.9rem;
        color: #a0a0a0;
        margin-top: 30px;
    }
</style>
</head>
<body>
<div class="container">
    <div class="content">
        <h1>To My Love ❤️</h1>
        <div class="heart">💖</div>

        <p>
            I wrote you this little poem, because some feelings are too big for ordinary words.
        </p>

        <div class="poem">
            You are the morning light that softly breaks my night,<br>
            The quiet peace that makes everything feel right.<br><br>

            In your laughter, I find music I never knew I needed,<br>
            In your eyes, a universe where my heart is always greeted.<br><br>

            You turn ordinary moments into something divine,<br>
            And somehow, just by being you, you become my sign.<br><br>

            If love had a language, you would be its sweetest verse,<br>
            A gentle blessing that makes my whole world immerse.<br><br>

            So stay with me, in this story we continue to write,<br>
            My heart has chosen you — endlessly, every day and night.
        </div>

        <p>
            No matter where life takes us, you are my favorite place to be.
        </p>

        <div class="footer">
            Made with all my heart ✨
        </div>
    </div>
</div>
</body>
</html>
