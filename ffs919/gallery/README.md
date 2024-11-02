# Forest Finds 網頁項目

此項目是一個展示 Forest Finds 品牌的單頁面應用，使用了 Tailwind CSS 進行設計。頁面包含品牌的 LOGO、圖片展示區域以及檔主計劃的詳細信息。

## 功能概述

- **LOGO 顯示**: 頁面頂部顯示品牌的 LOGO，並提供 Instagram 的鏈接。
- **圖片展示**: 使用網格布局展示 6 張圖片，圖片自適應不同屏幕尺寸。
- **檔主計劃**: 提供三種不同的檔主計劃，詳細描述每個計劃的月租和抽成信息。

## 使用方法

1. **LOGO 和 Instagram**: 點擊頁面右上角的 Instagram 圖標可跳轉到品牌的 Instagram 帳戶。
2. **圖片展示**: 圖片自動從 `gallery` 目錄中加載，支持不同設備的自適應顯示。
3. **檔主計劃**: 在頁面下方展示三種檔主計劃，幫助用戶了解不同的租賃選擇。

## 外部文件

- **Tailwind CSS**: 使用 CDN 加載，用於頁面樣式設計。
- **Font Awesome**: 使用 CDN 加載，用於顯示 Instagram 圖標。

## 文件結構

- `index.html`: 主頁面文件，包含所有的 HTML 結構和功能。
- `images/LOGO.jpg`: 頁面頂部的 LOGO 圖片。
- `gallery/`: 存放展示圖片的目錄，圖片命名為 `image1.jpg` 至 `image6.jpg`。

## 開發規劃

- **擴展性**: 可以根據需要增加更多的圖片或修改檔主計劃的內容。
- **樣式調整**: 使用 Tailwind CSS，方便快速調整樣式和布局。

## 注意事項

- 確保 `gallery` 目錄中有足夠的圖片，並按照命名規則命名。
- LOGO 圖片應放置在 `images` 目錄中，並命名為 `LOGO.jpg`。

