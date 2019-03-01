## git-dots

Dotfiles managed only by Git.

Setup

```
git init --bare $HOME/git/hub/git-dots
alias git-dots='git --git-dir=$HOME/git/hub/git-dots/ --work-tree=$HOME'
git-dots remote add origin git@github.com:jreisinger/git-dots.git
git-dots config status.showUntrackedFiles no
```

See tracked files

```
git-dots ls-tree -r master --name-only
```

More

* https://wiki.archlinux.org/index.php/Dotfiles
* https://news.ycombinator.com/item?id=11070797
* https://github.com/Siilwyn/my-dotfiles/tree/master/.my-dotfiles
