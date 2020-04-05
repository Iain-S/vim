# vim
My standard vim configuration

To use on Windows, clone the .vim folder into the home directory:

-> home
  -> .vim
    -> .vimrc
   
and then make a symbolic link with an admin-mode cmd prompt:

    mklink ".vimrc" ".vim/.vimrc"

so that the directory structure now looks like:


-> home
  -> .vimrc (symlink)
  -> .vim
    -> .vimrc (real file)