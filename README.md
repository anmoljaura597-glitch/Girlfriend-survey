<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>The Official Girlfriend Survey 💖</title>

<style>
    body {
        font-family: 'Segoe UI', sans-serif;
        background: linear-gradient(135deg, #fbd3e9, #c77dff);
        margin: 0;
        padding: 20px;
        color: #333;
    }
    .container {
        max-width: 500px;
        background: white;
        margin: auto;
        padding: 25px;
        border-radius: 18px;
        box-shadow: 0 10px 25px rgba(0,0,0,0.15);
    }
    h1 {
        text-align: center;
        color: #8a2be2;
    }
    p {
        text-align: center;
        font-size: 15px;
    }
    h2 {
        margin-top: 25px;
        color: #d63384;
    }
    label {
        font-weight: 600;
        display: block;
        margin-top: 18px;
    }
    input, textarea, select {
        width: 100%;
        padding: 10px;
        margin-top: 8px;
        border-radius: 10px;
        border: 1px solid #ccc;
        font-size: 14px;
    }
    textarea {
        resize: none;
    }
    button {
        margin-top: 25px;
        width: 100%;
        padding: 12px;
        border: none;
        border-radius: 30px;
        background: #8a2be2;
        color: white;
        font-size: 16px;
        cursor: pointer;
    }
    button:hover {
        background: #6f1dbb;
    }
    .love {
        text-align: center;
        margin-top: 20px;
        font-size: 18px;
    }
</style>
</head>

<body>

<div class="container">
    <h1>The Official Girlfriend Survey 💋</h1>
    <p>
        Hey My Love 💖<br><br>
        I made this just because I’m completely in love with you (and slightly obsessed 😌).  
        Answer honestly, flirt shamelessly, and let’s see how cute you can be 💕
    </p>

    <h2>💗 Warm-Up / Cute Basics</h2>

    <label>1. What’s my full name (correct spelling 😏)?</label>
    <input type="text">

    <label>2. Your favorite nickname for me 💕</label>
    <input type="text">

    <label>3. When did we officially become “us”? 📅</label>
    <input type="date">

    <label>4. Your first thought when you saw me 😌</label>
    <textarea rows="2"></textarea>

    <label>5. Who fell first? 😛</label>
    <select>
        <option>You</option>
        <option>Me</option>
        <option>Both at same time</option>
    </select>

    <h2>💘 Love & Feelings</h2>

    <label>6. What do you love most about me? 💖</label>
    <textarea rows="3"></textarea>

    <label>7. What do I do that melts your heart? 🫠</label>
    <textarea rows="2"></textarea>

    <label>8. How much do you love me? ❤️</label>
    <select>
        <option>A lot</option>
        <option>Too much</option>
        <option>Infinity ♾️</option>
        <option>More than words</option>
    </select>

    <h2>😈 Fun & Flirty</h2>

    <label>9. My cutest habit 😘</label>
    <textarea rows="2"></textarea>

    <label>10. My most attractive feature 👀🔥</label>
    <textarea rows="2"></textarea>

    <h2>💭 Final Question (Be Honest 😌)</h2>

    <label>11. Write 5 GOOD things about me 💖</label>
    <textarea rows="4" placeholder="1.\n2.\n3.\n4.\n5."></textarea>

    <label>12. Write 5 BAD things about me 💔</label>
    <textarea rows="4" placeholder="Be honest… I can handle it 😏"></textarea>

    <button onclick="thankYou()">Submit with Love 💌</button>

    <div class="love" id="message"></div>
</div>

<script>
function thankYou() {
    document.getElementById("message").innerHTML =
    "Form submitted 💖<br>I love you more than you know 😘";
}
</script>
