git-cleanup
===========

Clean up fully merged branches


Installation
------------

    $ git clone https://github.com/mattv/git-cleanup.git
    $ cd git-cleanup
    $ chmod 755 git-cleanup
    $ ln -s `pwd`/git-cleanup /usr/local/bin/git-cleanup

Usage
-----

To remove all local fully-merged branches:

    $ git cleanup

To remove all remote fully-merged branches:

    $ git cleanup --remote


Notes
-----

You should be on a clean branch when running this script (no unstaged/uncommitted files)
