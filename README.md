# radioClicky

Bash script to play some radio streams.

## Install

Copy bin/radioClicky somewhere on path. Optionaly copy flac samples to .config/radioClicky/sounds.

## Usage

    radioClicky --sysinfo
    radioClicky --help
    radioClicky --play

## Tint2 and Openbox

Optionaly add to tint2 as executor (see --tint2 for example). Optionaly add to openbox menu.xml as pipemenu

    <separator/>
     <menu id="radio" label="radio" execute="radioClicky --openbox" />
    <separator/>
