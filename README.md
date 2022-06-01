# radioClicky

Bash script to play some radio streams.

## Install

1. Copy bin/radioClicky somewhere on path. 
1. Make sure that radioList is populated and to be found, by deafult "$HOME/.config/radioClicky/radiolist"
1. Optionaly copy flac samples to "$HOME/..config/radioClicky/sounds"

## Usage

    radioClicky --sysinfo
    radioClicky --help
    radioClicky --play

### Tint2 

Optionaly add to tint2 as executor (see --tint2 for example).  

### Openbox

Optionaly add to openbox menu.xml as pipemenu

    <separator/>
     <menu id="radio" label="radio" execute="radioClicky --openbox" />
    <separator/>
