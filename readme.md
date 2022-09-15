# Some Useful Templates for Quick Setup

## command prompt

### bash

```bash
PS1="[\e[1;32m\u@\H\e[0m]:\e[0;34m\w\e[0m\$ "
```
[explained](https://phoenixnap.com/kb/change-bash-prompt-linux)
```

```


### zsh
[zsh manual](https://web.cs.elte.hu/zsh-manual/zsh_17.html)
[zsh prompt generator](https://zsh-prompt-generator.site/)
```zsh
PROMPT="%F{34}%n%f@%F{34}%m%f:%F{11}%~%f> "

%Sinverted%s
%Uunderlined%u
%Bbold%b
%F{<color>}%f

Foreground colors: black, white, yellow, green, red, blue, cyan, magenta
or {0-255}

NEWLINE=$'/n'

```
[some tips](https://www.makeuseof.com/customize-zsh-prompt-macos-terminal/)
[git info in prompt](https://github.com/zsh-users/zsh/blob/master/Misc/vcs_info-examples)
