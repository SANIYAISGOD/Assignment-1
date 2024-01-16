<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }

    .shape-container {
      position: relative;
    }

    .shape {
      width: 100px;
      height: 50px;
      background-color: blue;
      transition: transform 0.5s;
    }

    .shape:hover {
      transform: scale(1.5); /* Scale the shape to make it a circle */
      border-radius: 50%;
    }
  </style>
</head>
<body>
  <div class="shape-container">
    <div class="shape"></div>
  </div>
</body>
</html>
