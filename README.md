# php7-mail-header-patch
mail header patch for php 7.0<br>
Ported patch for php 7.0 from https://choon.net/php-mail-header.php<br>
example: <br>
X-PHP-Script: www.example.com/~user/testapp/send-mail.php for 10.0.0.1<br>
<br>
Modify from original:<br>
- porting for php 7.0 (new zend api)
- adding header if running from cli/cron
- adding full path for script which send mail
