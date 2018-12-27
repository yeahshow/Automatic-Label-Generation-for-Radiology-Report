
## 環境設定
- 使用 pipenv

  ```pipenv sync --dev```

- 使用 pre-commit 避免 commit 超大檔案

  ```pre-commit install```

- 設定相對路徑

  參考 config_sample.py, 把大硬碟的位置和本地資料的位置分別輸入，另存成 config.py 在本地端。

- 執行 femh_subset.ipynb

  對大資料庫進行取樣，製作一個 subset資料集方便處理。
