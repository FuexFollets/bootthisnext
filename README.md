# bootthisnext
Changes the next boot the current boot. Utilizes efibootmgr.

# Usage
The scirpt `./bootthisnext` can be moved to anywhere located in `$PATH` (reccomended `/usr/local/bin`)
It is run wihtout parameters and requires root user. The current boot represented as a 4-digit hexidecimal integer will then be shown and there will be a Y/n prompt if this shold be set as the next boot. Only if the answer Y is provided will the boot be set to the current boot.
