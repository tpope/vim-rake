rake.vim
========

With rake.vim, you can use all those parts of
[rails.vim](https://github.com/tpope/vim-rails) that you wish you could
use on your other Ruby projects on anything with a `Rakefile`, including
`:R`/`:A`, `:Rlib` and friends, and of course `:Rake`.  It's great when
paired with `gem open` and `bundle open` and complemented nicely by
[bundler.vim](https://github.com/tpope/vim-bundler).

Installation
------------

If you don't have a preferred installation method, I recommend
installing [pathogen.vim](https://github.com/tpope/vim-pathogen), and
then simply copy and paste:

    cd ~/.vim/bundle
    git clone git://github.com/tpope/vim-rake.git

Once help tags have been generated, you can view the manual with
`:help rake`.

FAQ
---

> I installed the plugin and started Vim.  Why don't any of the commands
> exist?

This plugin cares about the current file, not the current working
directory.  Edit a file from a Ruby library.

> I opened a new tab.  Why don't any of the commands exist?

This plugin cares about the current file, not the current working
directory.  Edit a file from a Ruby library.  You can use the `:RT`
family of commands to open a new tab and edit a file at the same time.

Contributing
------------

See the contribution guidelines for
[rails.vim](https://github.com/tpope/vim-rails#readme).

Self-Promotion
--------------

Like rake.vim? Follow the repository on
[GitHub](https://github.com/tpope/vim-rake) and vote for it on
[vim.org](http://www.vim.org/scripts/script.php?script_id=3669).  And if
you're feeling especially charitable, follow [tpope](http://tpo.pe/) on
[Twitter](http://twitter.com/tpope) and
[GitHub](https://github.com/tpope).

License
-------

Distributable under the same terms as Vim itself.  See `:help license`.
