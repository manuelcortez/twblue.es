<!-- 
.. title: документация
.. slug: documentation
.. date: 2016-10-03 04:59:39 UTC-05:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
-->

Внимание! {#_2}
---------

Вы читаете документацию к программе, которая еще находится в разработке.
Цель данной инструкции - разъяснить некоторые подробности работы с
данной программой. Помните, что, поскольку приложение активно
развивается, фрагменты данного руководства пользователя могут быть
изменены в ближайшем будущем, поэтому советуем переодически проверять
его, чтобы не пропустить важную информацию.

Если вы хотите посмотреть какие изменения произошли с предыдущей версии,
[читайте список обновлений здесь.](changes.html)

Введение {#_3}
--------

TWBlue - это программа, делающая работу с твиттером простой и быстрой,
используя минимум ресурсов. При помощи TWBlue можно выполнять следующие
действия:

-   Создавать твиты, отвечать, ретвитить и удалять твиты.
-   Добавлять твиты в Избранное и удалять из него,
-   Отправлять и удалять личные сообщения,
-   Просматривать списки читающих вас и читаемых вами,
-   читать, переставать читать, блокировать пользователей и сообщать о
    спаме,
-   открывать ленты пользователей, чтобы просматривать их твиты
    отдельно,
-   Открывать ссылки из твитов или личных сообщений,
-   Воспроизводить различные типы аудиофайлов из интернета,
-   И другое.

Использование {#_4}
-------------

Твиттер - это социальная сеть или инструмент для микро-блоггинга,
позволяющий создавать короткие, не более 140 символов заметки. Твиттер -
это возможность общаться с друзьями, членами семьи и коллегами,
обмениваясь быстрыми, короткими сообщениями, и оставаясь всегда на
связи. Обновления можно ограничить только для круга друзей или, как
выбрано по умолчанию, делать их доступными всем.

Вы можете следить за обновлениями ваших друзей, родных и коллег (читать
их), а они, в свою очередь, могут видеть ваши обновления (читать вас).
Короткие сообщения называются твитами. Твиты публикуются ввашем профиле
или блоге и доступны для поиска в Твиттере.

Для того, чтобы пользоваться TWBlue, вам нужно создать учетную запись на
сайте Твиттера. Процесс создания учетной записи в Твиттере очень
доступен. При регистрации вам нужно будет выбрать имя пользователя. Это
нужно для двух целей. При помощи этого имени люди смогут с вами
общаться, но, что еще важнее, имя пользователя и пароль понадобятся вам
для подключения TWBlue к вашей учетной записи. Придумайте имя, которое
будет легко запомнить не только вам самим, но и тем, кто, как вы
надеетесь, будет вас читать.

Мы начнем, исходя из того, что у вас уже есть учетная запись в Твиттере
с соответствующими именем пользователя и паролем.

### Авторизация приложения {#_5}

Прежде всего, для того, чтобы программа могла получить доступ к вашей
учетной записи в Твиттере и работать от вашего имени, ее нужно
авторизовать. Процесс авторизации довольно прост, и такие данные, как
ваш пароль, нигде не сохраняются. Для того, чтобы авторизовать
приложение, нужно всего лишь запустить основной исполняемый файл,
TWBlue.exe (на некоторых компьютерах он может называться просто TWBlue,
если в проводнике Windows не включено отображение расширений). Для
удобства мы советуем создать на рабочем столе ярлык, указывающий на этот
файл.

Вы можете одновременно входить под несколькими учетными записями. Каждая
учетная запись (аккаунт), в программе называется "сессией". Если вы
впервые запустили TWBlue, и ни одной сессии не существует, появится
менеджер сессий. В этом диалоговом окне можно авторизовать сколько
угодно учетных записей. Если вы нажмете клавишу Таб, дойдете до кнопки
"Добавить аккаунт", и активируете ее Пробелом, откроется диалоговое
окно, предлагающее открыть ваш интернет браузер по умолчанию для того,
чтобы авторизовать приложение, и вам будет предложено продолжить.
Активируйте кнопку "Да" нажав букву "Y" и процесс запустится.

В браузере, выбранном у вас по умолчанию, откроется сайт твиттера с
запросом об авторизации. Если вы еще не вошли под своей учетной записью,
введите имя пользователя и пароль в соответствующие поля редактирования,
выберите кнопку Авторизовать и нажмите ее.

Как только ваша учетная запись будет авторизована, сайт Твиттера
перенаправит вас на страницу, сообщающую о том, что авторизация TWBlue
прошла успешно. Теперь вы можете закрыть страницу, нажав Альт + F4 и
вернуться в менеджер сессий. В списке сессий появится новый элемент под
временным названием "Авторизованный аккаунт X", где x - это номер.
Название сессии изменится сразу же, как только вы ее откроете.

Чтобы начать работу с TWBlue, нажмите кнопку ОК в диалоге менеджера
сессий. По умолчанию, программа запускает все созданные сессии
автоматически, однако, это можно изменить.

Если все прошло хорошо, начнут проигрываться звуки, означающие, что ваши
данные обновляются.

По окончании этого процесса, по умолчанию прозвучит еще один звук и
программа экранного доступа скажет "Готово" (это тоже можно
перенастроить).

Основные понятия {#_6}
----------------

Прежде чем приступить к описанию работы с TWBlue, разъясним некоторые
понятия, которые будут постоянно употребляться в данном руководстве
пользователя.

### Буфер {#_7}

Буфер - это обработанный приложением список элементов, относящихся к
данным, получаемым из Твиттера. Когда вы настраиваете в TWBlue новую
сессию и запускаете ее, создается много буферов. В каждом из них может
находиться несколько элементов, с которыми работает программа: твитов,
личных сообщений, пользователей, трендов или событий. В зависимости от
того, в каком буфере вы находитесь, вы можете выполнять определенные
действия с содержащимися в нем элементами.

Ниже дано описание каждого из буферов TWBlue и типа элементов, с которым
он работает.

-   Ваша лента: здесь показаны все твиты главной ленты. Это твиты
    пользователей, которых вы читаете.
-   Упоминания: Если пользователь, независимо оттого, читаете вы его или
    нет, упомянул вас в Твиттере, это отобразится в данном списке.
-   Личные сообщения: здесь находятся личные сообщения, которыми вы
    обмениваетесь с читающими вас пользователями, либо сообщения от
    других пользователей, если вы разрешили прием личных сообщений от
    кого угодно(это настраивается на сайте Твиттера). В этом списке
    отображаются только полученные сообщения.
-   Отправленные личные сообщения: в этом буфере отображаются все личные
    сообщения, отправленные с вашей учетной записи.
-   Отправленные твиты: здесь показаны все твиты, отправленные с вашей
    учетной записи.
-   Понравившиеся: здесь вы увидите все твиты, которые вы отметили
    как понравившиеся.
-   Читающие: когда пользователь начнет вас читать, вы сможете увидеть
    его в этом буфере, где также будет частично отображена информация о
    его учетной записи.
-   Читаемые: то же, что и предыдущий буфер, но это пользователи,
    которых читаете вы.
-   Ленты пользователей: это буферы, которые можно
    создавать дополнительно. В них содержатся только твиты от
    конкретных пользователей. Они нужны для того, чтобы просматривать
    твиты от определенного человека, не пролистывая приэтом всю
    главную ленту. Таких буферов можно создавать сколько угодно.
-   События: событие - это то, что происходит в Твиттере, например,
    когда кто-то начинает вас читать, добавляет ваш твит в Избранное или
    удаляет его; когда вы подписываетесь на список. Подобных событий
    много, но в буфере программы отображаются только самые основные,
    чтобы вы могли отслеживать все, происходящее с вашей
    учетной записью.
-   Списки: список похож на пользовательскую ленту, с той разницей, что
    сюда можно добавлять твиты от нескольких пользователей.
-   Поиск: в этом буфере находятся результаты поиска.
-   Понравившиеся ленты: вы можете создать буфер, в котором будут
    содержаться твиты, отмеченные определённым пользователем
    как понравившиеся.
-   Трендовые (популярные) темы: в трендовом буфере отображаются десять
    терминов, наиболее часто используемых в определенном регионе.
    Регионом может быть как страна, так и город. Тренды обновляются
    каждые пять минут.

Если в твите содержится ссылка, ее можно открыть, нажав клавишу Ввод в
окне программы, либо нажав сочетание клавиш Контрол + Виндовс + Ввод в
невидимом интерфейсе. Если присутствует аудио, его можно прослушать,
нажав Контрол + Ввод или Контрол + Виндовс, + Альт, + Ввод
соответственно. Если в твите присутствует хэштег (метка) \#audio, TWBlue
проиграет звук, но аудио может содержаться и в твитах, не имеющих этой
метки. Наконец, если в твите содержится информация о местоположении,
нажмите Контрол + Виндовс + G в невидимом интерфейсе, чтобы ее
прочитать.

### Поля ввода имени пользователя {#_8}

В эти поля можно вводить имя пользователя Твиттера без знака Собачка
(эт). Их можно увидеть в диалоговых окнах отправки личных сообщений и
меню действий с пользователем. Об этих диалоговых окнах мы поговорим
позже. Первоначальное значение этих полей зависит от того, где они были
открыты. Такое поле ввода заполняется именем пользователя, написавшего
твит, находящийся в фокусе (если он открыт из главной ленты, ленты
отправленных твитов, ленты пользователя или из списка); именем
отправителя личного сообщения (в буферах полученных и отправленных
личных сообщений), или, если в фокусе находится пользователь (в буферах
Читающие и Читаемые. Если одно из этих диалоговых окон открыто из твита,
и, если в нем упомянуто несколько пользователей, перемещаться по ним
можно клавишами стрелок. Либо, вы можете сами ввести имя пользователя

Интерфейс программы {#_9}
-------------------

### Графический пользовательский интерфейс {#_10}

Графический интерфейс TWBlue представляет собой окно, содержащее:

-   строку меню, состоящую из пяти элементов (приложение, твит,
    пользователь, буфер и помощь);
-   Дерево просмотра,
-   Список просмотра элементов,
-   Четыре кнопки в большинстве диалогов: Твит, Ретвит, Ответ и
    Личное сообщение.

Действия, доступные для каждого элемента будут описаны позже.

Короче говоря, графический интерфейс состоит из двух основных
компонентов. Это элементы управления, которые вы обнаружите, нажимая
клавишу Таб, и различные элементы, расположенные в строке меню.

#### Кнопки приложения {#_11}

-   Твит: этой кнопкой открывается диалоговое окно для написания твита.
    Длина сообщения не должна превышать 140 символов. Если вы привысите
    лимит, прозвучит предупреждающий сигнал. Обратите внимание, что
    количество символов отображается в строке заголовка. Для изменения
    длины сообщения можно использовать кнопки сократить или
    развернуть ссылку. Выбрав одну из кнопок, доступных в этом
    диалоговом окне, вы можете загрузить фото, проверить орфографию,
    добавить аудио или перевести ваше сообщение. Кроме того, вы можете
    активировать автозаполнение имен пользователей, нажав Альт + A, или
    отвечающую за это кнопку, если у вас создана база
    данных пользователей. Чтобы отправить твит, нажмите Ввод. Если все
    пройдет хорошо, вы услышите звук, оповещающий об отправке. В
    противном случае, программа экранного доступа произнесет сообщение
    об ошибке, описывающее проблему, на английском языке.
-   Ретвит: При помощи этой кнопки выполняется ретвит сообщения, которое
    вы сейчас читаете. После нажатия этой кнопки, если соответствующая
    настройка не была изменена, вам будет предложено добавить
    комментарий, либо отправить как есть. Если вы выберите добавление
    комментария, и если комментарий вместе с исходным твитом превысят
    140 символов, вам будет предложено отправить сообщение как
    упоминание оригинального пользователя со ссылкой на исходный твит.
-   Ответ: Когда вы просматриваете твит, вы можете ответить написавшему
    его пользователю, нажав эту кнопку. Откроется диалог, подобный окну
    создания твита, но с уже заполненным именем пользователя (например,
    @user), и вам останется только написать свое сообщение. Если твит
    относится к нескольким пользователям, можно нажать Шифт-Таб и
    отметить флажок Упомянуть всех. Если вы находитесь в списке друзей
    или читателей, этот флажок будет называться Упомянуть.
-   Личное сообщение: тоже, что и отправка твита, но это приватное
    сообщение, которое может быть просмотрено только тем пользователем,
    которому вы его отправляете. Чтобы посмотреть получателя,
    нажмите Шифт-таб. Если в сообщении, которое вы читаете, упомянуто
    несколько пользователей, стрелками вверх и вниз можно выбрать
    получателя сообщения, или ввести имя вручную, без знака собаки.

Учтите, что кнопки будут отображаться в зависимости от того, какие
действия доступны в просматриваемом списке. Например, в главной ленте, в
упоминаниях, Отправленных, избранном и лентах пользователей вы увидите
четыре кнопки, в то время как в списке личных сообщений будут
отображаться только кнопки Личное сообщение и Твит, а в списках друзей и
читающих будут доступны кнопки Личное сообщение,Твит и Упомянуть.

#### Меню {#_12}

Визуально, в верхней части главного окна программы, находится строка
меню, в котором представлены многие из функций, описанных в предыдущем
разделе, а также некоторые другие элементы. Чтобы войти в строку меню,
нажмите клавишу Альт. Откроется список из пяти меню: Приложение, Твит,
Пользователь, Буфер и Помощь. В данном разделе описаны элементы каждого
из них.

##### Меню Приложение {#_13}

-   Управление аккаунтами: открывает окно со всеми сессиями,
    настроенными в TWBlue, в котором можно добавлять новые сессии и и
    удалять уже существующие.
-   Обновить профиль: открывает диалог, в котором можно обновить
    собственную информацию в твиттере: имя, местоположение, сайт
    и биографию. Если вы уже вводили эти данные, поля будут уже
    заполнены введенным текстом. Также, в свой профиль можно
    загрузить фото.
-   Скрыть окно: отключает графический интерфейс. Подробнее читайте об
    этом в разделах, посвященных невидимому интерфейсу.
-   Поиск: показывает диалоговое окно, в котором можно искать твиты или
    пользователей Твиттера.
-   Менеджер списков: В этом диалоговом окне можно управлять своими
    списками Твиттера. Для того, чтобы ими пользоваться, их сначала
    нужно создать. Здесь их можно просматривать, редактировать,
    создавать, удалять, или, опционально, открывать их в буферах,
    подобно лентам пользователей.
-   Редактировать горячие клавиши: этот пункт меню открывает диалог, в
    котором можно просматривать и редактировать сочетания клавиш,
    используемые в невидимом интерфейсе.
-   Настройки учетной записи: открывает диалоговое окно, позволяющее
    изменять параметры текущей учетной записи.
-   Основные настройки: открывает диалог, позволяющий изменять параметры
    для всего приложения.
-   Выход: спрашивает хотите ли вы выйти из программы. Если ответ
    положительный, закрывает приложение. Если вы не хотите, чтобы
    выдавался запрос на подтверждение выхода, снимите флажок в
    основных настройках.

##### Меню Твит {#_14}

-   в Начале находятся элементы: Твит, Ответить и Ретвитнуть, идентичные
    кнопкам с теми же именами.
-   Нравится: отмечает просматриваемый вами твит как понравившийся.
-   Не нравится: удаляет твит из списка понравившихся вам твитов, но не
    из твиттера.
-   Показать твит: открывает диалоговое окно, в котором можно прочесть
    твит, личное сообщение, имя друга или читателя, находящееся
    в фокусе. Текст можно читать клавишами стрелок. Этот диалог похож на
    окно отправки твита, но без возможности отправки, прикрепления
    вложений и автозаполнения. Однако, здесь указано число ретвитов и
    отметок Нравится. Если вы находитесь в списке читателей или друзей,
    будут доступны только поле для чтения информации, находящейся в
    фокусе, и кнопка Закрыть.
-   Просмотреть адрес: если в выбранном твите указано местоположение,
    TWBlue может отобразить диалоговое окно, в котором возможно
    просмотреть адрес твита. Этот адрес получается путем отправки
    географических координат твита в Карты Гугл.
-   Просмотр беседы: если в фокусе находится твит с упоминанием,
    откроется буфер, в котором можно просмотреть беседу полностью.
-   Удалить: удаляет находящийся в фокусе твит или личное сообщение из
    Твиттера и ваших списков. Имейте в виду, что Твиттер позволяет
    удалять только те твиты, которые вы сами написали.

##### Меню Пользователь {#_15}

-   Действия: открывает диалог, в котором можно взаимодействовать
    с пользователем. Это диалоговое окно относится к пользователю,
    написавшему твит или личное сообщение, находящееся в фокусе, или к
    пользователю выбранному в буфере друзей или читателей. Имя можно
    изменить, либо оставить как есть, и выполнить следующие действия:
    -   Начать читать: начать читать пользователя. Это значит, что вы
        будете видеть его / ее твиты в своей главной ленте, и если он /
        она также читает вас, вы сможете обмениваться
        личными сообщениями. Вы также можете отправлять друг другу
        личные сообщения, если у вас в настройках выбрано Разрешить
        личные сообщения от кого угодно.
    -   Перестать читать: перестать читать пользователя, т.е., больше не
        видеть его / ее твиты в своей главной ленте, отключить обмен
        личными сообщениями, если только не выбрана опция приема личных
        сообщений от кого угодно.
    -   Отключить: TWBlue не будет отображать в вашей главной ленте
        твиты пользователя; вы также не будете видеть упоминаний
        этого человека. Но вы сможете обмениваться личными сообщениями.
        О том, что пользователь отключен, он уведомлен не будет.
    -   Включить: эта опция позволяет TWBlue снова отображать твиты и
        упоминания пользователя.
    -   Заблокировать: блокирует пользователя. Это приводит к тому, что
        пользователь принудительно перестает вас читать.
    -   Разблокировать: снимает блокировку с пользователя.
    -   Сообщить о спаме: в Твиттер отправляется сообщение о том, что
        этот пользователь практикует запрещенные в социальных
        сетях вещи.
    -   Игнорировать твиты, которые отправляются из этого клиента:
        добавляет клиент, из которого был отправлен твит, находящийся в
        фокусе, в список игнорируемых.
-   Показать ленту: позволяет открыть ленту пользователя, выбрав его из
    списка в диалоговом окне. Для ее создания нажмите Ввод. Если эта
    опция применяется к пользователю, у которого еще нет твитов,
    операция не будет выполнена. Если вы пытаетесь создать уже
    существующую ленту, программа предупредит об этом и повторно лента
    создана не будет.
-   Личное сообщение: та же функция, что и у кнопки.
-   Добавить в список: чтобы видеть твиты человека в одном или
    нескольких из своих списков, сначала его нужно добавить. В
    диалоговом окне, открывшемся после выбора пользователя, вам будет
    предложено выбрать список, в который его нужно добавить. После
    этого, в списке появится новый член и будут отображаться его твиты.
-   Удалить из списка: позволяет удалить пользователя из списка.
-   Просмотр списков: показывает списки, созданные
    указанным пользователем.
-   Показать профиль пользователя: открывает диалоговое окно с профилем
    указанного пользователя.
-   Просмотреть Понравившиеся: открывает буфер, в котором можно увидеть
    твиты, отмеченные указанным пользователем как понравившиеся.

##### Меню Буфер {#_16}

-   Новый буфер для трендов: открывает буфер для самых популярных тем в
    мире, стране или городе. Вы сможете выбрать из списка показывать ли
    популярные темы по стране, городу или со всего мира (эта опция
    находится в списке Город), а затем выбрать нужный элемент. Буфер для
    трендов будет создан как только в диалоговом окне будет активирована
    кнопка Ок. Помните, этот буфер будет обновляться каждые пять минут.
-   Загрузить предыдущие элементы: позволяет загрузить больше элементов
    в указанный буфер.
-   Отключить: отключает звук и уведомления для конкретного буфера, так
    что вы не будете слышать, когда приходят новые твиты.
-   Авточтение: когда включено, программа экранного доступа или голос
    SAPI 5 (если активен) будет читать текст входящих твитов. Обратите
    внимание, что, если приходит много твитов, программа может слишком
    много болтать.
-   Очистить буфер: удаляет все элементы из буфера.
-   Закрыть и удалить: удаляет список, в котором вы находитесь.

##### Меню Помощь {#_17}

-   Документация: открывает этот файл, в котором можно прочесть
    некоторые полезные вещи о программе.
-   Гид по звукам: открывает диалоговое окно, в котором можно
    ознакомиться с различными звуками этой программы.
-   Что нового в этой версии?: открывает документ со списком изменений,
    начиная с этой версии и старше.
-   Проверить обновления: каждый раз при запуске программы выполняется
    проверка на наличие новых версий. Если доступно обновление, вам
    будет предложено его загрузить. Если вы согласитесь, будет
    произведено обновление. По окончании, TWBlue перезапустится. Этот
    пункт меню позволяет проверить на наличие обновлений без
    перезапуска программы.
-   Сообщить об ошибке: открывает диалоговое окно, позволяющее, заполнив
    несколько полей, сообщить о неполадке. Нажатием клавиши Ввод отчет
    будет отправлен. Если этого не произойдет, программа
    покажет предупреждение.
-   Сайт TWBlue: посетить нашу [домашнюю страницу](http://twblue.es) ,
    где можно найти всю информацию о программе и загрузить TWBlue, а
    также стать членом сообщества.
-   О TWBlue: показывает данные о программе.

### Невидимый интерфейс {#_18}

Невидимый интерфейс, как следует из названия, не имеет графического окна
и работает напрямую с программами экранного доступа, такими как JAWS для
Windows, NVDA и System Access. По умолчанию этот интерфейс отключен, но
его можно включить нажав Контрол + M. Он работает подобно TheQube и
Chicken Nugget. Горячие клавиши также похожи на те, что используются в
этих клиентах. Кроме того, в программе имеется возможность
редактирования клавиатурных команд, которую можно выбрать в Основных
настройках. По умолчанию, с горячими клавишами этого интерфейса
невозможно работать в графическом окне, но этот параметр можно изменить
в Основных настройках.

В следующем разделе представлен список клавиатурных команд для обоих
интерфейсов. Имейте в виду, что мы говорим только о горячих клавишах,
выбранных по умолчанию.

Список горячих клавиш {#_19}
---------------------

### Горячие клавиши для графического интерфейса {#_20}

-   Ввод: открыть ссылку.
-   Контрол + Ввод: воспроизвести аудио.
-   Контрол + M: скрыть графический интерфейс.
-   Контрол + N: создать новый твит.
-   Контрол + R: ответить / упомянуть.
-   Контрол + Шифт + R: ретвитнуть.
-   Контрол + D: отправить личное сообщение.
-   Контрол + F: отметить твит как понравившийся.
-   Контрол + Шифт + F: удалить твит из списка понравившихся.
-   Контрол + S: открыть диалог действий с пользователем.
-   Контрол + Шифт + V: показать твит.
-   Контрол + Q: закрыть программу.
-   Контрол + I: открыть ленту пользователя.
-   Контрол + Шифт+ I: закрыть и удалить буфер.
-   F5: увеличить громкость на 5%.
-   F6: уменьшить громкость на 5%.
-   Контрол + P: редактировать свой профиль.
-   Контрол + Дэлит: удалить твит или личное сообщение.
-   Контрол + Шифт + Дэлит: очистить текущий буфер.

### Горячие клавиши для невидимого интерфейса {#_21}

-   Контрол + Windows + Стрелка вверх: перемещает к предыдущему элементу
    в буфере.
-   Контрол + Windows + Стрелка вниз: перемещает к следующему элементу
    в буфере.
-   Контрол + Windows + Стрелка влево: перейти к предыдущему буферу.
-   Контрол + Windows + Стрелка вправо: перейти к следующему буферу.
-   Контрол + Windows + Шифт + Влево: перейти к предыдущей сессии.
-   Контрол + Windows + Шифт + Вправо: перейти к следующей сессии.
-   Контрол + Windows + C: просмотреть беседу.
-   Контрол + Windows + Ввод: Открыть ссылку.
-   Контрол + Windows + Альт + Ввод: воспроизвести аудио.
-   Контрол + Windows + M: показать или скрыть графический интерфейс.
-   Контрол + Windows + N: новый твит.
-   Контрол + Windows + R: ответить / упомянуть.
-   Контрол + Windows + Шифт + R: ретвитнуть.
-   Контрол + Windows + D: отправить личное сообщение.
-   Windows+ Альт + F: отметить твит как понравившийся.
-   Альт + Windows + Шифт + F: удалить из списка понравившихся.
-   Контрол + Windows + S: открыть диалог действий с пользователем.
-   Контрол + Windows + Альт + N: посмотреть информацию о пользователе.
-   Контрол + Windows + V: показать твит.
-   Контрол + Windows + F4: закрыть TWBlue.
-   Контрол + Windows + I: открыть ленту пользователя.
-   Контрол + Windows + Шифт + I: закрыть и удалить буфер.
-   Контрол + Windows + Альт + вверх: увеличить громкость на 5%.
-   Контрол + Windows + Альт + Вниз: уменьшить громкость на 5%.
-   Контрол + Windows + Хоум: перейти к первому элементу
    текущего буфера.
-   Контрол + Windows + Энд: перейти к последнему элементу
    текущего буфера.
-   Контрол + Windows + Страница вверх: перейти на 20элементов вверх в
    текущем буфере.
-   Контрол + Windows + Страница вниз: перейти на 20 элементов вниз в
    текущем буфере.
-   Windows + Альт + P: редактировать профиль.
-   Контрол + Windows + Дэлит: удалить твит или личное сообщение.
-   Контрол + Windows + Шифт + Дэлит: очистить текущий буфер.
-   Контрол + Windows + Пробел: повторить последний элемент.
-   Контрол + Windows + Шифт + C: скопировать в буфер обмена.
-   Контрол + Windows+ A: добавить пользователя в список.
-   Контрол + Windows + Шифт + A: удалить пользователя из списка.
-   Контрол + Windows + Шифт + M: отключить / включить звуки для
    текущего буфера.
-   Windows + Альт + M: Отключить / включить звуки для текущей сессии.
-   Контрол + Windows + E: переключить авточтение входящих твитов в
    текущем буфере.
-   Контрол + Windows + -: искать в Твиттере.
-   Контрол + Windows + K: показать редактор горячих клавиш.
-   Контрол + Windows + L: показать списки указанного пользователя.
-   Windows + Альт + Страница вверх: загрузить предыдущие элементы для
    текущего буфера.
-   Контрол + Windows + G: получить местоположение.
-   Контрол + Windows + Шифт + G: показать местоположение для твита
    в диалоге.
-   Контрол + Windows + T: создать буфер для трендов.
-   Контрол + Windows + {: найти фразу в текущем буфере.

Настройка {#_22}
---------

Как описано выше, в данном приложении имеется два диалога настроек:
диалог основных настроек и диалог настройки учетной записи.

### Диалог настройки учетной записи {#_23}

#### Вкладка Общие {#_24}

-   Настройки автозаполнения: позволяют сконфигурировать базу данных
    для автозаполнения. Можно добавлять пользователей вручную, либо
    позволить TWBlue добавлять ваших читателей, друзей, или и тех, и
    других
-   Относительное время: позволяет выбрать будет ли приложение
    рассчитывать время отправки твита или личного сообщения, основываясь
    на текущем времени, либо просто называть время получения
    или отправки.
-   Количество вызовов API: позволяет настроить число обращений API,
    производимых программой к Твитттеру
-   Элементов при каждом вызове API: позволяет задать число твитов,
    получаемых при каждом API обращении (по умолчанию и максимум 200).
-   Отображение твитов: позволяет настроить расположение твитов в
    обратном порядке, т.е., когда более старые твиты находятся в конце,
    а новые, в начале списка.
-   Стиль ретвита: позволяет настроить опцию ретвита: можно выбрать
    между ретвитом с комментарием, ретвитом без комментария или ретвитом
    с запросом.
-   Количество элементов для каждого буфера в Кэше: позволяет указать
    сколько твитов TWBlue будет кэшировать в базе данных. Можно ввести
    любое значение, 0 для кэширования всех, оставить поле пустым для
    отключения кэширования.

#### Вкладка Буферы {#_25}

На этой вкладке представлен список всех созданных вами буферов, кроме
Поиска, лент, Избранного и списков. Их можно показывать, скрывать и
перемещать.

#### Вкладка Игнорируемые клиенты {#_26}

На этой вкладке можно добавлять и удалять клиенты, которые будут
игнорироваться программой.

#### Вкладка Звук {#_27}

На этой вкладке можно настроить громкость звука, выбрать устройство
ввода и вывода и указать звуковой пакет, который будет использоваться
программой.

#### Вкладка Сервис аудио {#_28}

На этой вкладке вы можете ввести свой ключ для приложения SndUp (если
таковой у вас есть), чтобы загружать на SndUp аудио из вашей учетной
записи. Обратите внимание, что если данные введены не будут, загрузка
будет происходить анонимно.

### Основные настройки {#_29}

В этом диалоговом окне можно настроить некоторые параметры, влияющие на
работу приложения в целом.

#### Вкладка Общие {#_30}

-   Язык: здесь можно выбрать язык программы. В настоящий момент
    поддерживаются Арабский,Каталанский, немецкий, английский,испанский,
    баскский, финский, французский, Галисийский, хорватский, венгерский,
    итальянский, польский, португальский, русский и турецкий.
-   Показывать диалог перед выходом из TWBlue: этот флажок позволяет
    выбрать будет ли программа перед закрытием
    запрашивать подтверждение.
-   Воспроизводить звук при запуске TWBlue: этот флажок позволяет
    выбрать будет ли приложение проигрывать звук после того, как
    загрузятся все буферы.
-   Произносить приветствие при запуске TWBlue: то же, что и предыдущий
    параметр, но определяет будет ли программа экранного доступа
    говорить "готово".
-   Использовать горячие клавиши невидимого интерфейса в окне программы:
    поскольку невидимый и графический интерфейсы имеют собственные
    клавиатурные команды, возможно, вам будет удобнее использовать
    сочетания клавиш для невидимого интерфейса все время. Если выбран
    этот параметр, в графическом интерфейсе будут доступны горячие
    клавиши невидимого интерфейса.
-   Активировать SAPI5, когда ни один скринридер не запущен: этот флажок
    позволяет активировать синтезатор речи SAPI 5, когда не запущена ни
    одна другая программа экранного доступа.
-   Скрывать окно при запуске: позволяет выбрать будет ли TWBlue
    запускаться с графическим или невидимым интерфейсом.
-   Клавиатурные команды: позволяет изменить список клавиатурных команд,
    используемых программой в невидимом интерфейсе. Доступны сочетания
    клавиш по умолчанию, команды для Qwitter, Windows 10 и
    Chicken Nugget.

#### Вкладка Прокси {#_31}

На этой вкладке можно настроить работу TWBlue через прокси сервер,
заполнив отображаемые поля (сервер, порт, имя пользователя и пароль).

Лицензия, исходный код и пожертвования {#_32}
--------------------------------------

Tw Blue - это бесплатная программа, распространяемая по лицензии GNU
GPL, начиная с версии 2 и выше (на ваше усмотрение. Просмотреть текст
лицензии на английском языке можно в файле license.txt, или он-лайн по
ссылке <http://www.gnu.org/licenses/old-licenses/gpl-2.0.html>.

Исходный код программы доступен на GitHub, на странице
<https://www.github.com/manuelcortez/twblue>.

Если вы хотите внести материальное пожертвование для проекта,сделать это
можно на <http://twblue.es/?q=node/3&language=en>. Спасибо за вашу
поддержку!

Контакт {#_33}
-------

Если, после прочтения этого документа, у вас все еще остались вопросы,
если вы хотите каким-либо образом сотрудничать с проектом, или, если вы
просто хотите связаться с разработчиком этого приложения, начните читать
в Твиттере пользователя [@tw\_blue2](https://twitter.com/tw_blue2) или
[@manuelcortez00.](https://twitter.com/manuelcortez00). Вы также можете
посетить [наш сайт](http://twblue.es)

Благодарности {#_34}
-------------

Разрабатывают и поддерживают TWBlue [Мануэль
Кортес](https://twitter.com/manuelcortez00) и [Хосе Мануэль
Деликадо](https://twitter.com/jmdaweb). Поддержку и спонсорскую помощь
оказывает [Technow S. L.](https://twitter.com/technow)

Также хотим выразить благодарность переводчикам TWBlue, сделавшим
возможным распространение приложения.

-   Английский: [Manuel Cortéz](https://twitter.com/manuelcortez00).
-   Арабский : [Mohammed Al Shara](https://twitter.com/mohammed0204).
-   Каталанский: [Francisco Torres](https://twitter.com/ftgalleg)
-   Испанский: [Manuel Cortéz](https://twitter.com/manuelcortez00).
-   Баскский: [Sukil Etxenike](https://twitter.com/sukil2011).
-   Финский: [Jani Kinnunen](https://twitter.com/jani_kinnunen).
-   Французский: [Rémi Ruiz](https://twitter.com/blindhelp38).
-   Галисийский: [Juan Buño](https://twitter.com/Quetzatl_).
-   Немецкий: [Steffen Schultz](https://twitter.com/schulle4u).
-   Хорватский: [Zvonimir Stanečić](https://twitter.com/zvonimirek222).
-   Венгерский: Robert Osztolykan.
-   Итальянский: [Christian Leo Mameli](https://twitter.com/llajta2012).
-   Японский: [Riku](https://twitter.com/riku_sub001)
-   Польский: [Pawel Masarczyk.](https://twitter.com/Piciok)
-   Португальский: Odenilton Júnior Santos.
-   Румынский: [Florian Ionașcu](https://twitter.com/7ro) and [Răzvan
    Ciule](https://twitter.com/pilgrim89)
-   Русский: [Наталья Хедлунд](https://twitter.com/Lifestar_n).
-   Сербский: [Aleksandar Đurić](https://twitter.com/sokodtreshnje)
-   Турецкий: [Burak Yüksek](https://twitter.com/burakyuksek).

Также огромная благодарность всем, кто работал над документацией.
Изначально [Мануэль Кортес](https://twitter.com/manuelcortez00) создал
документацию на испанском языке, затем она была переведена на английский
пользователями [Bryner Villalobos](https://twitter.com/Bry_StarkCR),
[Robert Spangler](https://twitter.com/glasscity1837), [Sussan
Rey](https://twitter.com/sussanrey17), [Anibal
Hernandez](https://twitter.com/anibalmetal), и [Holly
Scott-Gardner](https://twitter.com/holly1994). Текст был обновлен
пользователем [Sukil Etxenike](https://twitter.com/sukil2011), ценные
исправления внесли [Brian Hartgen](https://twitter.com/brianhartgen) и
[Bill Dengler](https://twitter.com/codeofdusk).

------------------------------------------------------------------------

Авторское право © 2013-2016. Manuel Cortéz
