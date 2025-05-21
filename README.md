<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Just For You</title>
  <style>
    body {
      margin: 0;
      font-family: 'Comic Sans MS', cursive, sans-serif;
      background: linear-gradient(135deg, #ff9a9e 0%, #fad0c4 100%);
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      overflow: hidden;
      animation: fadeIn 2s ease-in;
    }

    .container {
      text-align: center;
      background: white;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 8px 16px rgba(0,0,0,0.2);
      animation: popUp 1s ease-in-out;
    }

    h1 {
      font-size: 2.5rem;
      color: #ff4e50;
      margin-bottom: 10px;
    }

    p {
      font-size: 1.2rem;
      color: #444;
      margin-bottom: 20px;
    }

    a {
      text-decoration: none;
      background: #ff6f91;
      color: white;
      padding: 12px 25px;
      border-radius: 30px;
      font-size: 1.1rem;
      transition: background 0.3s ease;
    }

    a:hover {
      background: #ff3e6c;
    }

    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }

    @keyframes popUp {
      0% {transform: scale(0.5);}
      100% {transform: scale(1);}
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Hey Lovely! 🌸</h1>
    <p>There's something special waiting for you inside.</p>
    <a href="letter.html">Read the Letter 💌</a>
  </div>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Dear Lovely</title>
  <style>
    body {
      margin: 0;
      font-family: 'Comic Sans MS', cursive, sans-serif;
      background: #fff0f5;
      color: #444;
      padding: 50px 20px;
      line-height: 1.8;
      animation: fadeIn 1.5s ease;
    }

    .letter {
      max-width: 700px;
      margin: auto;
      background: white;
      padding: 40px;
      border-radius: 15px;
      box-shadow: 0 8px 16px rgba(0,0,0,0.1);
    }

    h2 {
      color: #e75480;
      margin-bottom: 20px;
    }

    p {
      font-size: 1.1rem;
      margin-bottom: 15px;
    }

    .signature {
      margin-top: 30px;
      font-weight: bold;
      color: #e75480;
    }

    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }
  </style>
</head>
<body>
  <div class="letter">
    <h2>Dear Lovely,</h2>
    <p>I don’t usually do things like this, but there’s something I want to say and I hope this message reaches you.</p>
    <p>I just want you to know that I truly admire you. There’s something about your smile that I truly love. I admire who you are—the way you look and the way you smile. It’s all effortlessly beautiful.</p>
    <p>We may not have shared deeper conversations, but even in those little messages, I’ve found comfort and warmth. I just wanted to be honest and let you know how I feel. You’re someone truly special, and I wanted you to hear that directly from me.</p>
    <p class="signature">Sincerely,<br/>Adrian</p>
  </div>
</body>
</html>

