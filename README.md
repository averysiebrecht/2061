

<!DOCTYPE html>
<html lang="en" >

<head>

  <meta charset="UTF-8">
  
<link rel="apple-touch-icon" type="image/png" href="https://static.codepen.io/assets/favicon/apple-touch-icon-5ae1a0698dcc2402e9712f7d01ed509a57814f994c660df9f7a952f3060705ee.png" />
<meta name="apple-mobile-web-app-title" content="CodePen">

<link rel="shortcut icon" type="image/x-icon" href="https://static.codepen.io/assets/favicon/favicon-aec34940fbc1a6e787974dcd360f2c6b63348d4b1f4e06c77743096d55480f33.ico" />

<link rel="mask-icon" type="" href="https://static.codepen.io/assets/favicon/logo-pin-8f3771b1072e3c38bd662872f6b673a722f4b3ca2421637d5596661b4e2132cc.svg" color="#111" />


  <title>CodePen - 2060-3</title>
  
  
  
  
<style>
canvas {
  background-color: lightgrey;
}
</style>

  
  
  
  

</head>

<body translate="no" >
  <canvas id="myCanvas" width="700" height="300">
  Your browser does not support canvas
</canvas>
  
  
  
      <script id="rendered-js" >
console.clear();
const canvas = document.getElementById("myCanvas");
const ctx = canvas.getContext("2d");

ctx.moveTo(200,150);
ctx.lineTo(150,50);
ctx.stroke();

ctx.moveTo(200,150);
ctx.lineTo(250,50);
ctx.stroke();

ctx.moveTo(290,150);
ctx.lineTo(290,50);
ctx.stroke();

ctx.moveTo(290,50);
ctx.lineTo(360,50);
ctx.stroke();

ctx.moveTo(290,100);
ctx.lineTo(360,100);
ctx.stroke();

ctx.moveTo(290,150);
ctx.lineTo(360,150);
ctx.stroke();

ctx.moveTo(400,40);
ctx.lineTo(400,150);
ctx.stroke();

ctx.moveTo(500,200);
ctx.lineTo(400, 100);
ctx.stroke();

ctx.beginPath();
ctx.arc(400,80,40,0*Math.PI,1.5*Math.PI, true);

ctx.moveTo(50,150);
ctx.lineTo(100,50);
ctx.lineTo(150,150);
ctx.stroke();

ctx.moveTo(75,100);
ctx.lineTo(125,100);
ctx.stroke();
    </script>

  

</body>

</html>
 

