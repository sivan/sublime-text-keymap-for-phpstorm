# 适用于 PhpStorm 的 Sublime Text 键位配置

这是一份适用于 PhpStorm（未测试其他  JetBrains IDE）的 Sublime Text 3 键位配置。基本还原了 Sublime Text 3 原生的大部分键位设置。

## 使用说明
在 「File - Import Settings…」导入 `dist/sublime-keymap.jar` 文件即可。

## Cheat Sheet
这里有一份适用于 PhpStorm 的 Sublime Text 3 Keymap Cheat Sheet：  
[http://www.cheatography.com/sivan/cheat-sheets/sublime-text-cheat-sheet-os-x/](http://www.cheatography.com/sivan/cheat-sheets/sublime-text-cheat-sheet-os-x/)

## 注意事项

* 没有找到「Edit-Undo Selection」里各指令的对应动作；
* 指令「Edit-Line-Delete Line」除了快捷键「⌃⇧K」，还保留了 PhpStorm 本身的快捷键 「⌘⌫」；
* 指令「Edit-Text-Delete to Beginning」未采用原本快捷键「⌘⌫」，OS X 系统快捷键「⌃T」即可实现；
* 没有找到「Edit-Text-Transpose 」指令的对应动作；
* 指令「Edit-Tag-Close Tag 」通过「[Completing Punctuation](https://www.jetbrains.com/phpstorm/help/completing-punctuation.html)」实现；
* 指令「Edit-Tag-Expand Selection to Tag」通过 PhpStorm 本身指令「Extend Selection」实现，快捷键相同；
* 「Edit-Mark」里各指令可通过「[Managing Bookmarks](https://www.jetbrains.com/phpstorm/help/managing-bookmarks.html)」实现；
* 「Edit-Convert Case」里各指令通过「[Toggling Case](https://www.jetbrains.com/phpstorm/help/toggling-case.html)」（⇧⌘U）实现（Sublime Text 默认没有为相应指令「Swap Case」绑定快捷键）；
* 「Edit-Sort Lines」可通过「[Lines Sorter](https://plugins.jetbrains.com/plugin/5919)」插件实现；
* 「Selection-Split into Lines」可通过按住「⌥」拖动鼠标实现[^1]；
* 「Selection-Expand Selection to …」通过「[Completing Punctuation](https://www.jetbrains.com/phpstorm/help/completing-punctuation.html)」（⌥⌘A）实现；
* 「Find-Replace Next」可通过搜索/替换时，在搜索框中按「⌥P」实现；
* 「Find-Use Selection for …」为 PhpStorm 默认表现；
* 「View-Layout」及「View-Group」里各指令可通过「[Splitting and Unsplitting Editor Window](https://www.jetbrains.com/phpstorm/help/splitting-and-unsplitting-editor-window.html)」实现；
* 没有找到「View-Move File to Group」里各指令的对应动作；
* 指令「Goto-Goto Definition…」可通过「[Declaration](https://www.jetbrains.com/phpstorm/help/navigating-to-declaration-or-type-declaration-of-a-symbol.html)」实现；
* 调换了指令「Goto-Switch File-Next/Previous File」[^2]与「Goto-Switch File-Next/Previous File in Stack」的快捷键；
* 没有找到「Goto-Switch File-Switch Header/Implementation」指令的对应动作；
* 「Goto-Bookmarks-Clear Bookmarks」会先呼出「Bookmarks」窗口再进行删除。

[^1]:	http://youtrack.jetbrains.com/issue/IDEA-122181
[^2]:	通过 PhpStorm 的 [Switcher](https://www.jetbrains.com/phpstorm/help/navigating-between-files-and-tool-windows.html) 实现

-- EOF --