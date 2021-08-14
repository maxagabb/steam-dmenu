# steam-dmenu

I don't like having python installed so this has been ported to a semi-posix compliant shell script (requires xdg-open and sed)
the diffrance between this and the original script is that this can be used to export/import a minimal version of the steam game manifest(which you can modify in case you don't wan't tools/ proton showing up)

### Simple usage example:

`steam_dmenu.sh -d 'bemenu -i'`

### Using exported game manifest

`steam_dmenu.sh -o > games`
`cat games | steam_dmenu.sh -d 'bemenu -i'`
