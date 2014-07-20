Модуль Oplata для 1C Bitrix.
=====

Данный модуль подходит для версий Малый бизнес, Бизнес и Бизнес Веб-кластер.
--


#Инструкция по установке модуля оплаты Oplata под 1C Битрикс

Папку oplata нужно разместить в `{Корневой каталог сайта}/bitrix/php_interface/include/sale_payment/`

Файл oplata_result.php нужно вставить в папку `{Корневой каталог сайта}/bitrix/tools/`

#После этого необходимо :

>1. Зайти в административную часть интернет магазина.

>2. Перейти на страницу "Платежные системы" ( "Магазин" -> "Настройки магазина" -> "Платежные системы" )

>3. Нажать на кнопку "Добавить платежную систему"

>4. Заполнить общие данные о платежной системе.

>5. Перейти на нужную вкладку ( "Физические лица" или "Юридические лица" ) и заполнить всю необходимую информацию

>6. Сделать платежную систему активной и нажать "Сохранить"


В настройках вашего мерчанта на Oplata необходимо указать ссылку возврата информации о статусе платежа на страницу `http://yoursite.com/bitrix/tools/oplata_result.php`


[1]: https://raw.githubusercontent.com/oplatacom/bitrix/master/settings.png