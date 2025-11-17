<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>DLC</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
      background: #000;
      font-family: Arial, Helvetica, sans-serif;
    }

    body {
      display: flex;
      flex-direction: row;   /* split screen left/right */
      height: 100vh;         /* full viewport height */
      overflow: hidden;
    }

    .left, .right {
      width: 50%;            /* each half of the page */
      height: 100%;          /* full height */
      display: flex;
      flex-direction: column;
    }

    .top-bar {
      background: #1565c0;
      padding: 0.75em 0;
      text-align: center;
      box-shadow: 0 2px 4px rgba(0,0,0,0.2);
    }

    .top-bar-title {
      color: #fff;
      font-size: 2rem;
      font-weight: bold;
      margin: 0;
      letter-spacing: 1px;
    }

    iframe {
      border: none;
      flex: 1;               /* iframe fills remaining space */
      width: 100%;
    }
  </style>
</head>
<body>
  <div class="left">
    <div class="top-bar">
      <span class="top-bar-title">GN Math</span>
    </div>
    <iframe
      src="https://lebro29.github.io/gn/"
      allowfullscreen
      loading="lazy"
      title="GN Math"
    ></iframe>
  </div>
  <div class="right">
    <div class="top-bar">
      <span class="top-bar-title">Eaglercraft</span>
    </div>
    <iframe
      src="https://eaglercraft-unblocked.neocities.org/"
      allowfullscreen
      loading="lazy"
      title="Eaglercraft"
    ></iframe>
  </div>
</body>
</html>
