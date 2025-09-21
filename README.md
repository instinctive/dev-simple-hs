# Simple Haskell Repo

Simple Haskell repo for new projects.

    $ git clone git@github.com:instinctive/dev-simple-sh.git changeme
    $ cd changeme
    $ ./rename CHANGEME changeme

Where `CHANGEME` is your starting Haskell library module, and `changeme` is
your lower-case project name. These must be a legal Haskell identifiers.

The `rename` script will also delete the git repo and git init this one.

Then you can build and run the simple project.

    $ nix-shell
    $ cabal run
