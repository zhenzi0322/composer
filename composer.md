
## composer初始化项目
```cmd
composer init
```

```cmd
PS F:\PHP\composer_package> composer init


  Welcome to the Composer config generator



This command will guide you through creating your composer.json config.

Package name (<vendor>/<name>) [long/composer_package]: test
The package name test is invalid, it should be lowercase and have a vendor name, a forward slash, and a package name, matching: [a-z0-9_.-]+/[a-z0-9_.-]+
Package name (<vendor>/<name>) [long/composer_package]: zhenzi0322/test
Description []: test description
Author [long <1962036114@qq.com>, n to skip]:
Minimum Stability []: dev
Package Type (e.g. library, project, metapackage, composer-plugin) []: project
License []: MIT

Define your dependencies.

Would you like to define your dependencies (require) interactively [yes]?
Search for a package:
Would you like to define your dev dependencies (require-dev) interactively [yes]? no

{
    "name": "zhenzi0322/test",
    "description": "test description",
    "type": "project",
    "license": "MIT",
    "authors": [
        {
            "name": "long",
            "email": "1962036114@qq.com"
        }
    ],
    "minimum-stability": "dev",
    "require": {}
}

Do you confirm generation [yes]? yes
Would you like the vendor directory added to your .gitignore [yes]? yes
PS F:\PHP\composer_package>
```


## 安装
```cmd
composer install
```