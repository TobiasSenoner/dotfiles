# dotfiles

1 **.tmux.conf** <br>
(Inspired by: https://github.com/samoshkin/tmux-config/blob/master/tmux/tmux.conf)
* Add file to HOME
* Clone git repo: 
```bash
$ git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```
* Reload TMUX environment:
```bash
$ tmux source ~/.tmux.conf
```
* Install new plugins + refresh TMUX environment: Press `prefix` + <kbd>I</kbd> (capital i)
* You're good to go! The plugin was cloned to `~/.tmux/plugins/` dir and sourced.
