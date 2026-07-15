# 食快啲啦 Eatfaster

- **App link：** https://mssallyct.github.io/eatfaster/
- **GitHub repo：** https://github.com/mssallyct/eatfaster
- **類型：** 親子進餐鼓勵 PWA / 手機網頁 App
- **語言：** 香港繁體中文為主，完成鼓勵語音支援廣東話 / English

## App 目標

- 幫小朋友建立開心、有節奏、安全嘅進餐習慣。
- 小朋友每食完一啖，就可以按一次 **「餵寵物一啖！」**。
- App 會提醒小朋友：**慢慢咀嚼，吞咗先可以再撳**。
- 重點係鼓勵進餐節奏，唔係催促小朋友狼吞虎嚥。

## 主要玩法

- 選擇今餐目標：
  - 10 啖
  - 15 啖
  - 20 啖
- 選擇食飯地方：
  - 家中飯枱
  - 日式小廚房
  - 公園野餐
  - 學校飯堂
  - 海邊餐墊
  - 森林小屋
  - 太空飯堂
  - 電車月台
  - 糖果小屋
- 選擇寵物：
  - 胖胖貓
  - 胖柴犬
  - 胖兔仔
  - 胖熊貓
  - 胖企鵝
  - 胖倉鼠
  - 胖水豚
  - 胖小象
  - 胖小恐龍
- 進食時：
  - 小朋友食完一啖
  - 按 **「餵寵物一啖！」**
  - 寵物會做餵食動畫
  - 進度條會增加
  - 播放對應寵物聲效

## 最新完成事項

- 已改為獨立 GitHub repo：
  - `mssallyct/eatfaster`
- 已部署到獨立 GitHub Pages：
  - https://mssallyct.github.io/eatfaster/
- 已確認不再放喺數獨 repo 入面。
- 已修正手機進食版面：
  - 壓縮進度卡高度
  - 壓縮寵物舞台高度
  - 壓縮提示訊息高度
  - 壓縮底部餵食按鈕高度
  - 加入 `visualViewport` 動態高度修正
  - 避免 Safari / WhatsApp 內置瀏覽器底欄遮住 **「餵寵物一啖！」** 按鈕
- 已更新 service worker cache：
  - `eatfaster-prototype-v16-mobile-game-fit`

## 圖像設計

- 全部正式圖像使用 Gemini PNG 卡通風格。
- 風格方向：
  - 溫暖日系復古兒童漫畫
  - 圓潤可愛
  - 柔和手繪感
  - 適合小朋友使用
- 已有素材：
  - 9 張背景 PNG
  - 9 隻寵物 PNG
  - 12 款食物 PNG
- 食物圖已處理：
  - 透明背景
  - 無白框
  - 無外框

## 聲效設定

- 餵食聲效已改為跟隨所選寵物。
- 每隻寵物都有對應嘅真實動物聲可愛版。
- 動物叫聲整理為三音節乾淨版。
- 聲效位置：
  - `assets/sounds/pet-calls/`
- 已不再使用舊咀嚼聲資料夾：
  - `assets/sounds/chewing10/`

## 完成今餐畫面

- 完成目標後會顯示 **「完成今餐！」**。
- 完成畫面上方會顯示所選寵物原圖。
- 不使用拿碟子圖。
- 不使用大肚摸肚完成圖。
- 完成後會播放鼓勵語音。

## 鼓勵語音

- 只保留：
  - 廣東話
  - English
- 廣東話語音：
  - `assets/voices/encourage-yue.mp3`
- 英文語音：
  - `assets/voices/encourage-en.mp3`
- 已移除國語語音引用：
  - `encourage-zh.mp3`

## PWA / 手機支援

- 可用手機瀏覽器打開。
- 支援 GitHub Pages 靜態部署。
- 包含：
  - `manifest.json`
  - `sw.js`
  - app icon
  - cache assets
- 手機版已針對短畫面重新調整，確保餵食按鈕留喺可見範圍內。

## 主要檔案

- `index.html`
  - App 主程式、畫面、互動、聲效邏輯
- `manifest.json`
  - PWA 設定
- `sw.js`
  - Service worker / cache 設定
- `assets/gemini/pets/`
  - 寵物 PNG
- `assets/gemini/foods/`
  - 食物 PNG
- `assets/gemini/backgrounds/`
  - 背景 PNG
- `assets/sounds/pet-calls/`
  - 寵物聲效 MP3
- `assets/voices/`
  - 完成鼓勵語音 MP3

## 使用連結

- 正式 App：
  - https://mssallyct.github.io/eatfaster/
- GitHub：
  - https://github.com/mssallyct/eatfaster
