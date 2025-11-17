<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>DLC</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    :root { --bar-height: 64px; }

    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
      background: #000;
      font-family: Arial, Helvetica, sans-serif;
    }

    body {
      display: flex;
      flex-direction: column;
      height: 100vh; /* full viewport height */
    }

    .top-bar {
      height: var(--bar-height);
      width: 100%;
      background: #1565c0;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 2px 4px rgba(0,0,0,0.2);
      flex: 0 0 var(--bar-height); /* fixed height */
    }

    .top-bar-title {
      color: #fff;
      font-size: 2rem;
      font-weight: bold;
      margin: 0;
      letter-spacing: 1px;
    }

    .embed-row {
      flex: 1; /* take up remaining vertical space */
      display: flex;
      justify-content: center; /* center horizontally */
      align-items: center;     /* center vertically */
      gap: 10px;               /* optional space between iframes */
    }

    iframe {
      border: none;
      width: 45%;   /* each iframe takes ~half width but leaves gap */
      height: 90%;  /* centered vertically with some margin */
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
