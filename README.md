# 𓃥 白六 DEATH STAR HOLO-COMM | 帝國中秋全息通訊器

[![Deploy to GitHub Pages](https://github.com/kuochili-ops/Lunar-message/actions/workflows/pages/pages-build-deployment/badge.svg)](https://kuochili-ops.github.io/Lunar-message/)
![Three.js](https://img.shields.io/badge/Three.js-r128-black?style=flat&logo=three.js)
![License](https://img.shields.io/badge/License-MIT-green.svg)

線上體驗：[https://kuochili-ops.github.io/Lunar-message/](https://kuochili-ops.github.io/Lunar-message/)

---

## 📌 簡介

**𓃥 白六 DEATH STAR HOLO-COMM** 是一款結合星際大戰（Star Wars）死星（Death Star）與中秋賞月意象的 3D 全息通訊互動網頁應用程式。

開場呈現 100% 滿月姿態，隨著球體優雅的 3D 雙軸旋轉（Yaw & Pitch Down），死星金屬裝甲與北半球 3D 立體超級雷射凹盤將俯衝對齊正中央，並從凹盤中心噴射出帶著游離微光粒子的綠色全息光錐（Holographic Cone），呈現動態排版的中秋祝賀詞。

---

## 🌟 核心特色

- **雙面擬真貼圖 (Dual Texture Mapping)**：開場 100% 正滿月質感，旋轉後無縫銜接死星鋼鐵裝甲與經緯面板線條。
- **3D 立體凹盤與法線對齊 (3D Superlaser Dish)**：採用獨立 3D 幾何體打造向內凹陷的超級雷射碟盤，具備 32 條輻射金屬線與深邃立體光影，並精確對齊球面法線（Normal Vectors）。
- **粒子游離全息系統 (Holographic Particle Dust)**：全息光錐內部加入 180+ 顆動態升騰與閃爍的微光粒子，重現星戰科幻全息投影質感。
- **雙階段自然運鏡與姿態**：球體順暢進行 180° 水平旋轉後，再銜接 X 軸俯衝傾斜，將全息文字完美的呈現在螢幕正中央。
- **動態祝賀詞斷行與輪播**：動態 Canvas 文字排版，文字旋轉居中後自動觸發輪播。
- **一鍵自動錄影下載 (WebM Exporter)**：內建 WebGL 高畫質錄影機制（60 FPS），點擊後自動從開場旋轉錄製至所有賀詞完整播放完一次，自動打包下載 `.webm` 影片。

---

## 🛠️ 技術棧

- **3D 渲染引擎**：[Three.js (r128)](https://threejs.org/)
- **視角互動控制**：OrbitControls.js
- **畫面擷取與錄影**：MediaRecorder API & HTMLCanvasElement `captureStream()`
- **前端技術**：HTML5, CSS3 (Glassmorphism / HUD Theme), ES6+ JavaScript

---

## 🚀 快速開始

本專案為純前端單頁應用程式（SPA），無需安裝任何依賴套件即可直接運行。

### 本地開發

1. 複製本儲存庫：
   ```bash
   git clone [https://github.com/kuochili-ops/Lunar-message.git](https://github.com/kuochili-ops/Lunar-message.git)
