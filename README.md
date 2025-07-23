<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Alya in AR</title>
    <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.min.js"></script>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <model-viewer
      src="alya.glb"
      ar
      ar-modes="scene-viewer quick-look webxr"
      camera-controls
      auto-rotate
      environment-image="neutral"
      shadow-intensity="1"
      style="width:100vw; height:100vh;">
    </model-viewer>
  </body>
</html>
body {
  margin: 0;
  background: #000;
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
}
model-viewer {
  width: 100%;
  height: 100%;
