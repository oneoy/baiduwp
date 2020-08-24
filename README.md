# baiduwp-php
PanDownload 网页复刻版，PHP 语言版<br/>
本项目是依据 [baiduwp](https://github.com/TkzcM/baiduwp "baiduwp") 的 JavaScript 版本改写而来，仅供大家学习参考<br/>

## 安装注意事项
- 使用了 `SESSION`，注意 **PHP 访问系统文件（夹）权限**问题
- 仅支持 **PHP 7 和 7+**！

## Setting
请在 `config.php` 中找：
```
define('BDUSS', '');
define('STOKEN', '');
define('IsCheckPassword', true);
define('Password', '请在这里填写密码啦！ヾ(≧▽≦*)o');
```
