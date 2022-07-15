# A syntax highlighting vimscript for endless sky plain text data

This is a naive and simple syntax highlighting vimscript for endless sky data.

###### installation

Under most Linux installations:
- Drop the `.vim` file in `$HOME/.vim/syntax/` or `/usr/share/vim/vim*/syntax/`

##### usage

No automatic filetype detection is performed, as no such routines have been
written by the author. Therefore you must use `:setf endlessskydata` to set
the correct highlighting. You can probably enforce this automatically per
directory in a vim configuration file.

[leklachu] Personally I smylink from ~/.vim/syntax/esky.vim to make it easier to use, from vim with the command `:setf esky` (less typing!)

To do this, after installing endlessskydata.vim into `$HOME/.vim/syntax` as above, navigate to that directory and add the symlink:

`cd ~/.vim/syntax`  
`ln -s endlessskydata.vim esky.vim`

###### license

See the `LICENSE` file, as well as `COPYING`.
