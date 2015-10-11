[<img src="https://habrastorage.org/files/695/c88/7ad/695c887ad04a461aa32e28fb5747fa70.jpg"/>](https://habrastorage.org/files/695/c88/7ad/695c887ad04a461aa32e28fb5747fa70.jpg)

Я сделал эту раскладку чтобы исключить постоянную смену языков во время набора русских текстов использующих разметку [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). Теперь символы вроде **#, < >, [ ]** всегда на кончиках пальцев.

Подсвеченные в шпаргалке символы вводятся с зажатой клавишей <kbd>Alt Gr</kbd> (т.н. «правый альт»). Для ввода символов из верхней строки вместе с <kbd>Alt Gr</kbd> нужно зажать ещё и <kbd>Shift</kbd>. Например, сочетание <kbd>Alt Gr</kbd>+<kbd>3</kbd> даст **#**, а <kbd>Alt Gr</kbd>+<kbd>Shift</kbd>+<kbd>3</kbd> даст **⅓** — всё просто. Для поддержания консистентности в архиве две раскладки — для русского и английского языков. Так же полная копия раскладки собрана для OS X. В качестве основного модификатора там можно использовать **любой** <kbd>Alt</kbd>.

[Скачать дистрибутив для Windows →](https://github.com/Atarity/Strata/releases/download/v0.2/Strata.Markdown.Layout.Installer.v02.zip)

[Скачать установщик для OS X →](https://github.com/Atarity/Strata/releases/download/v02/Strata.Markdown.Layout.v02.dmg)

### FAQ
**При попытке ввести кое-какие символы через <kbd>Alt Gr</kbd> некоторые приложения ведут себя странно. Почему?**

>На самом деле <kbd>Alt Gr</kbd> это не какая-то особенная кнопка и фактически в Windows является просто сочетанием клавиш <kbd>Alt</kbd>+<kbd>Ctrl</kbd>. Поэтому, если вы, например, пытаетесь вводить знак § в приложении, которые использует сочетание <kbd>Alt</kbd>+<kbd>Ctrl</kbd>+<kbd>G</kbd> для быстрого доступа к каким-то собственным функциям, то, скорее всего, это сочетание будет интерпретировано дважды: как горячая клавиша и как §. Если для вас это огромная проблема, существует [совсем замороченное решение](http://superuser.com/questions/592970/can-i-make-ctrlalt-not-act-like-altgr-on-windows).

**Как ставить ударение?**

>Кнопка с ударением неспроста имеет особый вид в шпаргалке. Она относится к так называемым [мёртвым клавишам](https://ru.wikipedia.org/wiki/%D0%9C%D1%91%D1%80%D1%82%D0%B2%D1%8B%D0%B5_%D0%BA%D0%BB%D0%B0%D0%B2%D0%B8%D1%88%D0%B8) и работает особенным образом позволяя вносить модификацию почти в любой печатаемый символ. Использовать её проще всего так: введите символ над которым хотите увидеть ударе́ние и затем дважды нажмите <kbd>Alt Gr</kbd>+<kbd>Shift</kbd>+<kbd>/</kbd> .

**Как мне удалить системную английскую раскладку в OS X после установки Страты?**

>В OS X это что-то типа защиты от дурака, которая не очень хорошо работает. Есть простой способ удалить системную раскладку: Из списка раскладок добавьте японскую раскладку (она там одна). Затем удалите системную английскую, а после удалите японскую.

**Мне крайне нобходима буква Ѣ и ∫ и обязательно 💩. Что делать?**

>Репозиторий состоит всего из четырёх файлов. Для Win это расширение .klc — конфиги для утилиты [Microsoft Keyboard Layout Creator](http://www.microsoft.com/en-us/download/details.aspx?id=22339). С её помощью вы можете самостоятельно изменить раскладку для Windows. Для OS X файлы с расширением .keylayout можно отредактировать утилитой [Ukelele](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=ukelele) Шлите пул-реквесты и оставляйте тикеты, если вам кажется, что вы сделали что-то важное.

*Эта раскладка основана на [Типографской Раскладке Ильи Бирмана](http://ilyabirman.ru/projects/typography-layout/). Правда «типографского» в ней почти ничего не осталось.)*
