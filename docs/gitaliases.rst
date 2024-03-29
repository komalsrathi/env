.. |date| date::

**tldr**: These aliases are based on the neat robbyrussell's zsh git plugin.
For detailed information see `documentation`_

***********
Git Aliases
***********

:authors: Gunes Gundem, Komal Rathi, Juan Medina
:contact: medinaj@mskcc.org
:organization: Memorial Sloan-Kettering
:date: |date|

Introduction
============

These aliases are based on the neat robbyrussell's zsh git plugin.
For detailed information see the `documentation`_.

To use them, add this to your bash profile:

.. code:: bash

    if [ -f /ifs/work/leukgen/opt/.env/cgp ]; then
       . /ifs/work/leukgen/.env/cgp
    fi

Examples
========

+--------+-------------------------------------------------+
| Alias  | Command                                         |
+========+=================================================+
| g      | git                                             |
+--------+-------------------------------------------------+
| ga     | git add                                         |
+--------+-------------------------------------------------+
| gaa    | git add --all                                   |
+--------+-------------------------------------------------+
| gapa   | git add --patch                                 |
+--------+-------------------------------------------------+
| gb     | git branch                                      |
+--------+-------------------------------------------------+
| gba    | git branch -a                                   |
+--------+-------------------------------------------------+
| gbl    | git blame -b -w                                 |
+--------+-------------------------------------------------+
| gbnm   | git branch --no-merged                          |
+--------+-------------------------------------------------+
| gbr    | git branch --remote                             |
+--------+-------------------------------------------------+
| gbs    | git bisect                                      |
+--------+-------------------------------------------------+
| gbsb   | git bisect bad                                  |
+--------+-------------------------------------------------+
| gbsg   | git bisect good                                 |
+--------+-------------------------------------------------+
| gbsr   | git bisect reset                                |
+--------+-------------------------------------------------+
| gbss   | git bisect start                                |
+--------+-------------------------------------------------+
| gc     | git commit -v                                   |
+--------+-------------------------------------------------+
| gc!    | git commit -v --amend                           |
+--------+-------------------------------------------------+
| gca    | git commit -v -a                                |
+--------+-------------------------------------------------+
| gcam   | git commit -a -m                                |
+--------+-------------------------------------------------+
| gca!   | git commit -v -a --amend                        |
+--------+-------------------------------------------------+
| gcan!  | git commit -v -a -s --no-edit --amend           |
+--------+-------------------------------------------------+
| gcb    | git checkout -b                                 |
+--------+-------------------------------------------------+
| gcf    | git config --list                               |
+--------+-------------------------------------------------+
| gcl    | git clone --recursive                           |
+--------+-------------------------------------------------+
| gclean | git reset --hard && git clean -dfx              |
+--------+-------------------------------------------------+
| gcm    | git checkout master                             |
+--------+-------------------------------------------------+
| gcmsg  | git commit -m                                   |
+--------+-------------------------------------------------+
| gco    | git checkout                                    |
+--------+-------------------------------------------------+
| gcount | git shortlog -sn                                |
+--------+-------------------------------------------------+
| gcp    | git cherry-pick                                 |
+--------+-------------------------------------------------+
| gcs    | git commit -S                                   |
+--------+-------------------------------------------------+
| gd     | git diff                                        |
+--------+-------------------------------------------------+
| gdca   | git diff --cached                               |
+--------+-------------------------------------------------+
| gdt    | git diff-tree --no-commit-id --name-only -r     |
+--------+-------------------------------------------------+
| gdw    | git diff --word-diff                            |
+--------+-------------------------------------------------+
| gf     | git fetch                                       |
+--------+-------------------------------------------------+
| gfa    | git fetch --all --prune                         |
+--------+-------------------------------------------------+
| gfo    | git fetch origin                                |
+--------+-------------------------------------------------+
| gg     | git gui citool                                  |
+--------+-------------------------------------------------+
| gga    | git gui citool --amend                          |
+--------+-------------------------------------------------+
| ggpull | ggl                                             |
+--------+-------------------------------------------------+
| ggpur  | ggu                                             |
+--------+-------------------------------------------------+
| ggpush | ggp                                             |
+--------+-------------------------------------------------+
| gl     | git pull                                        |
+--------+-------------------------------------------------+
| glg    | git log --stat --color                          |
+--------+-------------------------------------------------+
| glgg   | git log --graph --color                         |
+--------+-------------------------------------------------+
| glgga  | git log --graph --decorate --all                |
+--------+-------------------------------------------------+
| glgm   | git log --graph --max-count = 10                |
+--------+-------------------------------------------------+
| glgp   | git log --stat --color -p                       |
+--------+-------------------------------------------------+
| glo    | git log --oneline --decorate --color            |
+--------+-------------------------------------------------+
| glog   | git log --oneline --decorate --color --graph    |
+--------+-------------------------------------------------+
| glp    | _git_log_prettily                               |
+--------+-------------------------------------------------+
| gm     | git merge                                       |
+--------+-------------------------------------------------+
| gmom   | git merge origin/master                         |
+--------+-------------------------------------------------+
| gmt    | git mergetool --no-prompt                       |
+--------+-------------------------------------------------+
| gmtvim | git mergetool --no-prompt --tool = vimdiff      |
+--------+-------------------------------------------------+
| gmum   | git merge upstream/master                       |
+--------+-------------------------------------------------+
| gp     | git push                                        |
+--------+-------------------------------------------------+
| gpd    | git push --dry-run                              |
+--------+-------------------------------------------------+
| gpoat  | git push origin --all && git push origin --tags |
+--------+-------------------------------------------------+
| gpu    | git push upstream                               |
+--------+-------------------------------------------------+
| gpv    | git push -v                                     |
+--------+-------------------------------------------------+
| gr     | git remote                                      |
+--------+-------------------------------------------------+
| gra    | git remote add                                  |
+--------+-------------------------------------------------+
| grb    | git rebase                                      |
+--------+-------------------------------------------------+
| grba   | git rebase --abort                              |
+--------+-------------------------------------------------+
| grbc   | git rebase --continue                           |
+--------+-------------------------------------------------+
| grbi   | git rebase -i                                   |
+--------+-------------------------------------------------+
| grbm   | git rebase master                               |
+--------+-------------------------------------------------+
| grbs   | git rebase --skip                               |
+--------+-------------------------------------------------+
| grh    | git reset HEAD                                  |
+--------+-------------------------------------------------+
| grhh   | git reset HEAD --hard                           |
+--------+-------------------------------------------------+
| grmv   | git remote rename                               |
+--------+-------------------------------------------------+
| grrm   | git remote remove                               |
+--------+-------------------------------------------------+
| grset  | git remote set-url                              |
+--------+-------------------------------------------------+
| gru    | git reset --                                    |
+--------+-------------------------------------------------+


.. _documentation: https://github.com/robbyrussell/oh-my-zsh/wiki/Plugin%3Agit/_edit
