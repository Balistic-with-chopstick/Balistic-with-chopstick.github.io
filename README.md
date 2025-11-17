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
      height: 100vh;   /* full viewport height */
      width: 100vw;    /* full viewport width */
      background: #000;
      font-family: Arial, Helvetica, sans-serif;
      overflow: hidden; /* no scrollbars */
    }

    body {
      display: flex;
      flex-direction: column;
    }

    .top-bar {
      height: 10vh;    /* heading takes 10% of screen height */
      width: 100%;
      background: #1565c0;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 2px 4px rgba(0,0,0,0.2);
    }

    .top-bar-title {
      color: #fff;
      font-size: 2rem;
      font-weight: bold;
      margin: 0;
      letter-spacing: 1px;
    }

    .embed-row {
      height: 90vh;    /* remaining 90% of screen */
      width: 100%;
      display: flex;
    }

    iframe {
      border: none;
      width: 50%;      /* each iframe takes half the width */
      height: 100%;    /* full height of embed row */
    }
  </style>
</head>
<body>
  <div class="top-bar">
    <span class="top-bar-title">DLC</span>
  </div>
  <div class="embed-row">
    <iframe
      src="https://lebro29.github.io/gn/"
      allowfullscreen
      loading="lazy"
      title="GN Math"
    ></iframe>
    <iframe
      src="https://eaglercraft-unblocked.neocities.org/"
      allowfullscreen
      loading="lazy"
      title="Eaglercraft"
    ></iframe>
  </div>
</body>
</html>
