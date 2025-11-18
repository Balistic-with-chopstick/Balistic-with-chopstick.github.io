<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>DLC</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    /* Global reset */
    * {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
      width: 100%;
      background: linear-gradient(180deg, #000 0%, #111 100%);
      font-family: Arial, Helvetica, sans-serif;
      color: #fff;
      overflow-y: scroll;   /* vertical scroll */
      overflow-x: hidden;   /* no horizontal scroll */
    }

    /* Layout */
    body {
      display: flex;
      flex-direction: column;
      align-items: stretch;   /* full width */
    }

    .top-bar {
      height: 64px;
      width: 100%;            /* use percent to avoid scrollbar width issues */
      background: #1565c0;
      display: flex;
      align-items: center;
      justify-content: flex-start;
      /* remove left padding to kill the gap */
      padding: 0;
      box-shadow: 0 2px 4px rgba(0,0,0,0.4);
    }

    .top-bar-title {
      color: #fff;
      font-size: 2rem;
      font-weight: bold;
      margin: 0 0 0 0;        /* no margin pushing content right */
      letter-spacing: 2px;
      text-transform: uppercase;
      /* add minimal inner spacing via a wrapper if needed */
    }

    /* Optional: inner spacer to create controlled space without shifting the bar */
    .top-bar-content {
      padding-left: 8px;
      width: 100%;
    }

    .embed-column {
      display: flex;
      flex-direction: column;
      width: 100%;            /* stretch to edges */
      gap: 16px;
      /* remove padding to avoid left gap */
      padding: 0;
    }

    iframe {
      border: 4px solid #1565c0;
      border-radius: 12px;
      width: 100%;
      height: 120vh;          /* taller than viewport for vertical scroll */
      box-shadow: 0 8px 16px rgba(0,0,0,0.6);
    }

    footer {
      width: 100%;
      background: #222;
      color: #aaa;
      text-align: left;
      padding: 12px 0 12px 8px;  /* small internal padding, not container padding */
      font-size: 0.9rem;
      border-top: 2px solid #1565c0;
    }

    /* Debug helper: uncomment to visualize edges
    .top-bar, .embed-column, footer { outline: 1px dashed rgba(255,255,255,0.25); }
    */
  </style>
</head>
<body>
  <div class="top-bar">
    <div class="top-bar-content">
      <span class="top-bar-title">DLC</span>
    </div>
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
