# RoboticsWorkshop

This is a MakeCode extension for controlling Gigo Robotics Workshop kits with the BBC micro:bit.

🔗 Try it in MakeCode:  
`https://makecode.microbit.org/#add-package=https://github.com/billliu329/RoboticsWorkshop`

---

## 📦 Features

- 🔄 Control DC motors
- 🔊 Play buzzer sounds
- 💡 Turn on/off LEDs
- 📟 Read values from sensors (e.g., IR, light, etc.)
- ⚙️ Suitable for STEM/robotics teaching using Gigo kits

---

## 🛠️ How to install

1. Open the [MakeCode for micro:bit](https://makecode.microbit.org) editor.
2. Click **"Advanced" → "Extensions"**.
3. Paste this URL in the search box:

https://github.com/你的帳號/RoboticsWorkshop

yaml
複製
編輯

4. Press Enter and click the extension to install.

---

## 📂 Example (JavaScript)

```ts
// Run both motors forward
robot.motorRun(1, 100)
robot.motorRun(2, 100)

// Stop after 2 seconds
basic.pause(2000)
robot.motorStopAll()
🧱 Example Blocks

<sub>(You can insert a screenshot of the blocks here later)</sub>

📌 Hardware Setup
Compatible with Gigo Robotics Workshop + micro:bit

Connect via edge connector or breakout board

Uses Micro:bit I/O pins: P0, P1, P2, etc.

🪪 License
MIT License © Gigo Toys
Made for educational purposes.

yaml
複製
編輯

---

## ✅ 建議你做的事

1. **把上面 `README.md` 內容貼到 GitHub Repo 的首頁說明欄位或 `README.md` 文件中**。
2. **把 `https://github.com/你的帳號/RoboticsWorkshop` 換成你實際的帳號與路徑**。
3. **可選：補上一張擷圖顯示積木區的樣子（上傳圖後填入連結）**

---

要我也幫你畫一張「範例積木區的圖片」嗎？  
或者如果你告訴我現在 extension 的 block 名稱與功能，我可以幫你模擬一張圖片加上去 ✅







你說：
改成繁體中文


ChatGPT 說：
以下是為你專案 RoboticsWorkshop 提供的繁體中文 README.md 說明文件，適合上架 GitHub 並提交 Micro:bit 官方 MakeCode 延伸積木審查使用：

markdown
複製
編輯
# RoboticsWorkshop 微型積木套件擴充

這是專為 **Gigo Robotics Workshop** 機器人教材與 BBC micro:bit 設計的擴充套件（MakeCode Extension）。

🔗 在 MakeCode 中加入此擴充功能：  
`https://makecode.microbit.org/#add-package=https://github.com/你的帳號/RoboticsWorkshop`

---

## 📦 功能特色

- 🔄 控制Gigo DDM馬達正轉、反轉、停止
- 🔊 控制蜂鳴器發聲
- 💡 開關 多色LED 燈
- 📟 讀取感測器數值（如：紅外線、光感測等）
- ⚙️ 適用於國小、國中 STEM 機器人課程

---

## 🛠️ 安裝教學

1. 開啟 [MakeCode for micro:bit 編輯器](https://makecode.microbit.org)
2. 點選左側 **「進階」→「擴充功能」**
3. 在搜尋框貼上以下網址：
https://github.com/billliu329/RoboticsWorkshop
4. 按 Enter，選擇「RoboticsWorkshop」套件，即可安裝成功 ✅

---

📌 硬體說明
支援 Gigo Robotics Workshop 套件

可透過 Gigo 1409主控盒連接其他相關感測器

主要使用腳位：P0、P1、P2... 等

🪪 授權說明
本專案以 MIT License 授權，歡迎自由應用與修改。
著作權 © Gigo Toys
僅供教育學習用途使用。
