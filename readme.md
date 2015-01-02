### tree.py

Simple Python script generating pretty directory tree visualisation.

Sample output:
```
grubyak@peso directory-tree $ ./tree.py
directory-tree
|-- readme.md
|-- tree.py
'-- .git
    |-- COMMIT_EDITMSG
    |-- config
    |-- description
    |-- HEAD
    |-- index
    |-- hooks
    |   |-- applypatch-msg.sample
    |   |-- commit-msg.sample
    |   |-- post-update.sample
    |   |-- pre-applypatch.sample
    |   |-- pre-commit.sample
    |   |-- pre-push.sample
    |   |-- pre-rebase.sample
    |   |-- prepare-commit-msg.sample
    |   '-- update.sample
    |-- info
    |   '-- exclude
    |-- logs
    |   |-- HEAD
    |   '-- refs
    |       |-- heads
    |       |   '-- master
    |       '-- remotes
    |           '-- origin
    |               '-- master
    |-- objects
    |   |-- 02
    |   |   '-- b5b11f8216aa8c1af805bae94741de8f10d595
    |   |-- info
    |   '-- pack
    '-- refs
        |-- heads
        |   '-- master
        |-- remotes
        |   '-- origin
        |       '-- master
        '-- tags
```
