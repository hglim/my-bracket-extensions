#Code folding for Brackets
A code folding extension for [Brackets](https://github.com/adobe/brackets/) based on [CodeMirror's folding addon](http://codemirror.net/demo/folding.html).
Peforms code folding based on brace ({}, []) matching and multiline comments for javascript, json, css, php and less files. Also has some support for html and xml files based on tag matching.

### Features
1. Define custom regions in any language recognised in Brackets by creating a line comment whose first word is **region** to designate the beginning of a region, and another line comment whose first word is **endregion** to designate the end of a region

2. Collapse or expand all foldable child regions by holding down the Alt-key while clicking on fold triangles (as found in OSX Finder).

3. Fold states are persisted to preferences file.

### How to install
Navigate to **Brackets > File > Install Extension** and paste url https://github.com/thehogfather/brackets-code-folding

####Or manually
1. [Download](https://github.com/thehogfather/brackets-code-folding/archive/master.zip)
2. Unzip in **user** folder in **Brackets > Help > Show Extensions Folder**
3. Restart or Reload Brackets

### Keyboard shortcuts
The following are the default keyboard shortcut keys for the code-folding extension.

    Ctrl-Alt-C Collapse code region at current cursor position
    Ctrl-Alt-X Expand code region at current cursor position
    Alt-1 Collapse all code regions in current editor
    Shift-Alt-1 Expand all code regions in current editor

##Known Issues
#### Conflicting keyboard shortcuts
**If any of the shortcut keys above conflict with your keyboard or you would prefer to use another shortcut key for any reason, please use an extension like [Brackets Key Remapper](https://bitbucket.org/sacah/brackets-key-remapper) to change the shortcut keys to suit your needs.**

#### EdgeCode support
If you are running edge code, the latest compatible version is [v0.2.7](https://github.com/thehogfather/brackets-code-folding/tree/v0.2.7). You can download and install from [this url](https://github.com/thehogfather/brackets-code-folding/tree/v0.2.7).

### License
MIT-licensed.

### Credits
CodeMirror folding addon.

### Compatibility
Brackets Sprint 38 or later.
