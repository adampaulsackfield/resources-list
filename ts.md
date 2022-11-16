# Useful Shortcuts

A selection of shortcuts, these are MacOS centric, but the same should be possible on Windows.

---

## Terminal

- `control + a` - Goto start of line.
- `control + e` - Goto end of line.
- `control + w` - Remove words, backwards.
- `!!` - Runs the previous command. Say you ran `/dev /devOps` as you wanted to changed the name but forgot the `mv`. You could now run `mv !!` which will complete as `mv /dev /devOps`

## Aliases

You can set up aliases (shortcuts) in many terminals. The following will be for _ohmyzsh_ but you can find the equivalent for all terminals. Below is a snippet of a `.zshrc` file with some aliases. The part to the left of `=` is the command, for example, `gs`. The part to the right of the `=` is the command to run. These commands can take arguments. Mac users may have `.bash_profile` file in the `~` directory. Guider [here](https://dev.to/mhjaafar/git-bash-on-windows-adding-a-permanent-alias-198g) for Windows users.

```bash
alias meow="cat"
alias zshconfig="code ~/.zshrc"
alias ohmyzsh="code ~/.oh-my-zsh"
alias dev="cd ~/Development"

alias mon="brew services start mongodb-community@5.0"
alias moff="brew services stop mongodb-community@5.0"

alias gs="git status"
alias gaa="git add ."
alias ga="git add "
alias gc="git commit -m "
alias gp="git push origin "
alias dmb="git branch --merged | grep -v \* | xargs git branch -D" # Delete all merged local branches
```
