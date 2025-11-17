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
      overflow: auto;
      display: flex;
      flex-direction: column;
    }
    .top-bar {
      background: #1565c0;  /* Blue */
      width: 100vw;
      padding: 0.75em 0;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 100;
      box-shadow: 0 2px 4px rgba(0,0,0,0.08);
    }
    .top-bar-title {
      color: #fff;
      font-size: 2rem;
      font-family: Arial, Helvetica, sans-serif;
      font-weight: bold;
      margin: 0;
      letter-spacing: 1px;
    }
    .fullscreen-frame {
      flex: 1;
      border: none;
      width: 100vw;
      height: 100vh;
    }
    @media (max-width: 600px) {
      .top-bar-title { font-size: 1.2rem; }
    }
  </style>
</head>
<body>
  <div class="top-bar">
    <span class="top-bar-title">Super Mario 64</span>
  </div>
  <iframe
    class="fullscreen-frame"
    src="https://lebro29.github.io/gn/"
    allowfullscreen
  ></iframe>
</body>
</html>
