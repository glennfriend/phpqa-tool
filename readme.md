#phpqa

###how to use
```
project_path="/var/www/your_project/"
phpqa_tool="/var/www/tool/phpqa/vendor/bin/phpqa"
cd $your_project
$phpqa_tool --ignoredDirs build,vendor,node_modules --report
```

###look all tools
```sh
./vendor/bin/phpqa tools
```

###from
```
http://jaceju.net/2017-01-11-php-quality-analysis/
```

#framework example
```sh
yii     => --ignoredDirs build,vendor,composer,framework,react-ui,protected/vendors,protected/test,protected/migrations,protected/runtime
laravel => --ignoredDirs build,vendor
```