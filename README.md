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
      height: 100vh;   /* viewport height */
      width: 100vw;    /* viewport width */
      background: #000;
      font-family: Arial, Helvetica, sans-serif;
      overflow: scroll; /* enable scrollbars */
    }

    body {
      display: flex;
      flex-direction: column;
    }

    .top-bar {
      height: 64px;    /* fixed heading height */
      width: 100%;
      background: #1565c0;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 2px 4px rgba(0,0,0,0.2);
      flex-shrink: 0;
    }

    .top-bar-title {
      color: #fff;
      font-size: 2rem;
      font-weight: bold;
      margin: 0;
      letter-spacing: 1px;
    }

    .embed-column {
      display: flex;
      flex-direction: column; /* stack iframes vertically */
      width: 200%;            /* double the viewport width */
      height: 400%;           /* 4x the viewport height */
    }

    iframe {
      border: none;
      width: 100%;            /* each iframe fills full width of container */
      flex: 1;                /* share vertical space equally */
    }
  </style>
</head>
<body>
  <div class="top-bar">
    <span class="top-bar-title">DLC</span>
  </div>
  <div class="embed-column">
    <iframe
      src="https://eaglercraft-unblocked.neocities.org/"
      allowfullscreen
      loading="lazy"
      title="Eaglercraft"
    ></iframe>
    <iframe
      src="https://lebro29.github.io/gn/"
      allowfullscreen
      loading="lazy"
      title="GN Math"
    ></iframe>
  </div>
</body>
</html>
