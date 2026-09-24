# 櫻花大戰 DC 繁體中文移植計畫 (SakuraTaisen-TraditionalChinese)

## 📖 專案目的 (Project Purpose)

1. **解決現代系統相容性問題**：目前的《櫻花大戰》官方 PC 中文版在 Windows 11 作業系統環境下非常不友善，玩家在執行與遊玩時經常會遇到各種相容性障礙。

2. **提升跨平台遊玩體驗**：希望讓喜愛這款經典遊戲的玩家，可以透過 Dreamcast (DC) 模擬器，在現代的 PC 或是掌上型遊戲機（手提機，如 Steam Deck 等）上順暢重溫《櫻花大戰》。

## 🛠️ 製作與技術說明 (Technical Details)

* 本專案基於 **PSP 版的簡體漢化** 文本為基礎進行修改。

* 將原有的漢化文本與字體，重新編譯並 **移植至 Dreamcast (DC) 版本** 的遊戲中。

* 配合專案目標，將文本與字體轉換/優化為繁體中文，以提供更佳的閱讀體驗。

## 📸 遊戲截圖 (Screenshots)

![遊戲截圖 1](Screenshot%202026-09-23%20132125.png)

![遊戲截圖 2](Screenshot%202026-09-23%20132213.png)

![遊戲截圖 3](Screenshot%202026-09-23%20132229.png)

## 🚀 使用方法 (How to Play)

### 1. 映像檔準備與補丁套用 (Image Preparation and Patching)
本專案補丁是基於 Internet Archive 中 Dreamcast GDI Japan 內的 `Sakura Taisen v1.010 (2000)(Sega)(JP)` 版本而制定。

請依照以下步驟套用補丁：
1. 準備好對應版本的日文遊戲映像檔（IMAGE）。
2. 將日文 IMAGE 分別放入對應的資料夾內：
   * 將 CD1 的日文 IMAGE 放入 `CD1` 資料夾內。
   * 將 CD2 的日文 IMAGE 放入 `CD2` 資料夾內。
3. 執行批次檔來建立中文 IMAGE：
   * 點擊執行 `CD1_PATCH.BAT`。
   * 點擊執行 `CD2_PATCH.BAT`。

正確的檔案與資料夾配置結構應如下所示（可參考附圖）：
```text
CD1\cd1.cht.v0.6.patch
CD1\<日文IMAGE CD1>
CD2\cd2.cht.v0.6.patch
CD2\<日文IMAGE CD2>
CD1_PATCH.BAT
CD2_PATCH.BAT
cd-patcher.exe
```

### 2. 模擬器遊玩 (Play with Emulator)
準備支援 Dreamcast 的模擬器（例如：Flycast, Redream 等）。

透過模擬器載入剛剛建立好的中文遊戲映像檔即可開始遊玩。

☕ 支持與贊助 (Donation)
如果您喜歡這個專案，並希望支持後續的開發與維護，歡迎透過 PayPal 掃碼贊助！
(qrcode.png)
⚠️ 免責聲明 (Disclaimer)
本專案僅供程式技術研究、字體移植測試與學習交流使用，遊戲本體及文本版權歸原遊戲公司與原漢化團隊所有。請玩家務必支持並購買正版遊戲，請勿將本專案用於任何商業營利用途。