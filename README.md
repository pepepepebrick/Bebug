# What if your "Code" could be a "Bug"?

This is an interactive system built with **TouchDesigner** and **VS Code** that transforms your code into a visualized "Bug" in Real-time.

`TouchDesigner`  `VS Code`  `Python`  `Microsoft Partner`

(圖1:程式碼+蟲子)


## 🪲 Code to Hatch, DeBug to BeBug

This interactive system breathes life into your code. By automatically reading characters directly from **VS Code**, it tracks the lifecycle of a beetle—from egg and larva to pupa and adult.

(圖2:孵化過程)

## 🧫 Code can also reflect your personal style

Beyond randomizing colors, sizes, and shapes, you can even choose between species like stag bugs, rhinoceros beetles, scarabs, or weevils. Whether you're building websites, developing apps, or live-coding music, this companion stays by your side, letting developers “BeBug” while they DeBug.

(圖3:個人風格化+:四種蟲子)
(圖4:多種並列)

## 🧬 Simulating nature through code

For this workflow, I integrated **VS Code** with **TouchDesigner** to handle the coding. VS Code is incredibly versatile with its support for various languages and extensions, making the development much more efficient. For example, in TouchDesigner I used `Script SOP` nodes and `Python` to generate the 3D coordinates and geometric attributes for the bug’s bodies and legs. I then utilized `Script DAT` to loop the code every 80 characters, converting it into a structured data table.

(圖5:程式協作介面/程式化/演算法)

## 🔬 The life cycle of a bug

* Main Title: (Row 1) Max 15 chars, spaces OK. "//" hidden. (e.g., Project Name)
* Subtitle: (Row 2) Max 15 chars, spaces OK. "//" hidden. (e.g., Name/Date)
* Body Text: (Starts from Row 3) Line breaks and spaces are ignored; loops every **80 chars** with carryover. (e.g., Code)
  - Char 1: *Egg*
  - Chars 2-10: *Larva*
  - Chars 11-20: *Pupa*
  - Chars 21-30: *Adult - Head*
  - Chars 31-40: *Adult - Body*
  - Chars 41-50: *Adult - Antennae*
  - Chars 51-80: *Adult - Legs*

(圖6:規則、部位解說)

## 🫙 Installation Guide

* **STEP1**: Download the `BeBug.toe` file for this project.
* **STEP2**: Download [VS Code](https://www.google.com) and note its installation path, and download [TouchDesigner](https://www.google.com)
* **STEP3**: Open TouchDesigner, go to `Settings/Preferences` from the top bar and click on the `DAT` subtab.
* **STEP4**: Click the folder icon next to `Text Editor`, select the VS Code executable `(Code.exe)`, and click `Save`.
* **STEP5**: Close TouchDesigner and open the `BeBug.toe` file.
* **STEP6**: Select the `text1` node (pink). Press `'P'` to open/close the sidebar, then click `Edit` under the `File` tab.
* **STEP7**: Type in `VS Code` to start hatching your bugs.
* **STEP8**: Click the star icon on the `container1` node (gray) to access personal settings. To expand the view, right-click the `null1` node (purple) and select `View`.

⚙️ [Youtube: TouchDesigner and VS Code Integration Tutorial](https://www.youtube.com/watch?v=pgPgOKxW1V4)


## ⛰️ Credit

Developer｜[pepepepebrick](https://www.instagram.com/pepepepebrick/)  
Partner｜[Microsoft Developer](https://www.instagram.com/microsoftdeveloper/)  
Live Coding Music｜[Zoe Chen](https://www.instagram.com/zcguide.42/)  
Video Editing｜[Piin Ann](https://www.instagram.com/piin_ann/)  


🟥 🟩  
🟦 🟨  



