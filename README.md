# PHPUnit

How to run the test:

1. Unzip the file unit-testing.zip

2. Find out where your PHP is living. For example, my is here:
   c:/OpenServer/modules/php/PHP_8.0/php.exe

3. Open the file: /unit-testing/vendor/bin/phpunit, and set the first line as:
   #!/usr/bin/env c:/OpenServer/modules/php/PHP_8.0/php.exe

4. Open your terminal (Git Bash) and make sure you are in: /unit-testing

5. Run the command: ./vendor/bin/phpunit tests

-----------------------

Как запустить тест:

1. Разархивируйте файл unit-testing.zip

2. Узнайте, где находится ваш PHP. Например, мой здесь:
    c:/OpenServer/modules/php/PHP_8.0/php.exe

3. Откройте файл: /unit-testing/vendor/bin/phpunit и установите первую строку так:
    #!/usr/bin/env c:/OpenServer/modules/php/PHP_8.0/php.exe

4. Откройте ваш терминал и убедитесь, что вы находитесь в: /unit-testing

5. Выполните команду: ./vendor/bin/phpunittests