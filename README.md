# Louis' 作品集

<!-- ## 介紹

歡迎來到我的作品集！我是 Louis Xie，一位具有豐富經驗的前端開發者和架構師，專注於構建高效、安全且用戶友好的網絡應用。我在金融科技、電信和銀行業務領域有多年的工作經歷，並且在項目管理、敏捷開發和技術架構設計方面有著深厚的積累。通過這個作品集，我將展示我的主要項目和技術專長，並分享我在各個項目中所獲得的寶貴經驗和成就。 -->

金融科技、電信與企業協作領域的前端開發：行動銀行 App（Cordova / MobileFirst）、網路銀行架構（Angular / NgRx）、舊系統框架升級（Angular.js → Vue.js），以及導入 Jenkins CI。

> 截圖中的帳號、電子郵件與他人姓名已遮蔽。

## 專案

| 專案 | 領域 | 主要技術 |
| --- | --- | --- |
| [元大銀行](#元大銀行) | 行動銀行 App | Cordova、MobileFirst 8、iOS / Android 原生、Jenkins |
| [台新銀行 Richart](#台新銀行-richart) | 行動銀行 App、網路銀行 | Angular、NgRx、TypeScript、Cordova、Jenkins |
| [遠傳電信](#遠傳電信) | 內部系統 | Vue.js、Angular.js、webpack、PWA |
| [訊真科技 WorkDo](#訊真科技-workdo) | 企業協作平台 | Angular.js、LESS、Gulp |

---

## 元大銀行

**技術**：HTML、CSS、JavaScript、Cordova、MobileFirst 8、iOS（Objective-C）、Android（Java）、Jenkins、Nginx

**職責**

- 前端需求分析與開發，確保各裝置上的一致性與回應速度
- 將 Jenkins CI 導入開發流程，建立自動化建置與測試管線

### 基金改版

- 重新設計基金申購與管理的前端介面，使其更直覺易用
- 以設計模式抽出可重用元件，同時套用到海外債與美股頁面

| | | | |
| --- | --- | --- | --- |
| <img src="./images/yuanta-fund-01.webp" alt="基金申購入口" width="180"> | <img src="./images/yuanta-fund-02.webp" alt="選擇基金" width="180"> | <img src="./images/yuanta-fund-03.webp" alt="篩選條件" width="180"> | <img src="./images/yuanta-fund-04.webp" alt="篩選結果" width="180"> |
| <img src="./images/yuanta-fund-05.webp" alt="基金申購資料填寫" width="180"> | <img src="./images/yuanta-fund-06.webp" alt="基金總覽" width="180"> | <img src="./images/yuanta-fund-07.webp" alt="申購清單" width="180"> | <img src="./images/yuanta-fund-08.webp" alt="定期定額" width="180"> |
| <img src="./images/yuanta-fund-09.webp" alt="產品搜尋" width="180"> | <img src="./images/yuanta-fund-10.webp" alt="熱門搜尋標籤" width="180"> | <img src="./images/yuanta-fund-11.webp" alt="基金交易明細查詢" width="180"> | |

**美股頁面**（共用基金改版的元件）

| | | |
| --- | --- | --- |
| <img src="./images/yuanta-us-stock-1.webp" alt="境外股票申購" width="180"> | <img src="./images/yuanta-us-stock-2.webp" alt="選擇標的" width="180"> | <img src="./images/yuanta-us-stock-3.webp" alt="個股申購" width="180"> |

### 台灣 Pay 畫面改版

- 改善台灣 Pay 支付介面，提升使用體驗與操作便利性

| | | |
| --- | --- | --- |
| <img src="./images/yuanta-taiwan-pay-1.webp" alt="帳戶支付" width="180"> | <img src="./images/yuanta-taiwan-pay-2.webp" alt="支付綁定" width="180"> | <img src="./images/yuanta-taiwan-pay-3.webp" alt="支付額度" width="180"> |

### 全盈+PAY 整合

- 將全盈+PAY SDK 整合進既有 App，支援更多支付方式

<img src="./images/yuanta-plus-pay.webp" alt="全盈+PAY" width="180">

### 轉帳成功訊息分享

- 轉帳成功後可將通知訊息分享到 LINE 等社群平台

<img src="./images/yuanta-transfer-share.webp" alt="轉帳成功訊息分享" width="180">

---

## 台新銀行 Richart

**技術**：HTML、CSS / SCSS、JavaScript、TypeScript、Angular、NgRx、Cordova、MobileFirst 8、Spring Boot（Java）、Jenkins

**職責**

- Richart App 前端開發與維護，確保穩定性與使用體驗
- 將 Jenkins CI 導入開發流程，建立自動化建置與測試管線
- 協助團隊將 TFS 看板轉移到 JIRA，改善專案管理與追蹤流程

### Richart App

<img src="./images/taishin-richart-app.webp" alt="Richart App 登入畫面" width="180">

### Richart 網路銀行前端架構

- 規劃 Angular + NgRx + SCSS 架構，切分核心模組、功能模組與共享模組
- 帶領外包廠商開發，直到團隊能獨立運作

<a href="https://richart.tw/WebBank/users/login"><img src="./images/taishin-richart-web-bank.webp" alt="Richart 網路銀行" width="720"></a>

---

## 遠傳電信

**技術**：HTML、CSS / SCSS、JavaScript、Angular.js、Vue.js、require.js、webpack、PWA

**職責**：前端需求分析與開發

### NSP 表單系統升級

- 將 NSP 表單系統從 Angular.js 升級為 Vue.js，提升效能與可維護性

<img src="./images/fet-nsp-forms.webp" alt="NSP 表單系統" width="720">

### 包膜師專案

- 包膜師專案的前端開發

<img src="./images/fet-lamination.webp" alt="包膜師專案" width="720">

---

## 訊真科技 WorkDo

**技術**：HTML、CSS / LESS、JavaScript、Angular.js、Gulp

**職責**：WorkDo 企業協作平台的前端開發

| | |
| --- | --- |
| <img src="./images/workdo-1.webp" alt="WorkDo 動態牆" width="400"> | <img src="./images/workdo-2.webp" alt="WorkDo 行事曆" width="400"> |
| <img src="./images/workdo-3.webp" alt="WorkDo 帳號設定" width="400"> | <img src="./images/workdo-4.webp" alt="WorkDo 通知" width="400"> |
