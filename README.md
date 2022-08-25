
# 下載前端插件依賴包
bower install

# 下載PHP依賴包
composer install

# 一鍵創建數據庫並導入數據
php think install -u 數據庫用戶名 -p 數據庫密碼

# 調整 composer 為 v1
   - cp /usr/local/bin/composer /usr/local/bin/composer1
   - composer1 self-update --1
   - php7.3 -d memory_limit=-1 /usr/local/bin/composer1 install --no-plugins
