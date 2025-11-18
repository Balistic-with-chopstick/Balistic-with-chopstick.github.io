<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>DLC</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    /* ===========================
       Global Reset & Base Styles
       =========================== */
    html, body {
      margin: 0;
      padding: 0;
      height: 100vh;
      width: 100vw;
      background: linear-gradient(180deg, #000 0%, #111 100%);
      font-family: Arial, Helvetica, sans-serif;
      overflow-y: scroll;   /* vertical scroll bar */
      overflow-x: hidden;   /* no horizontal scroll */
      color: #fff;
      box-sizing: border-box;
    }

    /* ===========================
       Layout Containers
       =========================== */
    body {
      display: flex;
      flex-direction: column;
      align-items: flex-start;   /* align everything to the left */
      width: 100vw;
    }

    .top-bar {
      height: 64px;
      width: 100vw;              /* stretch full width */
      background: #1565c0;
      display: flex;
      align-items: center;
      justify-content: flex-start; /* content aligned left */
      padding-left: 20px;          /* spacing from left edge */
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

    /* ===========================
       Embed Section
       =========================== */
    .embed-column {
      display: flex;
      flex-direction: column;
      width: 100vw;              /* stretch full width */
      gap: 20px;
      padding: 20px;
      box-sizing: border-box;
      align-items: flex-start;   /* align iframes to left */
    }

    iframe {
      border: 4px solid #1565c0;
      border-radius: 12px;
      width: 100%;               /* full width of window */
      height: 120vh;             /* taller than viewport for scroll */
      box-shadow: 0 8px 16px rgba(0,0,0,0.6);
    }

    /* ===========================
       Footer Section
       =========================== */
    footer {
      width: 100vw;              /* stretch full width */
      background: #222;
      color: #aaa;
      text-align: left;          /* align text left */
      padding: 20px;
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
