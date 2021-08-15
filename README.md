# pick-your-own-farm
## 目錄
1. [專案展示](#專案展示)
2. [專案摘要](#專案摘要)
3. [開發介紹](#開發介紹)
    - [技術架構及摘要](#技術架構及摘要)
        - 前端開發及部署
        - 開發工具
    - [目錄架構](#目錄架構)
    - [開發流程](#開發流程)
4. [附錄](#附錄)
    - [技術介紹](#技術介紹)
    - [專案介紹](#專案介紹)

## 專案展示
- 專案網址：https://haoyuliaocurb.github.io/pick-your-own-farm/

## 專案摘要
「Pick Your Own Farm」為一 WIX 樣板臨摹，該樣板採用一頁式網頁形式，包含農場簡介、服務類別、社群貼文牆、聯絡我們等板塊。

## 開發介紹
### 技術架構及摘要
<!-- ![](https://github.com/haoyuliaocurb/pick-your-own-farm/blob/main/images/index-combined-sm.png) -->
- 更多細節可見附錄 [技術介紹](#技術介紹)
- 前端開發及部署：使用 [Sass/SCSS](#sassscss)、[Normalize.css]((#Normalizecss)) 等獨立開發，並實踐 [RWD](#專案細節)，沒有使用任何前端 UI 套件。使用 [GitHub Page](#GitHub-Page)
- 開發工具：使用 [Git/GitHub](#gitgithub) 做版本控管，並迭代進行 QA，更多細節可見 [開發流程](#開發流程)

### 目錄架構
專案目錄下具有 index.html 及存放樣式相關檔案的 styles 目錄。
* styles：放置 scss、css 等檔案；子目錄 src 中，_general.scss 具有全域 styles，_libraty.scss 存放開發者常用模組
### 開發流程
以 [Git Flow](#gitgithub) 為基礎進行開發，並迭代進行 QA
* 配合 QA 表格測試、Debug，搭配使用 [USB Debugging](#USB-debugging) 等技術
<!-- ## 優化方向 -->
## 附錄
<!-- ### 功能介紹 -->
### 技術介紹
#### 前端開發、部署
- ##### HTML
- ##### Sass/SCSS
  使用 Sass/SCSS 預處理、靜態切版
- ##### Normalize.css
  使用 Normalize.css 作跨瀏覽器 CSS 問題處理
- ##### 專案細節
  - 實踐 RWD
- ##### GitHub Page
  - 使用 GitHub Page 部署

#### 開發工具
- ##### Git/GitHub
  使用 Git/GitHub 做版本控管，實踐 Git Flow
- ##### USB Debugging
  透過 USB Debugging 技術在開發者工具中呈現手機版網頁運作狀況，包含 Console、styles 等

### 專案介紹
「Pick Your Own Farm」為一 WIX 樣板臨摹，該樣板採用一頁式網頁形式，包含農場簡介、服務類別、社群貼文牆、聯絡我們等板塊。

圖：農場簡介

![](https://github.com/haoyuliaocurb/pick-your-own-farm/blob/main/images/index-intro-lg.png)

圖：服務類別

![](https://github.com/haoyuliaocurb/pick-your-own-farm/blob/main/images/index-service-lg.png)

圖：社群貼文牆、聯絡我們

![](https://github.com/haoyuliaocurb/pick-your-own-farm/blob/main/images/index-wallNContact-lg.png)

圖左：手機版農場簡介<br>
圖右：手機版服務類別

![](https://github.com/haoyuliaocurb/pick-your-own-farm/blob/main/images/index-introNService-sm.png)

圖左：手機版社群貼文牆<br>
圖右：手機版聯絡我們

![](https://github.com/haoyuliaocurb/pick-your-own-farm/blob/main/images/index-wallNContact-sm.png)
<!-- ### 程式設計
### 組件開發總覽
#### \<App />
* ##### \<Main /> -->
