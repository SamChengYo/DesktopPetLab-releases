# DesktopPetLab 下載

Windows 本機 3D 角色桌寵與動作工作台。這個儲存庫只放安裝包，不含原始碼。

## 下載與安裝

1. 到 [Releases](../../releases/latest) 下載 `DesktopPetLab-<版本>-windows-x64.zip`。
2. **完整解壓**到一個可以寫入的資料夾（不要直接從 ZIP 裡開啟，也不要只複製 exe）。
3. 開啟 `DesktopPetLab.exe`。第一次開啟會自動安裝語音環境，可能需要數十分鐘，中途關掉下次會續傳。

`update-*.json`、`pack-*.zip`、`SHA256SUMS.txt` 是程式自動更新用的，不需要手動下載。

## 電腦需求

- Windows 10／11 64 位元。Windows 10 若沒有 WebView2 執行環境，請先從微軟官網安裝。
- 角色聲音需要 NVIDIA 顯示卡與新版驅動。沒有的話仍可使用桌寵、動畫與文字對話。
- 至少 30 GB 可用空間（語音環境與模型約 20 GB，另有下載快取；C 槽也要留幾 GB 給快取）。
- 第一次安裝需要網路。

## 第一次使用

- 語音喚醒：在工作台「對話」為角色完成三次「Hi＋角色名字」語音登錄，再開啟麥克風喚醒。
- Agent 對話：需要你自己的 OpenAI API 金鑰，在工作台「對話 → 模型與 API 設定」指定金鑰檔案。
