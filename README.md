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
      background: #000;
      font-family: Arial, Helvetica, sans-serif;
    }
    body {
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .top-bar {
      background: #1565c0;
      width: 100%;
      padding: 0.75em 0;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 100;
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
      display: flex;
      flex-direction: row;
      justify-content: center;
      align-items: stretch;
      width: 100%;
      max-width: 1600px; /* optional: limit width */
    }
    iframe {
      border: none;
      flex: 1;
      min-width: 0;
      height: 80vh; /* scrolls if taller */
    }
    @media (max-width: 900px) {
      .embed-row {
        flex-direction: column; /* stack vertically on small screens */
      }
      iframe {
        height: 60vh;
      }
    }
    @media (max-width: 600px) {
      .top-bar-title { font-size: 1.2rem; }
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
      title="GN Math Game"
    ></iframe>
    <iframe
      src="https://eaglercraft-unblocked.neocities.org/"
      allowfullscreen
      loading="lazy"
      title="Eaglercraft Game"
    ></iframe>
  </div>
</body>
</html>
