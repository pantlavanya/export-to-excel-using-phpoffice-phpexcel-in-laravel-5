# export-to-excel-using-phpoffice-phpexcel-in-laravel-5
Export to Excel using phpoffice/phpexcel in laravel 5

Below are the step to use PHPEXCEL("https://phpexcel.codeplex.com") with laravel 5

1:- Install "phpoffice" Package in Laravel 5. Below is the link for the packages <br /> "https://packagist.org/packages/phpoffice/phpexcel".

2:-  Add "phpexcel/phpexcel": "dev-master" to your composer.json. <br />
    Ex:- "require": { "phpexcel/phpexcel": "dev-master" } <br />
    You file will be look like composer.json. I have attached the file in same repository.

3:- Then execute "composer update".

4:- Open the file "/vendor/composer/autoload_namespaces.php". Paste the below line in the file. <br />
    'PHPExcel' => array($vendorDir . '/phpoffice/phpexcel/src'),

5:- Now you can use PHPEXCEL library in your controllers or middleware or library.<br />
    use PHPExcel; <br />
    use PHPExcel_IOFactory; <br />
    
