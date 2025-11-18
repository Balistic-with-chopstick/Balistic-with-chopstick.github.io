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
      background: linear-gradient(180deg, #000 0%, #111 100%);
      font-family: Arial, Helvetica, sans-serif;
      overflow: hidden; /* no scrollbars */
      color: #fff;
    }

    body {
      display: flex;
      flex-direction: column;
      height: 100vh;
      width: 100vw;
    }

    .top-bar {
      flex: 0 0 64px;  /* fixed heading height */
      width: 100vw;
      background: #1565c0;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 2px 4px rgba(0,0,0,0.4);
    }

    .top-bar-title {
      color: #fff;
      font-size: 2rem;
      font-weight: bold;
      margin: 0;
      letter-spacing: 2px;
      text-transform: uppercase;
    }

    .embed-column {
      flex: 1;              /* take up remaining vertical space */
      display: flex;
      flex-direction: column;
      width: 100vw;
      height: 100%;
    }

    iframe {
      border: none;
      width: 100%;
      flex: 1;              /* each iframe takes equal share of embed-column */
    }

    footer {
      flex: 0 0 40px;       /* fixed footer height */
      width: 100vw;
      background: #222;
      color: #aaa;
      text-align: center;
      line-height: 40px;
      font-size: 0.9rem;
      border-top: 2px solid #1565c0;
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
  <footer>
    &copy; 2025 DLC Project — Styled with ❤️
  </footer>
</body>
</html>
