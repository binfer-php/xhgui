
#

### 安装 mongodb, xhprof扩展

### 解析到webroot


```php
修改php配置文件中的auto_prepend_file配置
auto_prepend_file = /xhgui/external/hader.php

apache:  php_admin_value auto_prepend_file "/xhgui/external/hader.php"

nginx:   fastcgi_param PHP_VALUE "auto_prepend_file=/xhgui/external/hader.php";
```