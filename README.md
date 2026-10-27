<p align="center"><img src="assets/IMG_01_09-08-2025.jpg" alt="Imagem do projeto Concept-Car-Design" width="100%" /></p>

<h1 align="center">🚘 Concept Car Design</h1>

<p align="center"><em>Visualização interativa de um conceito automotivo 3D.</em></p>

<p align="center">🇧🇷 Português | 🇺🇸 <a href="README.en.md">English</a></p>

<p align="center"><img src="https://img.shields.io/badge/license-MIT-006bed?style=flat-square" alt="MIT" /> <img src="https://img.shields.io/github/last-commit/Felipe-Amorim-Dev/Concept-Car-Design?style=flat-square&color=006bed" alt="Last commit" /></p>

<p align="center"><a href="#sobre">Sobre</a> • <a href="#tecnologias">Tecnologias</a> • <a href="#como-rodar">Como rodar</a> • <a href="#licenca">Licença</a> • <a href="#autor">Autor</a></p>

---

<a id="sobre"></a>
## 📖 Sobre

Projeto demonstrativo que utiliza Three.js para carregar o arquivo STL de um veículo, com câmera orbital, zoom, grade e alternância de materiais.

## ✨ Funcionalidades

- Visualização do modelo STL
- Controles de órbita, zoom e pan
- Troca de material pela tecla T

<a id="tecnologias"></a>
## 🛠️ Tecnologias

![HTML5](https://img.shields.io/badge/HTML5-006bed?style=for-the-badge) ![JavaScript](https://img.shields.io/badge/JavaScript-006bed?style=for-the-badge) ![Three.js 0.160](https://img.shields.io/badge/Three.js_0.160-006bed?style=for-the-badge) ![WebGL](https://img.shields.io/badge/WebGL-006bed?style=for-the-badge)

## 📦 Pré-requisitos

Servidor HTTP local e acesso à internet para carregar módulos Three.js.

<a id="como-rodar"></a>
## 🚀 Como rodar

```bash
git clone https://github.com/Felipe-Amorim-Dev/Concept-Car-Design.git
cd Concept-Car-Design
python -m http.server 8000
```

## 📸 Demonstração

[Acessar projeto](https://felipe-amorim-dev.github.io/Concept-Car-Design/)

## 🔗 Repositórios relacionados

[CAD-Viewer](https://github.com/Felipe-Amorim-Dev/CAD-Viewer) — Biblioteca de visualização 3D.

## 🏗️ Organização e implementação do projeto

- O projeto concentra a experiência 3D em index.html, com importação de módulos Three.js pela CDN.
- STLLoader lê assets/Concept_Car.stl; OrbitControls implementa rotação, pan e zoom.
- WebGLRenderer desenha a cena, enquanto iluminação Hemisphere/Directional/Ambient e GridHelper compõem a apresentação.
- Ao carregar a geometria, o código recalcula normais, centraliza o modelo e ajusta sua escala.
- A tecla T alterna MeshPhysicalMaterial e MeshNormalMaterial; resize atualiza proporção da câmera e viewport.

### Estrutura e recursos

Os principais arquivos e recursos estão em `assets/Concept_Car.stl`. O ponto de entrada é `index.html`.

<a id="licenca"></a>
## 📄 Licença

Distribuído sob a [licença MIT](LICENSE).

<a id="autor"></a>
## 👤 Autor

**Felipe Figueiredo Amorim** — Desenvolvedor Full Stack.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Felipe%20Amorim-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/felipe-amorim-dev/) [![E-mail](https://img.shields.io/badge/E--mail-contato-006bed?style=for-the-badge)](mailto:felipe.f.amorim@outlook.com)

<p align="center"><strong>Obrigado por visitar! / Thanks for visiting!</strong></p>
