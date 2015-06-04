# colin1124x/auth-basic
[![Build Status](https://travis-ci.org/colin1124x/auth-basic.svg?branch=master)](https://travis-ci.org/colin1124x/auth-basic)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/colin1124x/auth-basic/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/colin1124x/auth-basic/?branch=master)
[![Code Coverage](https://scrutinizer-ci.com/g/colin1124x/auth-basic/badges/coverage.png?b=master)](https://scrutinizer-ci.com/g/colin1124x/auth-basic/?branch=master)
[![Build Status](https://scrutinizer-ci.com/g/colin1124x/auth-basic/badges/build.png?b=master)](https://scrutinizer-ci.com/g/colin1124x/auth-basic/build-status/master)
[![SensioLabsInsight](https://insight.sensiolabs.com/projects/3c0de3c4-ac2c-406b-ba2d-f374b4d76cd3/mini.png)](https://insight.sensiolabs.com/projects/3c0de3c4-ac2c-406b-ba2d-f374b4d76cd3)

```php

// 建構一個 basic 驗證物件

$basic = new Rde\Auth\Basic(array(
    'user_name' => 'encode_password', // 請使用 password_hash
));

// 登入判斷

$basic->isAuthorized() or $basic->challenge();

```
