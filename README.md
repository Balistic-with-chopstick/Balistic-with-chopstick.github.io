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
      overflow: scroll;
      color: #fff;
    }

    /* ===========================
       Layout Containers
       =========================== */
    body {
      display: flex;
      flex-direction: column;
    }

    .top-bar {
      height: 64px;
      width: 100%;
      background: #1565c0;
      display: flex;
      align-items: center;
      justify-content: center;
      box-shadow: 0 2px 4px rgba(0,0,0,0.4);
      flex-shrink: 0;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    .top-bar-title {
      color: #fff;
      font-size: 2rem;
      font-weight: bold;
      margin: 0;
      letter-spacing: 2px;
      text-transform: uppercase;
      animation: fadeIn 2s ease-in-out;
    }

    /* ===========================
       Embed Section
       =========================== */
    .embed-column {
      display: flex;
      flex-direction: column;
      width: 200%;
      height: 400%;
      gap: 20px;
      padding: 20px;
      box-sizing: border-box;
    }

    iframe {
      border: 4px solid #1565c0;
      border-radius: 12px;
      width: 100%;
      flex: 1;
      box-shadow: 0 8px 16px rgba(0,0,0,0.6);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    iframe:hover {
      transform: scale(1.02);
      box-shadow: 0 12px 24px rgba(0,0,0,0.8);
    }

    /* ===========================
       Footer Section
       =========================== */
    footer {
      background: #222;
      color: #aaa;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      border-top: 2px solid #1565c0;
    }

    /* ===========================
       Animations
       =========================== */
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(-10px); }
      to { opacity: 1; transform: translateY(0); }
    }

    /* ===========================
       Custom Scrollbar
       =========================== */
    ::-webkit-scrollbar {
      width: 12px;
      height: 12px;
    }
    ::-webkit-scrollbar-track {
      background: #111;
    }
    ::-webkit-scrollbar-thumb {
      background: #1565c0;
      border-radius: 6px;
    }
    ::-webkit-scrollbar-thumb:hover {
      background: #0d47a1;
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
