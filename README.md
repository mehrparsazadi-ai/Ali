<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Dream Life</title>

<style>
body {
    margin: 0;
    background: #101c2c;
    color: white;
    font-family: Tahoma;
    text-align: center;
}

header {
    background: #07111f;
    padding: 20px;
    font-size: 22px;
    color: gold;
}

.container {
    max-width: 600px;
    margin: auto;
    padding: 15px;
}

.scene {
    background: linear-gradient(#6bb7e8, #78b86b);
    padding: 45px 10px;
    font-size: 55px;
    border-radius: 18px;
    margin: 15px 0;
}

.message {
    background: #243b55;
    padding: 15px;
    border-radius: 12px;
    margin: 15px 0;
}

h2 {
    color: #ffd166;
    margin-top: 25px;
}

.grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 10px;
}

button {
    background: #ffd166;
    color: #101c2c;
    border: none;
    padding: 15px 8px;
    border-radius: 12px;
    font-size: 14px;
    font-weight: bold;
    cursor: pointer;
}

button:active {
    transform: scale(.96);
}
</style>
</head>

<body>

<header>
    🌙 DREAM LIFE
    <div>
        💰
        <span id="money">5000000</span>
        تومان
    </div>
</header>

<div class="container">

    <div class="scene">
        🏡 🚗 🌳
    </div>

    <div class="message" id="message">
        به زندگی رؤیایی خودت خوش آمدی!
    </div>

    <h2>💼 کار و درآمد</h2>

    <div class="grid">
        <button onclick="work()">💻 کار کردن</button>
        <button onclick="bonus()">🎁 جایزه گرفتن</button>
    </div>

    <h2>🏠 خرید خانه</h2>

    <div class="grid">
        <button onclick="buy(10000000,'خانه کوچک')">
            🏠 خانه کوچک - ۱۰ میلیون
        </button>

        <button onclick="buy(50000000,'آپارتمان لوکس')">
            🏢# Ali
Mehrsa 
