[<img src="https://github.com/Atarity/Strata/raw/master/History/v0.3.jpg"/>](https://github.com/Atarity/Strata/raw/master/History/v0.3.jpg)

Я сделал эту раскладку чтобы исключить постоянную смену языков во время набора русских текстов использующих разметку [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). Теперь символы вроде **#, < >, [ ]** всегда на кончиках пальцев.

Подсвеченные в шпаргалке символы вводятся с зажатой клавишей <kbd>Alt Gr</kbd> (т.н. «правый альт»). Для ввода символов из верхней строки вместе с <kbd>Alt Gr</kbd> нужно зажать ещё и <kbd>Shift</kbd>. Например, сочетание <kbd>Alt Gr</kbd>+<kbd>3</kbd> даст **⅓**, а <kbd>Alt Gr</kbd>+<kbd>Shift</kbd>+<kbd>3</kbd> даст **#** — всё просто.

В архиве две раскладки — для русского и английского языков. Так же полная копия раскладки собрана для OS X. В качестве основного модификатора там можно использовать **любой** <kbd>Alt</kbd>.

[Скачать дистрибутив для Windows →](https://github.com/Atarity/Strata/releases/download/v0.3/Strata.Markdown.Layout.Installer.v03.zip)

[Скачать установщик для macOS →](https://github.com/Atarity/Strata/releases/download/v0.5.0/Strata.Markdown.050.dmg)


### FAQ
**При попытке ввести  некоторые символы через <kbd>Alt Gr</kbd> приложения ведут себя странно. Почему?**

>В Windows клавиша <kbd>Alt Gr</kbd> фактически является просто сочетанием <kbd>Alt</kbd>+<kbd>Ctrl</kbd>. Поэтому, если вы, например, пытаетесь вводить знак § в приложении, которые уже использует сочетание <kbd>Alt</kbd>+<kbd>Ctrl</kbd>+<kbd>G</kbd> для быстрого доступа к каким-то собственным функциям, то, скорее всего, это сочетание будет интерпретировано дважды: как горячая клавиша и как §. Если для вас это огромная проблема, существует [совсем замороченное решение](http://superuser.com/questions/592970/can-i-make-ctrlalt-not-act-like-altgr-on-windows).

**Как ставить ударение?**

>Кнопка с ударением относится к так называемым [мёртвым клавишам](https://ru.wikipedia.org/wiki/%D0%9C%D1%91%D1%80%D1%82%D0%B2%D1%8B%D0%B5_%D0%BA%D0%BB%D0%B0%D0%B2%D0%B8%D1%88%D0%B8) и работает особенным образом позволяя вносить модификацию почти в любой печатаемый символ. Использовать её проще всего так: введите символ над которым хотите увидеть ударе́ние и затем дважды нажмите <kbd>Alt Gr</kbd>+<kbd>Shift</kbd>+<kbd>/</kbd> .

**Как удалить системную английскую раскладку в macOS после установки Страты?**

>[Вот этот вариант работает](https://apple.stackexchange.com/questions/44921/how-to-remove-or-disable-a-default-keyboard-layout) начиная с MacOS Big Sur.

**Как переключать раскладку клавиатуры в macOS по нажатию Caps Lock?**

>Начиная с macOS Catalina Страта поддерживает нативное переключение через <kbd>Caps Lock</kbd> — разрешите его в настройках раскладки. Если этот вариант вам не подходит, всегда можно использовать утилиту Karabiner. Ещё есть [вот такой воркэраунд](https://apple.stackexchange.com/a/303773).

**Мне крайне необходима буква Ѣ и ∫ и обязательно 💩. Что делать?**

>Репозиторий состоит всего из четырёх файлов. Для Win это расширение .klc — конфиги для утилиты [Microsoft Keyboard Layout Creator](http://www.microsoft.com/en-us/download/details.aspx?id=22339). С её помощью вы можете самостоятельно изменить раскладку для Windows. Для OS X файлы с расширением .keylayout можно отредактировать утилитой [Ukelele](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=ukelele). Шлите pull request и оставляйте issue, если вам кажется, что сделали что-то важное.

*В качестве основы для Страты использовалась [типографская раскладка Ильи Бирмана](http://ilyabirman.ru/projects/typography-layout/).*
