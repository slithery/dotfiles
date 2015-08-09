Arch Linux workstation dotfiles
===============================


Bash configuration
------------------

For bash to correctly source its config
from ~/.config/bash the following lines need to be 
added to the system-wide configurations...


####/etc/bash.bashrc

```bash
# Custom bashrc location
[ -f ~/.config/bash/bashrc ] && . ~/.config/bash/bashrc
```


####/etc/profile

```bash
# Custom bash_profile location
[ -f ~/.config/bash/bash_profile ] && . ~/.config/bash/bash_profile
```
