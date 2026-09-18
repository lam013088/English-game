# ⚡ 魔法拼字小學堂 - 寶可夢大冒險 ⚡
> 為小學英語生字與填空練習打造的互動式網頁學習遊戲

## 🌟 項目簡介
本專案透過 GitHub Pages 靜態託管，讓學生在 iPad、手機或電腦瀏覽器上直接點擊網址即可進行趣味拼字與句型填空練習。

- **情境視覺鷹架**：左側展示全彩寶可夢水彩手繪插圖與例句挖空提示。
- **多層次提示機制**：答錯時自動解鎖中文意思與首字母/字數鷹架。
- **即開即練（方案 B 預載架構）**：最新單元已預載至 `index.html` 中，開啟網頁直接點擊單元按鈕即可開始挑戰！

## 📁 目錄結構說明
```text
mygame/
├── index.html                   # 遊戲主程式 (已內建 Unit 1, Unit 2, p6a_unit2_fillblank, p6a_unit3_fillblank)
├── p6a_unit3_fillblank/         # P6A 第 3 課填空題卡插圖 (10 張 .jpg)
│   ├── baked.jpg
│   ├── beat.jpg
│   ├── boil.jpg
│   └── ...
├── p6a_unit2_fillblank/         # P6A 第 2 課填空題卡插圖
├── question_banks/              # 備用標準 CSV 題庫 (UTF-8 with BOM)
│   └── p6a_unit3_fillblank.csv
└── README.md                    # 本說明文件
```

## 🚀 日後如何新增下一個單元 (例如 P6A Unit 4)
1. **匯出插圖**：將 AI 生成的簡報匯出為 JPG，檔名存為該題目標生字（如 `stirred.jpg`）。
2. **建立資料夾**：在倉庫中建立 `p6a_unit4_fillblank/`，上傳所有圖片。
3. **更新題庫**：將包含新單元資料的 `index.html` 覆蓋上傳，GitHub Pages 即自動完成發布！
