# 費馬最後定理 · 一句頁邊註記，數學家追了 358 年

一個單頁網站，用廣東話解釋費馬最後定理（Fermat's Last Theorem）：

- 命題到底在講甚麼（為何 n = 2 有解、n ≥ 3 無解）
- 它是對還是錯 —— 為甚麼 1995 年之後它是「定理」而非「猜想」
- 358 年的歷史時間線（費馬、歐拉、熱爾曼、庫默、弗雷、里貝特、懷爾斯）
- 證明思路的三層結構：問題縮減 → 古典方法 → 弗雷曲線 + 模性定理
- 互動反例搜尋器（BigInt 精確運算，即時窮舉）
- 六個常見誤解的拆解

單一 HTML 檔，無外部依賴（無 CDN、無字體下載），可離線開啟。

## 檔案

| 檔案 | 說明 |
|---|---|
| `index.html` | 整個網站（HTML + CSS + JavaScript 內嵌） |

## 本地預覽

直接雙擊 `index.html`，或：

```bash
python3 -m http.server 8000
```

然後開 http://localhost:8000

## 線上版本

https://tyhcch1234.github.io/fermat-last-theorem/

## 資料來源

- Andrew Wiles, *Modular elliptic curves and Fermat's Last Theorem*, Annals of Mathematics 141 (1995), 443–551
- Taylor & Wiles, *Ring-theoretic properties of certain Hecke algebras*, Annals of Mathematics 141 (1995), 553–572
- Ribet, *On modular representations of Gal(Q̄/Q) arising from modular forms*, Inventiones Mathematicae 100 (1990)
- Simon Singh, *Fermat's Enigma* (1997)

本頁為科普整理，呈現證明的邏輯骨架，而非完整證明。
