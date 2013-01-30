gitwdiff
========

Better word-diff for Git and SVN.

Usage
-----

Add everything to your `$PATH`. Make sure you have `wdiff` installed.

Use `gitwdiff ...` instead of `git diff ...`.

Use `svnwdiff ...` instead of `svn diff ...`.

For the best results, copy the settings from `gitconfig-example` to
your `~/.gitconfig`. After that:

 - Long lines are wrapped in the output
   (no horizontal scrolling in the pager).

 - The usual Git commands such as `git diff`, `git show`, and
   `git status` will use colours that are similar to the colour
   scheme of `gitwdiff`.

Git uses a pager by default. With SVN, you can try this:

    svnwdiff ... | less -R


Examples
--------

More examples at: https://github.com/suomela/gitwdiff/tree/examples/example

### gitwdiff

<img src="https://raw.github.com/suomela/gitwdiff/examples/example/example1-gitwdiff.png" alt="gitwdiff" title="gitwdiff">]

### git diff --color-words

<img src="https://raw.github.com/suomela/gitwdiff/examples/example/example1-git-diff-color-words.png" alt="git diff --color-words" title="git diff --color-words">

### git diff --word-diff

<img src="https://raw.github.com/suomela/gitwdiff/examples/example/example1-git-diff-word-diff.png" alt="git diff --word-diff" title="git diff --word-diff">


Dependencies
------------

wdiff - http://www.gnu.org/software/wdiff/


Colours
-------

Try `gitwdiff1` or `gitwdiff2` for alternative colour schemes.

See http://en.wikipedia.org/wiki/ANSI_escape_code for the colour codes.
