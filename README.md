# What if your "Code" could be a "Bug"?🪲

This is an interactive system built with **TouchDesigner** and **VS Code** that transforms your code into a visualized "Bug" in Real-time.  
這是一個 **TouchDesigner** 與 **VS Code** 的互動系統，它可以將你的程式碼即時變成一隻蟲子  

`TouchDesigner`  `VS Code`  `Python`  `Microsoft Partner`  
<br>
![image_alt](https://github.com/pepepepebrick/Bebug/blob/92e014617dda065b9c4f935990fbc30ec2f173a1/01.png)  
<br>
<br>
## 🐞 Code to Hatch, Debug to Bebug

This interactive system breathes life into your code. By automatically reading characters directly from **VS Code**, it tracks the lifecycle of a beetle—from egg and larva to pupa and adult.  

**從 Debug 到 Bebug：** 這是一個可以用「寫程式」來孵化甲蟲的互動系統，它能自動讀取 **VS Code** 中的字元，讓程式碼從卵、幼蟲、蛹再變為成蟲
<br>
<br>
![image_alt](https://github.com/pepepepebrick/Bebug/blob/92e014617dda065b9c4f935990fbc30ec2f173a1/02.gif)  
<br>
<br>
## 🧫 Code can also reflect your personal style

Beyond randomizing colors, sizes, and shapes, you can even choose between species like stag bugs, rhinoceros beetles, scarabs, or weevils. Whether you're building websites, developing apps, or live-coding music, this companion stays by your side, letting developers “Bebug” while they Debug.  

**程式碼也能展現你的個人風格：** 除了能改變隨機顏色、尺寸與造型，還能選擇鍬形蟲、獨角仙、金龜子或象鼻蟲。不論是在寫網頁、開發APP或在即時編程音樂，它都能陪伴著你寫程式，讓工程師們在 Debug 時也能 “Bebug”  
<br>
![image_alt](https://github.com/pepepepebrick/Bebug/blob/92e014617dda065b9c4f935990fbc30ec2f173a1/03.png)  
  
![image_alt](https://github.com/pepepepebrick/Bebug/blob/92e014617dda065b9c4f935990fbc30ec2f173a1/04.gif)  
<br>
<br>
## 🧬 Simulating nature through code

For this workflow, I integrated **VS Code** with **TouchDesigner** to handle the coding. VS Code is incredibly versatile with its support for various languages and extensions, making the development much more efficient. For example, in TouchDesigner I used `Script SOP` nodes and `Python` to generate the 3D coordinates and geometric attributes for the bug’s bodies and legs. I then utilized `Script DAT` to loop the code every 80 characters, converting it into a structured data table.  

**用程式臨摹大自然的規則：** 這次我在 **TouchDesigner** 中使用了 **VS Code** 進行協作，它支援廣泛的程式語言與擴充元件，讓我能更方便的編輯程式碼。例如在 TouchDesigner 中，昆蟲的身體與腳，我都是透過 `Script SOP` 節點，用 `Python` 來寫出線段的3D座標與幾何屬性；接著再用 `Script DAT` 將程式碼以80個字元為單位進行循環，並轉換為特定形式的資料表格  
<br>
![image_alt](https://github.com/pepepepebrick/Bebug/blob/92e014617dda065b9c4f935990fbc30ec2f173a1/05.png)  
<br>
<br>
## 🔬 The life cycle of a bug

* Main Title: (Row 1) Max 15 chars, spaces OK. `'//'` hidden. (e.g., Project Name)
* Subtitle: (Row 2) Max 15 chars, spaces OK. `'//'` hidden. (e.g., Name/Date)
* Body Text: (Starts from Row 3) Line breaks and spaces are ignored; loops every **80 chars** with carryover. (e.g., Code)
  - Char 1: *Egg*
  - Chars 2-10: *Larva*
  - Chars 11-20: *Pupa*
  - Chars 21-30: *Adult - Head*
  - Chars 31-40: *Adult - Body*
  - Chars 41-50: *Adult - Antennae*
  - Chars 51-80: *Adult - Legs*
<br>

**Bebug 互動系統的規則：**  
* 大標題（第一行）：字數上限15字，可使用空格，`//`符號不顯示。適合填寫專案名稱
* 次標題（第二行）：字數上限15字，可使用空格，`//`符號不顯示。適合填寫名字、日期
* 內文（第三行開始）：分行與空格都會忽略，以 **80個字元** 循環，超過後遞補。適合填寫你的程式碼
  - 字元1：*卵*
  - 字元2-10：*幼蟲*
  - 字元11-20：*蛹*
  - 字元21-30：*成蟲 - 頭*
  - 字元31-40：*成蟲 - 身體*
  - 字元41-50：*成蟲 - 觸角*
  - 字元51-80：*成蟲 - 腳*  
<br>

![image_alt](https://github.com/pepepepebrick/Bebug/blob/fd5ac7bfb83b6f92343edbf43186598ed58c2194/image/07.jpg)  
<br>
![image_alt](https://github.com/pepepepebrick/Bebug/blob/92e014617dda065b9c4f935990fbc30ec2f173a1/06.gif)  
<br>
<br>
## 🫙 Installation Guide

⚙️ [Youtube: TouchDesigner and VS Code Integration Tutorial](https://www.youtube.com/watch?v=pgPgOKxW1V4)  

* **STEP1**: Download the `Bebug.toe` file for this project.
* **STEP2**: Download [VS Code](https://www.google.com) and note its installation path, and download [TouchDesigner](https://www.google.com)
* **STEP3**: Open TouchDesigner, go to `Settings/Preferences` from the top bar and click on the `DAT` subtab.
* **STEP4**: Click the folder icon next to `Text Editor`, select the VS Code executable `(Code.exe)`, and click `Save`.
* **STEP5**: Close TouchDesigner and open the `Bebug.toe` file.
* **STEP6**: Select the `text1` node (pink). Press `'P'` to open/close the sidebar, then click `Edit` under the `File` tab.
* **STEP7**: Type in VS Code to start hatching your bugs.
* **STEP8**: Click the star icon on the `container1` node (gray) to access personal settings. To expand the view, right-click the `null1` node (purple) and select `View`.  
<br>

**安裝教學：**  
* **步驟1**: 下載這個專案的 `Bebug.toe` 檔案
* **步驟2**: 下載 [VS Code](https://www.google.com) 並記得儲存位置，以及下載 [TouchDesigner](https://www.google.com)
* **步驟3**: 在 TouchDesigner 開啟導航欄中的 `Settings/Preferences`，點擊子分頁 `DAT`
* **步驟4**: 點擊 `Text Editor` 右側的資料夾圖示，選擇 VS code 的程式執行檔 `(Code.exe)`，並點擊 `Save`
* **步驟5**: 關閉 TouchDesigner，並開啟步驟1下載的 `Bebug.toe` 檔案
* **步驟6**: 選取畫面中的 `text1` 節點（粉紅色的），按按鍵 `'P'` 開啟/關閉側欄，點擊 `File` 頁面中的 `Edit` 按鈕
* **步驟7**: 在 VS Code 中輸入文字，開始孵化蟲子
* **步驟8**: 在 TouchDesigner 中，點擊 `container1` 節點（灰色的）右下角的星星符號，可以做個人化的設定。在 `null1` 節點（紫色的）點擊右鍵選單的 `view`，可以展開視窗
<br>

## ⛰️ Credit

**Developer 開發者**｜[pepepepebrick](https://www.instagram.com/pepepepebrick/)  
**Partner 合作夥伴**｜[Microsoft Developer](https://www.instagram.com/microsoftdeveloper/)  
**Live Coding Music 程式音樂**｜[Zoe Chen](https://www.instagram.com/zcguide.42/)  
**Video Editing 影片剪輯**｜[Piin Ann](https://www.instagram.com/piin_ann/)  
<br>
<br>
🟥 🟩  
🟦 🟨  



