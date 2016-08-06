#TO-DO

- [x] Пофиксить дельту
- [x] Вернуть sup 1
- [x] Вертикальную черту добавить
- [ ] Выпилить многоточие
- [ ] Куда делся  \` из русской раскладки?
- [x] Выяснить что не так с <kbd>Alt Gr</kbd>+<kbd>L</kbd> в Sublime
- [ ] Подумать над сменой мест » → >
- [ ] Нарисовать новые иконки для OSX
- [ ] Фак расширить на OSX
- [ ] <kbd>Alt Gr</kbd>+<kbd>M</kbd> починить для вебовых Google Docs
- [ ] Совместимость в Atom и его плагинах проверить

## Замеченные конфликты в разных приложениях
**Chrome, Skype, Photoshop** — сходные сочетания клавиш попадаются лишь для плагинов, или отдельных панелей/инструментов, которые никак не связаны с вводом текста. В **inDesign** при наборе текста мне не удалось найти конфликтов раскладки не смотря на [нечеловеческие дефолтовые сочетания](https://helpx.adobe.com/indesign/using/default-keyboard-shortcuts.html) для работы со шрифтами.

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
