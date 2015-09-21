Russian RAPIRA language pack for SuiteCRM
=========================================

+ Здесь находится самая актуальная версия языковых файлов для [SuiteCRM][suitecrm] (форка безвременно почившего [SugarCRM CE] [sugar]), с учётом последних дополнений и исправлений
+ Обновление языковых файлов проще всего сделать через установку языкового пакета ([ссылка на последний актуальный перевод для SuiteCRM 7.3][langpack]). Детально процесс установки/обновления русификации SuiteCRM описан ниже.
+ Обсуждение русификации SuiteCRM на [официальном форуме][forum]
+ Начинающие пользователи могут скачать ["Руководство пользователя и администратора"] [man], переведённое ранее для SugarCRM CE, но вполне подходящее и для знакомства с SuiteCRM.

------------------------------------------------

<b>Что нового в SuiteCRM 7.3</b>    (полная история изменений содержится в файле [HISTORY.TXT][history])

+ Добавлена возможность быстрой правки записей
  - Теперь правка записей доступна непосредственно при их просмотре, и в Форме просмотра, и в Форме списка: достаточно выполнить двойной клик мышкой на соответствующем поле
  - Включение/отключение возможности быстрой правки осуществляется в разделе "Настройка конфигурации" панели администратора
  - Настройка возможности быстрой правки <b>поля</b> записи осуществляется в Студии: отредактируйте свойства поля соответствующего модуля, изменив параметр "Быстрая правка"
+ Добавлена поддержка уведомлений браузера (работает в большинстве современных браузеров, поддерживающих HTML5 Desktop Notifications API)
    - Доступность данной функции зависит от версии браузера, включение осуществляется на странице настроек текущего пользователя - закладка "Дополнительно"
    - Получение уведомлений о Звонках и Встречах теперь доступно в виде всплывающего окна на Рабочем столе
    - Отображение пропущенных уведомлений в правой верхней части окна системы 
+ Улучшено отображение темы SuiteR на мобильных устройствах с небольшой диагональю экрана
+ Добавлена возможность обновления Обращения непосредственно из Формы просмотра
+ Добавлены дополнительные операторы сравнения в условия выполнения Процессов
+ Добавлены дополнительные временнЫе интервалы в условия формирования Отчётов

------------------------------------------------

<b>Установка языкового пакета</b>

Все действия по установке дополнительных пакетов (не только языковых) производятся через панель администратора.

1. Входим в систему с правами администратора.
2. В правом верхнем меню выбираем пункт <b>Admin</b> (Администрирование) для входа в раздел администратора системы.
3. В разделе администратора выбираем <b>Module Loader</b> (Загрузчик модулей), далее следуем шагам, описанным в мастере.
4. После того, как мастер сообщит об успешной установке пакета, выходим из системы (Logout) и на странице ввода логина/пароля выбираем необходимый язык интерфейса системы.
5. Вновь входим в систему.

Если вы не выбрали русский язык в процессе установки системы, его можно указать позже в качестве языка по умолчанию. Для этого в панели администрирования в подразделе <b>Региональные настройки</b> выберите соответствующий языковой пакет (Admin->Locale Settings->Default Language).
[langpack]: https://github.com/likhobory/SuiteCRM7RU/blob/ver.7.3.0/rapira-suite_pack_russian-7.3.zip?raw=true
[suitecrm]: https://github.com/salesagility/SuiteCRM
[man]: https://github.com/likhobory/SuiteCRM7RU/blob/master/DOCS/RRAG_6.2.2.pdf?raw=true
[forum]: https://suitecrm.com/forum/international-language-support/59
[sugar]: https://ru.wikipedia.org/wiki/SugarCRM
[history]: https://github.com/likhobory/SuiteCRM7RU/blob/master/HISTORY.TXT

