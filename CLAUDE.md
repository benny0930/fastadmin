# fastadmin

FastAdmin 1.3.4 原始碼封存，作為版本參考備份。

## 內容

| 檔案 | 說明 |
|------|------|
| `1.3.4.20220530.zip` | FastAdmin v1.3.4（2022-05-30）完整原始碼 |
| `README.md` | 安裝與初始化說明 |

## 安裝（供參考）

```bash
# 前端依賴
bower install

# PHP 依賴（PHP 7.3）
composer install
# 或低記憶體環境：
cp /usr/local/bin/composer /usr/local/bin/composer1
composer1 self-update --1
php7.3 -d memory_limit=-1 /usr/local/bin/composer1 install --no-plugins

# 建立資料庫並導入初始資料
php think install -u <db_user> -p <db_password>
```

## 注意

此 repo 僅作版本存檔，實際開發請參照 `benny` repo。
