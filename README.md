Arch Linux workstation dotfiles
===============================


Bash configuration
------------------

For bash to correctly source its configuration files
from ~/.config/bash the following lines need to be 
added to the system-wide configuration...

'''
/etc/bash.bashrc

[ -f ~/.config/bash/bashrc ] && . ~/.config/bash/bashrc



/etc/profile

[ -f ~/.config/bash/bash_profile ] && . ~/.config/bash/bash_profile
'''

