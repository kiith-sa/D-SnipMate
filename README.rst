==========
D-SnipMate
==========

D-SnipMate is a snippet file adding `D language <http://dlang.org>`_ support to
the `SnipMate <https://github.com/garbas/vim-snipmate>`_  plugin for the 
`Vim <http://www.vim.org>`_ text editor. SnipMate adds TextMate-like snippets 
for Vim.

-----
Notes
-----

This is a snippet file I created for my own usage. It is quite heavy and might
be obtrusive for some (e.g. there are many 2-character snippets) .

Due to a SnipMate bug (or maybe a SnipMate + my specific Vim configuration bug,
I don't know) , every snippet is made so that slots later on a line are 
accessed before slots earlier on the line. E.g; ::

   foreach(${2:var}; ${1:iterable})

Instead of: ::

   foreach(${1:var}; ${2:iterable})

To install D-SnipMate, copy the ``d.snippets`` file to the ``snippets`` 
directory in your Vim directory. Of course, you need to have SnipMate 
installed first.




