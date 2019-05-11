# simpleGrep
這是用來快速查找檔案的工具

- **[ -p / --path]** path 目前設定
    \. => 當下目錄
    指定目錄 => 完整目錄 ex ~/Desktop/XXX/XXX
    指定目錄 => 非完整目錄 ex ~/Downloads/XXX/XXX

- **[ -n / --next ]** 想查詢的下一個關鍵字
    可以在查找完一個關鍵字後，以此結果為立基查找下一個關鍵字.

- **[ --exclude-dir ]** 忽略此目錄下的檔案，可以使用 ',' 連接多個目錄

- **[ --exclude-file ]** 忽略此檔案，可以使用 ',' 連接多個檔案


- **[ -t / --type ]** 檔案類型
    (可以只查找特定的檔案類型)
    \. => 目前設定可查找的檔案類型為：php perl js css html log vue ts json
