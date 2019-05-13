# simpleGrep
這是用來快速查找檔案的工具

- **[ -p / --path]** 查找路徑 (預設為當下目錄)
    
- **[ -n / --next ]** 想查詢的下一個關鍵字
    可以在查找完一個關鍵字後，以此結果再查找下一個關鍵字.

- **[ --exclude-dir ]** 忽略此目錄下的檔案，可以使用 ',' 連接多個目錄

- **[ --exclude-file ]** 忽略此檔案，可以使用 ',' 連接多個檔案


- **[ -t / --type ]** 檔案類型，可以只查找特定的檔案類型


## Install


```
git clone https://github.com/z20240/simpleGrep ~/.simpleGrep

sudo ln -s ~/.simpleGrep/grepTool /usr/local/bin/grepTool
```
