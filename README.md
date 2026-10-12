<div align="center">

# 🔮 My Web Lens

**A minimal full-screen 3D starter for the browser.**

[![PlayCanvas](https://img.shields.io/badge/PlayCanvas-2.23-E05F2C?style=flat-square)](https://github.com/playcanvas/engine)
[![Vite](https://img.shields.io/badge/Vite-8-646CFF?style=flat-square&logo=vite&logoColor=white)](https://vite.dev/)

</div>

A rotating, lit box on a dark blue canvas that fills the window. Mobile-ready: touch gestures and overscroll are disabled, and the pixel ratio is capped at 2.

## 🚀 Quick start

```bash
npm install
npm run dev
```

Open the URL Vite prints. Edits reload automatically.

## 📜 Scripts

| Command           | Description                                  |
| ----------------- | -------------------------------------------- |
| `npm run dev`     | Dev server with hot reload                   |
| `npm run build`   | Production bundle into `dist/`               |
| `npm run preview` | Serve `dist/` on your local network          |

> 📱 **Test on a phone:** run `build`, then `preview`, and open the "Network" URL from a device on the same Wi-Fi.

## 📁 Structure

```
index.html       Full-screen <canvas id="app"> and base styles
src/main.js      Scene: camera, light, box, and update loop
vite.config.js   Relative asset paths (base: "./"), es2020 target
```

To change the scene, edit the entities in `src/main.js` before `app.start()`.
