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
      box-sizing: border-box;
    }
    *, *::before, *::after { box-sizing: inherit; }

    body {
      height: 100vh;          /* exactly the viewport height */
      overflow: hidden;       /* no extra scrolling */
      display: flex;
      flex-direction: column;
    }

    .top-bar {
      height: var(--bar-height);
      width: 100vw;
      background: #1565c0;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 2px 4px rgba(0,0,0,0.2);
      flex: 0 0 var(--bar-height); /* fixed height */
    }

    .top-bar-title {
      color: #fff;
      font-size: 1.5rem;
      font-weight: bold;
      margin: 0;
      letter-spacing: 1px;
    }

    .embed-row {
      width: 100vw;
      height: calc(100vh - var(--bar-height)); /* fill the rest of the screen */
      display: flex;
    }

    iframe {
      border: none;
      width: 50vw;   /* half the screen each */
      height: 100%;  /* full remaining height */
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
