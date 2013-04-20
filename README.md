brackets-theme
============================

Brackets theme update and MacOSX antialiasing fix.

Navigate to the www folder.

MacOSX
---

`/Applications/Brackets Sprint 23.app/Content/www`


Windows
---

`C:\Program Files (x86)\Brackets Sprint 23\www`

Make a backup of your brackets.less and brackets_theme_default.less.  Replace them with the files in this repository.

You can modify the font size at line 123 and 124.  It may be to large for your screen size.

```js
.code-font() {
    color: @content-color;
    // line-height must be specified in px not em because the code font and line number font sizes are different.
    // Sizing via em will cause the code and line numbers to misalign
    line-height: 22px;
    font-size: 17px;
    font-family: 'SourceCodePro', "ＭＳ ゴシック", "MS Gothic", monospace;
}
```	

Turns this



into this

