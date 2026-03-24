<!DOCTYPE html>
<html>
<head>
  <title>Happy Birthday Sister Samra 🎉</title>
  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      overflow: hidden;
      background: linear-gradient(120deg, #f6d365, #fda085);
      font-family: 'Great Vibes', cursive;
      text-align: center;
      color: #fff;
    }

    h1 {
      margin-top: 20%;
      font-size: 70px;
      text-shadow: 2px 2px 10px rgba(0,0,0,0.3);
      animation: fadeIn 3s ease-in-out;
    }

    p {
      font-size: 28px;
      animation: fadeIn 4s ease-in-out;
      margin-top: 20px;
    }

    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }

    .flower {
      position: absolute;
      font-size: 30px;
      animation: fall linear infinite;
      opacity: 0.8;
    }

    @keyframes fall {
      0% {top: -10%; transform: rotate(0deg);}
      100% {top: 110%; transform: rotate(360deg);}
    }
  </style>
</head>
<body>

<h1>🎉 Happy Birthday Sister Samra 🎉</h1>
<p>Wishing you happiness, love & endless joy!</p>

<script>
  const flowers = ["🌸","🌼","🌺","💮","🌻"];
  for(let i=0; i<50; i++){
    let flower = document.createElement("div");
    flower.className = "flower";
    flower.innerHTML = flowers[Math.floor(Math.random()*flowers.length)];
    flower.style.left = Math.random()*100 + "vw";
    flower.style.animationDuration = (Math.random()*5 + 5) + "s";
    flower.style.fontSize = (20 + Math.random()*20) + "px";
    document.body.appendChild(flower);
  }
</script>

</body>
</html>
