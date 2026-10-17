# courage-computer

這個專案是一個以 CRT 風格為主題的單頁 Web 應用，遵循 PDF 藍圖中的開發部署計畫，實作了以下功能：

- 復古 CRT 螢幕與酸民電腦外觀
- Tailwind CSS + Google Fonts 建立的前端設計
- Web Speech API 語音合成與低沉傲嬌配音
- Web Audio API 復古鍵盤與計算音效
- 動態 SVG 表情控制器
- GitHub Actions 自動部署到 GitHub Pages

## 目錄結構

- [index.html](index.html)：單頁應用主體
- [.github/workflows/deploy.yml](.github/workflows/deploy.yml)：GitHub Pages 自動部署設定

## 本地預覽

在專案根目錄執行：

```bash
python -m http.server 8000
```

然後在瀏覽器開啟：

```text
http://localhost:8000
```

## 部署方式

將程式碼推送到 `main` 分支後，GitHub 會依照 workflow 自動部署到 GitHub Pages。

在 GitHub Repository 的 Settings > Pages 中，將 Source 設為 GitHub Actions。
