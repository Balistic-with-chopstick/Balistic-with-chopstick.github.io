<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Super Mario 64</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    html, body {
      height: 100%;
      margin: 0;
      padding: 0;
      background: #000;
    }
    body {
      width: 100vw;
      height: 100vh;
      overflow: hidden;
      display: flex;
      flex-direction: column;
    }
    .fullscreen-frame, #emulator-container {
      flex: 1;
      border: none;
      width: 100vw;
      height: 100vh;
    }
    .info {
      color: #fff;
      background: #333;
      padding: 0.5em;
      text-align: center;
      font-size: 0.9em;
      z-index: 9;
    }
  </style>
</head>
<body>
  <div id="emulator-container"></div>
  <script src="emulator.js"></script>
  <script>
    // Place your emulator initialization here.
    // For example, if you're using a specific JS N64 emulator, initialize it with the container:
    // Emulator.init(document.getElementById('emulator-container'));
  </script>
</body>
</html>
