<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Super Mario 64</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    html, body {
      height: 100%;
      margin: 0;
      padding: 0;
      background: #000;
    }
    body {
      width: 100vw;
      height: 100vh;
      overflow: auto; /* Allows scrolling */
      display: flex;
      flex-direction: column;
    }
    .fullscreen-frame {
      flex: 1;
      border: none;
      width: 100vw;
      height: 100vh;
      /* Remove these if you want the iframe to be larger than the viewport */
      min-width: 100vw;
      min-height: 100vh;
    }
  </style>
</head>
<body>
  <iframe
    class="fullscreen-frame"
    src="https://lebro29.github.io/gn/"
    allowfullscreen
  ></iframe>
</body>
</html>
