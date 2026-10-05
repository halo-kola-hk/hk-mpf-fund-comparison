# 強積金基金表現比較 (MPF Fund Performance Comparison)

互動式數據可視化工具，比較香港強積金（MPF）基金的投資表現。

## 功能

- **折線圖**：顯示累積回報 Top 10 基金，由高至低排列
- **可切換時段**：1年、5年、10年、成立至今
- **點擊查看詳情**：基金開支比率、風險級別、費用明細（積金易平台費、受託人費、投資管理費等）
- **搜尋功能**：按基金名稱、計劃名稱或受託人搜尋

## 數據來源

- [積金局強積金基金平台](https://mfp.mpfa.org.hk/tch/mpp_list.jsp) - 官方基金表現、費用數據
- [積金局註冊強積金計劃](https://www.mpfa.org.hk/info-centre/public-registers/registered-mpf-schemes) - 計劃註冊資料
- 數據截至 2026年8月31日
- 覆蓋 447 個基金，24 個強積金計劃

## 技術

- 純 HTML + CSS + JavaScript（無框架依賴）
- Chart.js 用於折線圖渲染
- 響應式設計，支援手機瀏覽

## 使用

直接用瀏覽器打開 `index.html` 即可，或部署到任何靜態網站託管平台。
