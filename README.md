<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For My Love</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@600&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Inter', sans-serif;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden;
    background: linear-gradient(-45deg, #ffe4ec, #fff5f7, #ffd6e0, #fff);
    background-size: 400% 400%;
    animation: gradientBG 12s ease infinite;
}

@keyframes gradientBG {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
}

/* floating hearts */
.heart-bg {
    position: absolute;
    width: 100%;
    height: 100%;
    overflow: hidden;
    z-index: 0;
}

.heart-bg span {
    position: absolute;
    display: block;
    color: rgba(255, 105, 135, 0.3);
    animation: float 10s linear infinite;
    font-size: 20px;
}

@keyframes float {
    0% {
        transform: translateY(100vh) scale(1);
        opacity: 0;
    }
    50% {
        opacity: 1;
    }
    100% {
        transform: translateY(-10vh) scale(1.5);
        opacity: 0;
    }
}

.container {
    position: relative;
    z-index: 1;
    max-width: 650px;
    padding: 40px;
    border-radius: 25px;
    background: rgba(255, 255, 255, 0.6);
    backdrop-filter: blur(12px);
    box-shadow: 0 15px 40px rgba(0,0,0,0.1);
    text-align: center;
}

h1 {
    font-family: 'Dancing Script', cursive;
    font-size: 3rem;
    color: #d63384;
    margin-bottom: 10px;
}

.sub {
    font-size: 0.95rem;
    color: #666;
    margin-bottom: 25px;
}

.poem {
    text-align: left;
    font-style: italic;
    line-height: 1.8;
    color: #444;
    padding: 20px;
    border-left: 4px solid #ff8da1;
    background: rgba(255,255,255,0.5);
    border-radius: 10px;
}

.footer {
    margin-top: 25px;
    font-size: 0.85rem;
    color: #888;
}
</style>
</head>

<body>

<div class="heart-bg">
    <span style="left:10%;">❤</span>
    <span style="left:25%; animation-delay:2s;">❤</span>
    <span style="left:40%; animation-delay:4s;">❤</span>
    <span style="left:60%; animation-delay:1s;">❤</span>
    <span style="left:80%; animation-delay:3s;">❤</span>
</div>

<div class="container">
    <h1>To My Love ❤️</h1>
    <div class="sub">A little piece of my heart, written in words</div>

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

    <div class="footer">
        Made with love ✨
    </div>
</div>

</body>
</html>
