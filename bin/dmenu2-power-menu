#!/bin/bash

# dmenu power menu
#

OPT=$(echo -e "lock\nsuspend\npoweroff\nreboot" | dmenu -f -h 28 -fn "Ubuntu Mono:12" -x 435 -y 370 -w 410 -nb black -nf white -sb white -sf black )

case $OPT in
    lock) slock ;;
    suspend) systemctl suspend ;;
    poweroff) systemctl poweroff ;;
    reboot) systemctl reboot ;;
    *) ;;
esac

