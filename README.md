Задание
=======

Создать приложение для платформы Android, в интерфейсе которого присутствует единственная кнопка и TextView. При нажатии на кнопку, в TextView должен появится текст «Hello, world.

Заготовка приложения, которое необходимо доработать находится в репозитории GitHub по ссылке https://github.com/ITschoolKDF/HelloWolrdApp

Техническое задание
-------------------

### Интерфейс

Интерфейс приложения должен состоять из одной Activity. Корневым элементом интерфейса должен быть макет LinearLayout с вертикальным расположением дочерних элементов. Макет LinearLayout должен содержать элементы интерфейса, перечисленные в таблице 1.

Таблица 1. Перечень элементов интерфейса приложения

|||||||
|--- |--- |--- |--- |--- |--- |
|**№**|**View**|**id**|**Ширина**|**Высота**|**Другие свойства**|
||TextView|textView|Занимает всю ширину родительского элемента|Соответствует высоте содержимого элемента|Текстовая метка для отображения строки «Hello, world!». Текст должен храниться в текстовом ресурсе с именем hello|
||Button|showHello|Занимает всю ширину родительского элемента|Соответствует высоте содержимого элемента|Текст на кнопке должен быть «Показать приветствие». Текст должен храниться в текстовом ресурсе с именем show_hello|

Текст на кнопке должен быть «Показать приветствие». Текст должен храниться в текстовом ресурсе с именем show\_hello

Название приложения должно быть «Приветствие» (без кавычек).

В момент запуска приложения текстовое поля с id textView не должны содержать текст.

Приложение должно корректно обрабатывать изменение конфигурации устройства.

### Функционал

При нажатии на кнопку с id showHello, в текстовой метке с id textView должен появиться текст «Hello, world!».

#### Примеры интерфейса, удовлетворяющего техническому заданию

![Hello World Task Pic 1](https://user-images.githubusercontent.com/10827973/153540611-e9a8eb44-76da-4fd6-9d85-fccdf9b3edb2.png)
![Hello World Task Pic 2](https://user-images.githubusercontent.com/10827973/153540618-667d3f5f-d06c-4458-8e83-46a666b66bae.png)

Критерии оценивания и тесты
---------------------------

|||||
|--- |--- |--- |--- |
|**№**|**Название теста**|**Балл**|**Проверяемые элементы ТЗ**|
||**Группа 1**|||
|1|interfaceTest|1|Проверяет наличие элементов интерфейса и их атрибут id на соответствие техническому заданию|
|2|appName|1|Проверяет название приложения на соответствие техническому заданию|
|3|stringRes|1|Проверяет наличие строковых ресурсов на соответствие техническому заданию|
|4|emptyViewText|1|Проверяет соответствие начального состояния приложения техническому заданию|
||**Группа 2**|||
|5|changeConfigTest|1|Проверяет обработку приложением изменений конфигурации устройства|
||**Итого**|5||
