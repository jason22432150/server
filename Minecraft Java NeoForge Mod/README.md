## 🛠️ 安裝 Mod 教學 (NeoForge)

### 1. 安裝 NeoForge Mod 載入器

1.  前往 [NeoForge 官方網站](https://neoforged.net/forge/) 以下載頁面 (或其官方發布頁面，例如 CurseForge 或 Modrinth 上的 NeoForge 頁面)。
2.  選擇您的 Minecraft 版本，然後下載推薦的 NeoForge 安裝程式 (Installer)。
3.  執行下載的安裝程式，選擇 "Install client"，然後點擊 "OK"。
4.  開啟 Minecraft 啟動器，您應該會在設定檔列表中看到一個新的 NeoForge 設定檔。

### 2. 下載 Mod

1.  從 [您的 Mod 下載連結，例如：CurseForge, Modrinth, GitHub Releases] 下載 Mod 的 `.jar` 檔案。
2.  **請確保下載的 Mod 版本與您的 Minecraft 版本以及您安裝的 NeoForge 版本相容。**

### 3. 將 Mod 放入 `mods` 資料夾

1.  開啟您的 Minecraft 遊戲資料夾。通常的路徑如下：
    *   **Windows:** 按下 `Win + R`，輸入 `%appdata%\.minecraft`，然後按 Enter。
    *   **macOS:** 在 Finder 中，按下 `Shift + Command + G`，輸入 `~/Library/Application Support/minecraft`，然後按 Enter。
    *   **Linux:** 在您的家目錄中找到 `.minecraft` 資料夾 (通常是隱藏的，按 `Ctrl + H` 顯示)。
2.  在 `.minecraft` 資料夾中，找到或創建一個名為 `mods` 的資料夾。
3.  將您在步驟 2 中下載的 Mod `.jar` 檔案複製或移動到這個 `mods` 資料夾中。

### 4. 啟動遊戲

1.  開啟 Minecraft 啟動器。
2.  選擇您在步驟 1 中安裝的 NeoForge 設定檔。
3.  點擊 "Play" (開始遊戲)。
4.  如果一切順利，Mod 將會被載入。您可以在遊戲的主選單或特定介面中檢查 Mod 是否已成功安裝 (通常 Mod 列表會顯示已載入的 Mod)。

### 疑難排解

*   **遊戲崩潰或 Mod 未載入：**
    *   檢查 Mod 版本是否與 Minecraft 版本和 NeoForge 版本相容。
    *   確保您已安裝所有必要的前置 Mod (如果 Mod 說明中有提到)。
    *   檢查 `.minecraft/logs` 資料夾中的最新日誌 (`latest.log`) 或崩潰報告 (`crash-reports` 資料夾) 以獲取錯誤訊息。
*   **找不到 `mods` 資料夾：** 如果 `mods` 資料夾不存在，您可以手動創建它。
