# Obsidian 學習島嶼

依據 Salima 的 [Obsidian 智慧大腦養成術](https://hahow.in/courses/69f5ab12ad4fc2ec5695f2cf) 公開課程大綱製作，對應六章、23 個單元。

## 內容
- 六座可探索的 SVG 島嶼與完整單元導覽。
- 每單元提供原創觀念說明、實作任務、參考範例與學習日誌。
- 六個觀念挑戰、進度、XP、徽章與最終成果自評。
- 日誌以 localStorage 儲存在目前瀏覽器，可匯出 Markdown。
- 無後端、無追蹤、無外部套件，直接開啟 index.html 即可使用。

此專案為課程導覽及原創延伸練習，不包含課程影片。正式作業與外掛名單以課程為準。AI 相關練習在學員自己的工具執行；網頁不會連接 AI 或存取本機 Vault。

## GitHub Pages

在 repository **Settings → Pages** 將 Source 設為 **Deploy from a branch**，選擇 **main / (root)** 並儲存。

預期網址：https://101academyforyou.github.io/obsidian-learning/

## 本機預覽

用瀏覽器開啟 index.html，或執行 `python -m http.server 8000`。

## 檢查

已檢查 JavaScript 語法，並以瀏覽器驗證開啟單元、輸入日誌、完成任務、答題回饋、進度更新與重新載入後保存。

## 修改內容

`index.html` 的 `chapters` 陣列包含單元、任務、範例及章節題目。`requirements` 包含最終自評清單。
