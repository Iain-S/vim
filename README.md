# vim
My standard vim configuration.  See https://dougblack.io/words/a-good-vimrc.html for an alternative, and probably equally good, one.

To use on Windows, clone the .vim folder into the home directory:

<pre>
-> home\
  -> .vim\
    -> .vimrc
</pre>

and then make a symbolic link with an admin-mode cmd prompt:

    mklink ".vimrc" ".vim/.vimrc"

so that the directory structure now looks like:

<pre>
-> home
  -> .vimrc (symlink)
  -> .vim
    -> .vimrc (real file)
</pre>
