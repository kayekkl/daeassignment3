```markdown
# 可搜尋清單 (手機網頁界面)

## 學生資料

- 姓名：Ki, Ka Lai
- 學號：24822795
- 主題編號：5
- 主題名稱：開源硬體

## 功能完成度自評

（依照評分標準勾選完成的項目）

### 基本功能（40 分）

- 清單顯示

  - 顯示所需欄位
    - [x] 4 個文字欄位（3 分）
    - [x] 圖片正確顯示（2 分）
    - [x] 影片正確播放（1 分）
  - 資料完整性
    - [x] 至少 20 個項目（3 分）
    - [x] 資料合理且有意義（3 分）
  - [x] 版面配置合理（3 分）

- 搜尋功能

  - 關鍵字搜尋
    - [x] 空白關鍵字顯示所有項目（2 分）
    - [x] 單一關鍵字可正確過濾（4 分）
    - [x] 大小寫不敏感（2 分）
  - [x] 即時更新（4 分）
  - [x] 使用體驗流暢（3 分）

- 分類功能
  - 選擇類別
    - [x] 使用 ion-select（2 分）
    - [x] 點擊標籤可切換分類（2 分）
  - 分類過濾
    - [x] 未選擇時顯示所有項目（2 分）
    - [x] 選擇後正確過濾項目（2 分）
  - [x] 搜尋和分類組合使用（2 分）

### 界面設計（30 分）

- 響應式設計

  - 小型螢幕（5 分）
    - [x] 內容不會擠壓
    - [x] 不需橫向捲動
  - 中型螢幕（5 分）
    - [x] 最佳化的預設版面
  - 大型螢幕（5 分）
    - [x] 合理運用空間

- 視覺設計
  - 介面美觀
    - [x] 合理的間距和配色（4 分）
    - [x] 一致的設計風格（4 分）
  - 操作流暢
    - [x] 清晰的視覺回饋（4 分）
    - [x] 順暢的動畫效果（3 分）

### 技術實現（30 分）

- 程式碼品質

  - 代碼結構
    - [x] 模組化設計（4 分）
    - [x] 命名規範（2 分）
    - [x] 註解完整（2 分）
  - 可維護性
    - [x] 代碼重用（4 分）
    - [x] 錯誤處理（3 分）

- Ionic 運用
  - UI 元件使用
    - [x] 正確使用 Ionic 元件（5 分）
    - [x] 元件組合得當（3 分）
  - JavaScript 實作
    - [x] 事件處理（4 分）
    - [x] DOM 操作（3 分）

### 加分項目

1. 資料過濾與排序

   - [x] 支援多個分類同時選擇（3 分）
   - [ ] 加入日期範圍過濾（3 分）
   - [x] 支援標籤過濾（2 分）
   - [ ] 依照不同欄位排序（3 分）
   - [ ] 支援升冪/降冪切換（2 分）

2. 介面優化

   - [ ] 使用卡片視圖（3 分）
   - [ ] 支援列表/網格視圖切換（3 分）
   - [ ] 加入簡單的統計圖表（3 分）
   - [ ] 加入載入動畫效果（3 分）
   - [ ] 加入頁面切換動畫（2 分）

3. 功能擴展

   - [ ] 使用 LocalStorage 保存過濾設定（3 分）
   - [ ] 支援收藏功能（3 分）
   - [ ] 實作進階搜尋選項（3 分）

## 專案功能

- **動作清單**：顯示所有瑜伽動作的清單，包含縮圖和基本資訊
- **搜尋功能**：透過關鍵字搜尋動作名稱或描述（支援中英文關鍵字）
- **分類篩選**：根據難度和效果進行分類過濾
- **詳細資訊**：點擊動作項目可查看完整資訊、示範圖片和教學影片
- **響應式設計**：適應不同裝置尺寸(手機、平板、桌機)的顯示效果
- **雙語支持**：提供繁體中文和英文的完整介面和內容切換功能

## 雙語功能

應用程式實現了完整的雙語支持，具有以下特點：

- **語言切換按鈕**：每個頁面頂部都有語言切換按鈕（地球圖標），點擊可在繁體中文和英文間切換
- **記住語言偏好**：應用會使用 localStorage 記住用戶的語言偏好，下次訪問時自動應用
- **完整雙語內容**：所有內容（包括瑜伽動作名稱、效果、注意事項、界面元素等）均提供繁體中文和英文版本
- **搜尋增強**：無論使用中文或英文關鍵字搜尋，都能找到相關的瑜伽動作
- **動態更新**：切換語言時，頁面內容即時更新，無需重新載入

## 技術架構

- **HTML5**：頁面結構和內容
- **CSS3**：樣式和響應式設計
- **JavaScript**：互動功能和資料處理
- **Ionic 框架**：UI 元件和樣式
  - ion-list, ion-item
  - ion-searchbar
  - ion-select
  - ion-card
  - ion-button 等
- **LocalStorage**: 儲存用戶語言偏好

## 頁面說明

1. **首頁/清單頁 (index.html)**

   - 搜尋欄
   - 分類選單
   - 動作清單(含縮圖、名稱、難度和效果標籤)
   - 語言切換按鈕

2. **詳細頁 (detail.html)**

   - 動作詳細資訊(名稱、難度、效果、注意事項)
   - 示範圖片(可點擊放大)
   - 教學影片
   - 語言切換按鈕

3. **關於頁 (about.html)**

   - 應用程式介紹
   - 開發背景
   - 開發者資訊
   - 語言切換按鈕

4. **聯絡頁 (contact.html)**
   - 聯絡表單
   - 聯絡資訊
   - 常見問題
   - 語言切換按鈕

## 如何使用

1. 直接在瀏覽器中開啟 `index.html` 檔案即可使用本應用
2. 無需安裝任何額外套件或伺服器環境
3. 點擊頂部的地球圖標可切換語言

## 資料結構

應用程式使用 JavaScript 陣列存儲 20 個瑜伽動作的資料，每個動作包含以下資訊：

- 動作名稱（繁體中文和英文）
- 難度 (初級、中級、高級)
- 效果（繁體中文和英文）
- 注意事項（繁體中文和英文）
- 效果標籤（力量、柔軟度、平衡、放鬆）
- 示範圖片 URL
- 教學影片 URL

## 開發目標

本專案旨在練習 Ionic 框架的基本使用，以及實作具備搜尋和分類功能的清單應用程式。項目著重於以下幾個方面的實踐：

1. 使用 Ionic CDN 建立網頁應用程式
2. 運用 Ionic UI 元件建立使用者介面
3. 實作事件處理與 DOM 操作
4. 響應式設計原則
5. 實現多語言支持和本地化

## 授權說明

本專案僅用於教育目的，圖片和影片內容來自公開資源，僅供學習使用。

## 技術實現亮點

1. **CSS 類別控制**：使用 CSS 類別和 HTML 屬性控制不同語言內容的顯示和隱藏
2. **事件委派**：優化事件處理，提高性能
3. **動態內容渲染**：根據語言設置動態生成和更新頁面內容
4. **本地存儲**：使用 localStorage 保存用戶偏好設置
5. **響應式設計**：在不同裝置上提供一致的雙語用戶體驗
6. **語義化標記**：使用適當的 HTML 結構和屬性支持多語言內容