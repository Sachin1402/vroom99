<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Face Recognition App</title>
    <link rel="stylesheet" href="css/style.css" />
  </head>
  <body>
    <header>Face Recognition using Javascript</header>
    <div class="container">
      <video id="video" height="500" width="500" autoplay muted></video>
    </div>
    <div class="result-container">
      <div id="emotion">Emotion</div>
      <div id="gender">Gender</div>
      
    </div>

    <script src="./js/face-api.min.js"></script>
    <script src="./js/main.js"></script>
  </body>
</html>
