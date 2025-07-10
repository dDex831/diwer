# 浩軒國際貿易有限公司 - 客製化禮品靜態網站
# https://www.diwer.me/haoxuan.html

本專案是一個使用 HTML、CSS、JavaScript、Bootstrap 和 Swiper 製作的靜態網站，提供企業禮贈品、交屋包、戶外用品等商品的展示功能。



---

## 🔧 功能介紹

### ✅ 導覽列 Navigation Bar
- 品牌 LOGO + 名稱顯示
- 「產品目錄」可下拉展開，並自動抓取頁面內所有 `.outdoor-title` 區塊，排除「推薦」字樣
- 點擊各項目可自動跳轉至該區塊（錨點跳轉）

### ✅ 輪播圖 Carousel
- 使用 Bootstrap 的 Carousel
- 支援左右切換控制
- 自動輪播每 5 秒切換

### ✅ 商品展示區（多組）
- 使用 Swiper.js 建構可滑動的商品區塊
- 每組 `.outdoor-section` 對應一個 Swiper 輪播
- 可自動適應不同螢幕尺寸（響應式）
- 滑動商品時支援自由模式 (freeMode)

### ✅ 圖片放大預覽功能
- 點擊圖片會顯示放大視圖
- 滑鼠移動時可移動放大區域焦點
- 點擊任意位置關閉預覽

### ✅商品卡片進場動畫效果
- 使用的是輕量又常見的 AOS（Animate On Scroll） 函式庫

---

## 🖼️ 圖片路徑規範
- 所有圖片路徑採用相對路徑，放置於 `images-web/` 資料夾中

---

## 📁 專案結構（節錄）

