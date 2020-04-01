<html>
  <head>
  </head>
  <body>
    <canvas id="test" width="200" height="100"></canvas>
    <script>
      var c = document.getElementById("test");
      var ctx = c.getContext("2d");
      ctx.moveTo(0,0);
      ctx.lineTo(200,100);
      ctx.stroke();
      var ctx2 = c.getContext("2d");
      ctx2.moveTo(200,0);
      ctx2.lineTo(0,100);
      ctx2.stroke();
    </script>
  </body>
</html>
