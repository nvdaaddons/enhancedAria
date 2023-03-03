# Enhanced Aria #

* Автор: Jose Manuel Delicado
* Застарілий додаток: NVDA 2019.3 і новіші версії можуть читати статті в
  Інтернеті
* Сумісність з NVDA : 2017.4 до 2019.2
* Завантажити [стабільну версію][1]

Цей додаток дозволяє вам обрати, які орієнтири на WEB-сторінках має
промовляти NVDA.

Його функціонал дуже простий. Після встановлення відкрийте браузер і
заходьте до інтернету, як зазвичай. Типові орієнтири, які озвучуються у
Firefox і Chrome, також будуть видимими в Internet Explorer, тому ви зможете
натискати клавіші швидкої навігації для переміщення між ними, і переглянути
список усіх орієнтирів на сторінці після натискання NVDA+F7 у всіх
браузерах. Прочитайте посібник користувача NVDA для отримання додаткової
інформації.

The addon adds an extra landmark not included by default in NVDA, the
article (abbreviated in Braille as art).

## Діалог налаштувань

You can enable or disable landmarks by going to NVDA, preferences, Enhanced
Aria Settings or from the appropriate category in the NVDA options
dialog. The dialog has a checkbox for each landmark. If you disable a
landmark, you won't be able to jump to it pressing the d key when browsing a
webpage, and NVDA won't report it.

## Контактна інформація

This addon has been developed by Jose Manuel Delicado. If you want to
contact me, send an e-mail to jm.delicado@nvda.es, or open an issue on
GitHub at https://github.com/jmdaweb/enhancedAria

## Журнал змін

### Version 2.8

* Нові й оновлені переклади.
* Оновлено прапори сумісності з попередніми версіями NVDA.

### Version 2.7

* Оновлено прапори сумісності для попередніх версій NVDA.
* Нові й оновлені переклади.

### Version 2.6

* Оновлено прапори сумісності для попередніх версій NVDA. Ця версія сумісна
  лише з NVDA 2017.4 і вище.
* Нові й оновлені переклади.
* Тепер конфігурація автоматично застосовується після перемикання профілів
  NVDA і відновлення стандартних налаштувань.

### Version 2.5

* Оновлено прапори сумісності для попередніх версій NVDA.

### Version 2.4

* Тепер налаштування видаляються лише при видаленні додатка. Конфігурація
  більше не скидається при оновленні.
* Нові й оновлені переклади.

### Version 2.3

* Додано сумісність з попередніми версіями NVDA.
* Нові переклади.

### Version 2.2

* Виправлено фатальну помилку, коли використовувався брайлівський дисплей і
  було налаштовано повідомлення про статті.

### Version 2.1

* Поліпшення стабільності

### Версія 2.0

* Додано підтримку багатосторінкового діалогу з категоріями налаштувань
  NVDA, який доступний в NVDA 2018.2 і новіших версіях
* Added Python 3 compatibility
* Now guiHelper module is used to create the addon interface

### Версія 1.3

* Added configobj specification for addon settings

### Версія 1.2

* Bugs fixed

### Версія 1.1

* Fixed issues which prevented opening the addon settings dialog when
  reverting to NVDA saved configuration

[[!tag dev stable legacy]]

[1]: https://addons.nvda-project.org/files/get.php?file=earia
