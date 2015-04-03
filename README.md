# SAS language support in Atom

Adds syntax highlighting, and auto indentation to SAS files in Atom.

100% hand written. Not converted from TextMate/Sublime.

In the past a few years, I have been mainly using Vim to code my SAS programs. I recently decided to switch to Atom due to its better integration for OS X. This SAS language package is my first effort to switch to the new editor. I wrote the Vim SAS [syntax script](http://www.vim.org/scripts/script.php?script_id=3522) and [indentation script](http://www.vim.org/scripts/script.php?script_id=4034) and I feel that Atom allows me to better implement what I did in Vim.

Contributions are greatly appreciated. Please fork this repository and open a pull request to add modifications, patches, etc.

## Features

### Syntax highlighting

Syntax highlighting supports base SAS syntax up to ver. **9.3**. It can automatically distinguish different statement keywords with respect to the **data step section** and the **procedure section**. This package also supports highlighting the **SQL procedure** keywords.

![Syntax highlighting](https://cloud.githubusercontent.com/assets/9272721/6988864/f2a92720-da1a-11e4-9dc7-8bb0d4a95800.PNG)
> The screenshot used the default One Dark theme.

### Auto indentation

Auto indentation is supported. However, there are some limitations due to how Atom currently implemented its indentation mechanism. I was not able to implement the exact indentation behavior as what I did in the Vim SAS indentation script.

## Install

Go to `Atom > Preferences...` then search for **SAS Language** in Install tab.

## To-do

1. Snippets
2. SAS/STAT syntax highlighting
3. PROC IML specific syntax highlighting
