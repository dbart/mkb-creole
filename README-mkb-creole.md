# General Information
The files in this package are designed to help you edit
[MariaDB Knowledge Base](https://mariadb.com/kb "MariaDB Knowledge Base")
articles.

The MariaDB Knowledge Base uses wikicreole as its
[base syntax](https://mariadb.com/kb/en/editing-help "MariaDB Knowledge Base editing help"),
extended with several useful
[macros](https://mariadb.com/kb/en/macros "MariaDB Knowledge Base Macros").
This package provides syntax highlighting for VIM and some useful snippets for
use with
[SnipMate](http://www.vim.org/scripts/script.php?script_id=2540 "SnipMate") to
help with writing and editing Knowledge Base articles.

# Installation

Download the zip file, navigate to the `~/.vim/` directory, and unzip the file.
The files will be placed in their proper locations.

To enable, add the following to `~/.vim/filetype.vim`:
    augroup filetypedetect
        autocmd BufRead,BufNewFile *.creole,*.mkb-creole,*.mkb setfiletype mkb-creole
    augroup END

# Usage
The best way to use this is with
[It's All Text!](https://addons.mozilla.org/en-US/firefox/addon/its-all-text/)
for Firefox,
[Edit with Emacs](https://chrome.google.com/webstore/detail/edit-with-emacs/)
for Chrome, or something similar that allows you to edit text areas with VIM.
Whichever one you use, set it up to open MariaDB Knowledge Base source with a
`.creole`, `.mkb-creole`, or `.mkb` extension.

