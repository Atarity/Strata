## TO-DO

- [x] Пофиксить дельту
- [x] Вернуть sup 1
- [x] Вертикальную черту добавить
- [x] Выпилить многоточие (нет)
- [x] Выпилить обе i (на самом деле заменить на греческую Пи)
- [x] Переставить <kbd>@</kbd> <kbd>#</kbd> <kbd>$</kbd> в русской раскладке на <kbd>Shift</kbd>
- [x] Менять местами » → >
- [x] Жирную галку U+2714 на Y
- [x] Жирный крест U+2718 на N
- [x] Забыл продублировать  \` в русской раскладке. (Ставим на Ё, поднимаем тильду на шифт, а примерное равно переносим на М + шифт)
- [x] Вертикальную черту перенести на своё место (если возможно)
- [x] В русской раскладке Decimal separator (numpad) поставить точку, вместо заяпятой
- [x] Проверить квадратные и круглые [диакритики из 20D0](http://unicode-table.com/ru/blocks/combining-diacritical-marks-for-symbols/) (проверил. Работает так себе.)
- [x] Легенду под ISO/ANSI перерисовать? (нет)
- [x] Выяснить что не так с <kbd>Alt Gr</kbd>+<kbd>L</kbd> в Sublime
- [x] Исправить легенду под v0.3, добавить минимум одну OEM кнопку
- [x] Сделать релиз v0.3 для MacOS
- [ ] Нарисовать новые иконки для OSX под ретину и тёмный статусбар
- [ ] Фак расширить на OSX
- [x] <kbd>Alt Gr</kbd>+<kbd>M</kbd> починить для вебовых Google Docs
- [x] Совместимость в Atom и его плагинах проверить
- [ ] & переставить на шифт на "7"
- [ ] кавычки внутри «Э» поменять местами
- [x] поддержать ~ в русской раскладке для ANSI (keycode 50) для Mac
- [ ] поддержать ~ в русской раскладке для ANSI (keycode 50) для Windows
- [ ] нарисовать легенду для ANSI раскладки

## Замеченные конфликты в разных приложениях
**Chrome, Skype, Photoshop, Telegram** — сходные сочетания клавиш попадаются лишь для плагинов, или отдельных панелей/инструментов, которые никак не связаны с вводом текста. В **inDesign** при наборе текста мне не удалось найти конфликтов раскладки не смотря на [нечеловеческие дефолтовые сочетания](https://helpx.adobe.com/indesign/using/default-keyboard-shortcuts.html) для работы со шрифтами.

**Atom (fixed)**

- [x] <kbd>Alt Gr</kbd>+<kbd>-</kbd>
- [x] <kbd>Alt Gr</kbd>+<kbd>=</kbd>
- [x] <kbd>Alt Gr</kbd>+<kbd>Q</kbd>
- [x] <kbd>Alt Gr</kbd>+<kbd>R</kbd>
- [x] <kbd>Alt Gr</kbd>+<kbd>Shift</kbd>+<kbd>R</kbd>
- [ ] <kbd>Alt Gr</kbd>+<kbd>I</kbd>
- [x] <kbd>Alt Gr</kbd>+<kbd>O</kbd>
- [x] <kbd>Alt Gr</kbd>+<kbd>P</kbd>
- [x] <kbd>Alt Gr</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd>
- [x] <kbd>Alt Gr</kbd>+<kbd>[</kbd>
- [x] <kbd>Alt Gr</kbd>+<kbd>Shift</kbd>+<kbd>{</kbd>
- [x] <kbd>Alt Gr</kbd>+<kbd>]</kbd>
- [x] <kbd>Alt Gr</kbd>+<kbd>Shift</kbd>+<kbd>}</kbd>
- [x] <kbd>Alt Gr</kbd>+<kbd>D</kbd>
- [x] <kbd>Alt Gr</kbd>+<kbd>F</kbd>
- [x] <kbd>Alt Gr</kbd>+<kbd>H</kbd>
- [x] <kbd>Alt Gr</kbd>+<kbd>B</kbd>
- [x] <kbd>Alt Gr</kbd>+<kbd>Shift</kbd>+<kbd>B</kbd>
- [x] <kbd>Alt Gr</kbd>+<kbd>M</kbd>
- [x] <kbd>Alt Gr</kbd>+<kbd>.</kbd>

**Sublime Text 3**

- [ ] <kbd>Alt Gr</kbd>+<kbd>P</kbd> — Global
- [ ] <kbd>Alt Gr</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> — Global
- [ ] <kbd>Alt Gr</kbd>+<kbd>L</kbd> — Markdown Editing plugin
- [ ] <kbd>Alt Gr</kbd>+<kbd>G</kbd> — Markdown Editing plugin
- [ ] <kbd>Alt Gr</kbd>+<kbd>S</kbd> — Markdown Editing plugin

Для Саблайма есть костыль. В конфиг кастомных сочетаний клавиш нужно вписывать штуки типа

```
{ "keys": ["ctrl+alt+l"], "command": "insert_snippet", "args": {"contents": "|"} },
{ "keys": ["ctrl+alt+g"], "command": "insert_snippet", "args": {"contents": "§"} },
{ "keys": ["ctrl+alt+s"], "command": "insert_snippet", "args": {"contents": "∑"} }
```
