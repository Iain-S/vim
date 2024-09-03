# vim

My standard vim configuration.
See <https://dougblack.io/words/a-good-vimrc.html> for an alternative config.

To use, clone the .vim folder (e.g. into the home directory):

<pre>
-> home\
  -> .vim\
    -> .vimrc
</pre>

and then make a symbolic link:

```winbatch
mklink ".vimrc" ".vim/.vimrc"
```

so that the directory structure now looks like:

<pre>
-> home
  -> .vimrc (symlink)
  -> .vim
    -> .vimrc (real file)
</pre>

