## TO-DO

- [x] Пофиксить дельту
- [x] Вернуть sup 1
- [x] Вертикальную черту добавить
- [ ] Выпилить многоточие
- [ ] Выпилить обе i
- [ ] Вертикальную черту перенести на своё место
- [ ] Легенду под ISO/ANSI перерисовать?
- [ ] Подумать над жирной галкой U+2714
- [ ] Подумать над жирным крестом U+2718
- [ ] Куда делся  \` из русской раскладки?
- [x] Выяснить что не так с <kbd>Alt Gr</kbd>+<kbd>L</kbd> в Sublime
- [ ] Подумать над сменой мест » → >
- [ ] Нарисовать новые иконки для OSX
- [ ] Фак расширить на OSX
- [ ] <kbd>Alt Gr</kbd>+<kbd>M</kbd> починить для вебовых Google Docs
- [ ] Совместимость в Atom и его плагинах проверить

## Замеченные конфликты в разных приложениях
**Chrome, Skype, Photoshop** — сходные сочетания клавиш попадаются лишь для плагинов, или отдельных панелей/инструментов, которые никак не связаны с вводом текста. В **inDesign** при наборе текста мне не удалось найти конфликтов раскладки не смотря на [нечеловеческие дефолтовые сочетания](https://helpx.adobe.com/indesign/using/default-keyboard-shortcuts.html) для работы со шрифтами.

**Atom**

~≈¹Δ@½#⅓$¼‰↑^&∞←→—–≠±²³€®√™µΩ′″[{}]∠∑°⌀£§¶₽„“”|‘’;"×©¢↓•★−<«»>…цу́уц

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

- <kbd>Alt Gr</kbd>+<kbd>P</kbd> — Global
- <kbd>Alt Gr</kbd>+<kbd>Shift</kbd>+<kbd>P</kbd> — Global
- <kbd>Alt Gr</kbd>+<kbd>L</kbd> — Markdown Editing plugin
- <kbd>Alt Gr</kbd>+<kbd>G</kbd> — Markdown Editing plugin
- <kbd>Alt Gr</kbd>+<kbd>S</kbd> — Markdown Editing plugin

Для Саблайма есть костыль. В конфиг кастомных сочетаний клавиш нужно вписывать штуки типа

```
{ "keys": ["ctrl+alt+l"], "command": "insert_snippet", "args": {"contents": "|"} },
{ "keys": ["ctrl+alt+g"], "command": "insert_snippet", "args": {"contents": "§"} },
{ "keys": ["ctrl+alt+s"], "command": "insert_snippet", "args": {"contents": "∑"} }
```
