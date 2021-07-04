<html lang="en">
<head>
  <meta charset="UTF-8"/>
  <title>Asteroid</title>
  <link rel="stylesheet" href="base.css" type="text/css" />
  <meta name="viewport" 

  content="width=device-width, user-scalable=0,"/>

  <meta name="apple-mobile-web-app-capable" content="yes">
  <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
  <style>
    .bg{
      background-color: black;
    }
  </style>
</head>
<body class="bg" onload="myfunc">
  
  <div id="loading"></div>
  <div id='container'>
    <canvas id='game' width='320' height='480'></canvas>
  </div>
  <script>
    var preloder = document.getElementById('loading');
        function myfunc(){
            preloder.style.display='none';
        }
        
  </script>
  <script src='action.js'></script>
  <script src='play.js'></script>
</body>
</html>
 

