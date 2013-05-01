Vim .gitignore filetype plugin
==============================

> Yet underway...

About
-----

This plugin adds syntax highlighting and code snippets
(using [snipMate](https://github.com/msanders/snipmate.vim))
based on https://github.com/github/gitignore snippets
for `.gitignore` files in Vim.


Requirements
------------

* For using code snippets your must install
[snipMate](https://github.com/msanders/snipmate.vim)
* For useful commenting/uncommenting install
[tComment](https://github.com/tomtom/tcomment_vim)


Installation ways
-----------------

* Using [pathogen](https://github.com/tpope/vim-pathogen)
or [vundle](https://github.com/gmarik/vundle) from
https://github.com/rdolgushin/gitignore.vim
* Standard [Vim way](http://vimdoc.sourceforge.net/htmldoc/usr_05.html#add-plugin)


Usage
-----

### Snippets

Gitignore.vim contains an usual snipMate snippets. You can use it by
opening your `.gitignore` file, typing snippet name (for example, `Python`)
and pressing `<Tab>` key.

### Commenting

For commenting you can use standard tComment `<C-_>` key.
