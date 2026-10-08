# 在 Windows 安裝 Animavyr

1. 開啟[最新版本頁面](https://github.com/Niaudio/Animavyr/releases/latest)。
2. 下載 `Animavyr-Setup-x64.exe` 或帶有版本號的 Windows x64 安裝檔。
3. 下載對應的 `.sha256` 檔案，在執行前核對安裝檔的 checksum。
4. 執行安裝檔，依 Windows 畫面提示完成安裝。
5. 從開始功能表或桌面捷徑啟動 Animavyr。

## 未知發行者與 SmartScreen

目前預設安裝檔未簽章，因此 Windows 可能顯示未知發行者或 SmartScreen 警告。在決定繼續之前，請確認檔案來自本 repository 的官方 Release 頁面，且 SHA-256 與附帶的 checksum 一致。

未簽章本身不代表檔案遭到竄改，但也無法提供 Authenticode 發行者身分驗證。若 checksum 不符，或檔案來自其他來源，請停止安裝。

## LM Studio 與 ComfyUI

LM Studio 與 ComfyUI 為選用工具，不隨 Animavyr 提供。只有需要對應的本機 AI 功能時，才需另外安裝並啟動這些服務。
