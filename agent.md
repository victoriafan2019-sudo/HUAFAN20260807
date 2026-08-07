# 專案紀錄

## 概要

此專案為靜態單頁網站，以 Bootstrap 5 建立「癒見 YUJIAN」健康療癒服務的銷售頁。頁面依照 UI/UX 設計稿完成響應式切版。

## 專案結構

```text
website/
├── index.html
└── images/
    ├── pah (1).png
    ├── pah.png
    └── Pyrene_numbered.png
```

## 技術與相依

- HTML5
- Bootstrap 5.3.3（透過 jsDelivr CDN 載入 CSS 與 JavaScript Bundle）
- Google Fonts：Noto Serif TC、Noto Sans TC
- 自訂 CSS 內嵌於 `index.html`
- 不含套件設定檔或建置工具

## 頁面功能

### 導覽列

使用 Bootstrap 可折疊與置頂導覽列，包含「癒見初衷、為何失衡、旅程內容、聽見身體、預約相遇」等頁內錨點連結。

### 首頁主視覺

以自然人物照片搭配標題與引導文字，並在桌機與手機版調整文字位置、背景裁切與可讀性。

### 銷售頁區塊

- 疲憊、隱形疲勞與焦慮內耗的症狀引導卡片
- 「癒見初衷」品牌理念與 Why／How／What 三欄內容
- 「為何失衡？」PAS 模型流程
- 「旅程內容」FAB 模型服務價值
- 「聽見身體」SWOT 優勢說明
- 預約諮詢與了解療癒故事的 CTA 按鈕

## 執行方式

此為純靜態網站，直接以瀏覽器開啟 `index.html` 即可預覽；若使用本機開發伺服器，將專案根目錄設為網站根目錄即可。

## 待改善項目

- 將 CTA 按鈕連結至正式的 LINE 預約與品牌故事頁面。
- 以正式授權的品牌、人物與服務圖片取代目前的示意圖。
- 依品牌規範替換 Unicode 圖示為正式 SVG 圖示。
- 視需求拆出獨立 CSS 檔，方便後續維護。

## 維護備註

- Bootstrap、Google Fonts 與目前的示意圖片皆來自外部 CDN；離線環境下樣式、字型與圖片無法完整載入。
- `images/` 內的三張既有圖片目前未被銷售頁使用。
- 專案中未發現版本控制或套件管理設定檔。
## GITHUB推送地址
USER NAME:victoriafan2019-sudo
專案名稱:HUAFAN20260807
HTTPS:https://github.com/victoriafan2019-sudo/HUAFAN20260807.git
SSH:git@github.com:victoriafan2019-sudo/HUAFAN20260807.git
