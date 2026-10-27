<p align="center"><img src="assets/IMG_01_09-08-2025.jpg" alt="Project image Concept-Car-Design" width="100%" /></p>

<h1 align="center">🚘 Concept Car Design</h1>

<p align="center"><em>Interactive 3D concept car visualization.</em></p>

<p align="center">🇧🇷 <a href="README.md">Português</a> | 🇺🇸 English</p>

<p align="center"><img src="https://img.shields.io/badge/license-MIT-006bed?style=flat-square" alt="MIT" /> <img src="https://img.shields.io/github/last-commit/Felipe-Amorim-Dev/Concept-Car-Design?style=flat-square&color=006bed" alt="Last commit" /></p>

<p align="center"><a href="#sobre">About</a> • <a href="#tecnologias">Technologies</a> • <a href="#como-rodar">Run locally</a> • <a href="#licenca">License</a> • <a href="#autor">Author</a></p>

---

<a id="sobre"></a>
## 📖 About

Demo project using Three.js to load a vehicle STL model, with orbit controls, zoom, grid and material switching.

## ✨ Features

- STL model display
- Orbit, zoom and pan
- Press T to switch materials

<a id="tecnologias"></a>
## 🛠️ Technologies

![HTML5](https://img.shields.io/badge/HTML5-006bed?style=for-the-badge) ![JavaScript](https://img.shields.io/badge/JavaScript-006bed?style=for-the-badge) ![Three.js 0.160](https://img.shields.io/badge/Three.js_0.160-006bed?style=for-the-badge) ![WebGL](https://img.shields.io/badge/WebGL-006bed?style=for-the-badge)

## 📦 Prerequisites

Local HTTP server and Internet connection to load Three.js modules.

<a id="como-rodar"></a>
## 🚀 Run locally

```bash
git clone https://github.com/Felipe-Amorim-Dev/Concept-Car-Design.git
cd Concept-Car-Design
python -m http.server 8000
```

## 📸 Demo

[Visit the project](https://felipe-amorim-dev.github.io/Concept-Car-Design/)

## 🔗 Related repositories

[CAD-Viewer](https://github.com/Felipe-Amorim-Dev/CAD-Viewer) — 3D viewer library.

## 🏗️ Project organization and implementation

- The 3D experience lives in index.html and imports Three.js modules through a CDN.
- STLLoader reads assets/Concept_Car.stl and OrbitControls supports orbit, pan and zoom.
- WebGLRenderer draws the scene with Hemisphere/Directional/Ambient lighting and GridHelper.
- After loading, the geometry receives computed normals, is centered and scaled to fit.
- T toggles MeshPhysicalMaterial and MeshNormalMaterial; resize updates the camera and viewport.

### Rendering and assets

The central project assets can be found in `assets/Concept_Car.stl`. The entry point is `index.html`.

<a id="licenca"></a>
## 📄 License

Distributed under the [MIT license](LICENSE).

<a id="autor"></a>
## 👤 Author

**Felipe Figueiredo Amorim** — Full Stack Developer.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Felipe%20Amorim-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/felipe-amorim-dev/) [![E-mail](https://img.shields.io/badge/E--mail-contato-006bed?style=for-the-badge)](mailto:felipe.f.amorim@outlook.com)

<p align="center"><strong>Obrigado por visitar! / Thanks for visiting!</strong></p>
