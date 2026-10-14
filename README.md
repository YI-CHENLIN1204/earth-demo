# Earth Demo

使用 **Three.js / WebGL** 製作的 3D 地球視覺化練習，包含地球表面貼圖、法線貼圖、雲層、燈光與 OrbitControls 操作。

## 實作內容

- Three.js 3D scene / camera / renderer
- Sphere geometry 與多層材質
- Normal / Specular / Cloud textures
- Ambient / Directional / Point Light
- OrbitControls
- 地球與雲層獨立旋轉動畫

## 技術

`Three.js` `WebGL` `HTML` `JavaScript`

主要程式集中在 [index.html](./index.html)。Three.js 由 CDN import，repository 只保留實際使用的本地貼圖資產。

## 執行

使用任一 static HTTP server 開啟即可，例如：

```bash
python -m http.server 8000
```

再開啟 `http://localhost:8000`。

## 專案定位

此 repository 為前端 3D 視覺化的學習與實驗紀錄，並非目前研究所作品集的主要專案。

主要作品請參考我的 [GitHub Profile](https://github.com/YI-CHENLIN1204)。
