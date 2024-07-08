<backgroundimage>assets/img/Terminal_Logo2_CRT_Flat.png</backgroundimage>
<backgroundimageopacity>0.2</backgroundimageopacity>
## No Aliases
```bash
abbr gco "git checkout"
`gco<space> => git checkout _`
```
```bash
alias --save g="git"
funcsave: wrote /Users/rob/.config/fish/functions/g.fish
cat /Users/rob/.config/fish/functions/g.fish
function g --wraps=git --description 'alias g=git'
  git $argv
end
```
