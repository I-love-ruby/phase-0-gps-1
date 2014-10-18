phase-0-gps-1
=============
Your branch is up-to-date with 'origin/master'.
nothing to commit, working directory clean
phase-0-gps-1 [master] :> git branch "awesome-feature"
phase-0-gps-1 [master] :> ls
LICENSE         README.md       awesome_page.md
phase-0-gps-1 [master] :> git status
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working directory clean
phase-0-gps-1 [master] :> git branch
  awesome-feature
* master
phase-0-gps-1 [master] :> git checkout master
Already on 'master'
Your branch is up-to-date with 'origin/master'.
phase-0-gps-1 [master] :> git branch awesome-feature
fatal: A branch named 'awesome-feature' already exists.
phase-0-gps-1 [master] :> git checkout
HEAD              master            origin/master
awesome-feature   origin/HEAD
phase-0-gps-1 [master] :> git checkout awesome-feature
Switched to branch 'awesome-feature'
phase-0-gps-1 [awesome-feature] :> ls
LICENSE         README.md       awesome_page.md
phase-0-gps-1 [awesome-feature] :> subl
phase-0-gps-1 [awesome-feature] :> subl readme
phase-0-gps-1 [awesome-feature] :> subl README.md
phase-0-gps-1 [awesome-feature] :>