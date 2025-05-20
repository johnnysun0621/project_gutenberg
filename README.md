# Project Gutenberg 中文書籍爬蟲

使用 Python 爬取 Project Gutenberg 中的中文電子書，總共取得 **200 本**以上書籍，每本儲存為純中文字 `.txt` 檔。

## 安裝套件

```bash
pip install requests beautifulsoup4
```

> 版本資訊（可參考 pip list）：
- requests 2.31.0
- beautifulsoup4 4.12.3

## 使用說明

執行 `.ipynb` 檔案即可開始爬取，程式會自動建立 `project_gutenberg/` 資料夾並存入 txt 檔。

```bash
# 若為 .py 檔：
python project_gutenberg.py
```

## 成果展示

- 共下載 txt 書籍：**200 本**
- 每本內容皆為**純中文**
- 隨機驗證 3 本內容如下：

https://www.youtube.com/watch?v=qnyPuhuLUGQ


## 補充說明

- 僅保留中文字，英文或數字內容自動過濾
- 程式已使用正則表達式排除非中文內容
