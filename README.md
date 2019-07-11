# Vim-Matchit

Mirror repository created to be easy to install with git and git submodules using the official vim packages.

Created from the version 1.13.2 (2008) of the vim plugin: **Matchit**.

vim page : https://www.vim.org/scripts/script.php?script_id=39

### Vim packages

Since vim version 8.0, vim include it's own package manager.

You can type `:help packages` in vim to found more informations, or have a look to vimcasts: http://vimcasts.org/episodes/packages/

## Installation

### Without git submodules

```shell
mkdir -p ~/.vim/pack/vim-matchit
cd ~/.vim/pack/vim-matchit
git clone https://github.com/arouene/vim-matchit.git
```

### With git submodules

```shell
cd ~/.vim/
git submodule add https://github.com/arouene/vim-matchit.git pack/vim-matchit
```

## Description from the vim page

```
created by
Benji Fisher
 
script type
utility
 
description
The matchit.vim script allows you to configure % to match more than just
single characters.  You can match words and even regular expressions.
Also, matching treats strings and comments (as recognized by the
syntax highlighting mechanism) intelligently.
The default ftplugins include settings for several languages:
Ada, ASP with VBS, Csh, DTD, Essbase, Fortran, HTML, JSP
(same as HTML), LaTeX, Lua, Pascal, SGML, Shell, Tcsh, Vim, XML.
(I no longer keep track, so there may be others.)
The documentation (included in the zip file) explains how to configure
the script for a new language and how to modify the defaults.

Since vim 6.0, matchit.vim has been included in the standard vim distribution,
under the macros/ directory; the version here may be more recent.
 
install details
Vim 5.x:  Make sure to download the correct version (1.0).  Add a line like

:source path/to/matchit.vim

to your vimrc file.  More details are in matchit.html (included).

Vim 6.x, 7.x:  Download the most recent version.
Unpack the zip file in your personal vim directory (e.g. ~/.vim on *NIX):
this will put matchit.vim in your plugin/ directory and put matchit.txt into
your doc/ directory.  Then do

:helptags ~/.vim/doc

to rebuild the tags file.  For details, read

:help add-local-help

Make sure you have a line like

:filetype plugin on

in your vimrc file.  This enables filetype plugins, many of which tell
matchit.vim which matching pairs to use.
```
