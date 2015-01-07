
# u9520107/spf13-vim : Fork of Steve Francia's Vim Distribution


Changes:
======

1. Bundle Groups: general, neocomplcache, programming, javascript, html, misc

2. Indent Guides defaults to off

3. Keep NERDTree open by default

4. Turn off spell check by default

Additions:
=========

1. Editorconfig-vim support

2. <C-a> mapping for select all

3. vim-jsbeautify mapped to <C-f> in visual mode with selected range

4. tern_for_vim support, tern#Def mapped to <F12>

5. jsx support

6. stylus support

7. syntastic check on write, also uses jsxhint and jsonlint node packages for checking.


Node Dependencie:
================

1. vim-jsbeautify: find in ./spf13-vim-3/.vim/bundle/vim-jsbeautify, run npm install.

2. tern_for_vim: find in ./spf13-vim-3/.vim/bundle/tern_for_vim, run npm install.

3. jsxhint: run [sudo] npm install -g jsxhint

4. jsonlint: run [sudo] npm install -g jsonlint
