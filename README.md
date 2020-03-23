# go-task completions

Zsh completions for [go-task](https://github.com/go-task/task)

[![asciicast](https://asciinema.org/a/MZn6pzx7DUTMt1y3pCnEtNi1W.png)](https://asciinema.org/a/MZn6pzx7DUTMt1y3pCnEtNi1W)

## Usage

Completion for `task`

```bash
task <TAB>
```

Completion for options


```bash
task -<TAB>
```

## Installation

### [oh-my-zsh](http://github.com/robbyrussell/oh-my-zsh)

Clone the repository inside your oh-my-zsh repo:
```bash
git clone https://github.com/sawadashota/go-task-completions.git ${ZSH_CUSTOM:=~/.oh-my-zsh/custom}/plugins/go-task-completions
```

Enable it in your .zshrc by adding it to your plugin list and reloading the completion:
```bash
plugins=(… go-task-completions)
autoload -U compinit && compinit
```
