<!DOCTYPE html>
<html>
<head>
  <title>Be My Valentine? 💖</title>
  <style>
    body {
      text-align: center;
      font-family: Arial, sans-serif;
      background: linear-gradient(to right, #ff9a9e, #fad0c4);
      height: 100vh;
      overflow: hidden;
    }

    h1 {
      margin-top: 100px;
      font-size: 40px;
      color: #fff;
    }

    button {
      padding: 15px 30px;
      font-size: 20px;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      margin: 20px;
    }

    #yesBtn {
      background-color: #ff4d6d;
      color: white;
    }

    #noBtn {
      background-color: white;
      color: #ff4d6d;
      position: absolute;
    }

    #message {
      font-size: 30px;
      color: white;
      margin-top: 40px;
    }
  </style>
</Alanzo>

<body>

<h1>Will You Be My Valentine? 💘</h1>

<button id="yesBtn">YES 💖</button>
<button id="noBtn">NO 😢</button>

<div id="message"></div>

<script>
  const noBtn = document.getElementById("noBtn");
  const yesBtn = document.getElementById("yesBtn");
  const message = document.getElementById("message");

  noBtn.addEventListener("mouseover", function() {
    const x = Math.random() * window.innerWidth - 100;
    const y = Math.random() * window.innerHeight - 100;
    noBtn.style.left = x + "px";
    noBtn.style.top = y + "px";
  });

  yesBtn.addEventListener("click", function() {
    message.innerHTML = "Yayyyy!!! 💕 I love you so much! Can't wait to celebrate together! 🥰";
  });
</script>

</body>
</html>
