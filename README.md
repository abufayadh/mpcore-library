# MPCORE-HUB Library for Legacy fork

how to update your RetroPie source for legacy updates

go in EmulationStation on Startmenu open Quit -> "go to commandline"

open "sudo nano /home/pi/RetroPie-Setup/.git/config"

and change the source and the merge -> save exit


```shell

source https://github.com/mpcore-hub/RetroPie-Legacy

[branch "master"]
        remote = origin
        merge = refs/heads/legacy

```
