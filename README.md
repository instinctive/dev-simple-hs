# Simple Haskell Repo

Simple Haskell repo for new projects.

    $ git clone git@github.com:instinctive/dev-simple-hs.git mynewdir
    $ cd mynewdir
    $ ./setup MyProject myproject

Where `MyProject` is your starting Haskell library module, and `myproject` is
your lower-case project name. These must be a legal Haskell identifiers.

The `setup` script will delete the git repo, git init this one,
create a placeholder `README.md`, and do the initial git commit.

Then you can build and run the simple project.

    $ nix-shell
    $ cabal run
