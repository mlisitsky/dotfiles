# Matthew's GNU/Linux Dotfiles

There are my dotfiles! They are mainly based around the configs created by [Luke Smith](https://github.com/LukeSmithxyz)  to whom I am extremely grateful for creating his voidrice repository. I mainly use them on my Arch desktop, but they should be distro independent. That said, the main differences between my configs and Luke's at this point are additional shortcuts based around my machine's folder structure, so if you happen upon this, I recommend you to use Luke's configs as a starting point for your own, as this is mainly for my own reference/backup purposes. Additionally, the rest of this repo's description is, unless specified, taken from the description of Luke's voidrice repo, with minor changes to make sure that Luke is credited in the proper places.

## Programs whose configs can be found here

+ i3 (i3-gaps)
+ urxvt (rxvt-unicode) (although these files use [Luke's st build](https://github.com/lukesmithxyz/st) as the default terminal)
+ vim
+ bash
+ ranger
+ qutebrowser
+ ~~mutt/msmtp/offlineimap~~ Now moved to [LukeSmithxyz/mutt-wizard](https://github.com/LukeSmithxyz/mutt-wizard)
+ calcurse
+ ncmpcpp and mpd (my main music player)
+ Music on Console (moc and mocp as an alternative music player)
+ mpv (using the MPC-HC Keybinds for MPV by (dragons4life)[https://github.com/dragons4life/MPC-HC-config-for-MPV]
+ neofetch
+ compton (For transparency and to stop screen tearing)
+ And many little scripts I use

## More documentation

Check other config folders for more specific documentation.

[i3 guide and config](.config/i3/i3_guide.rmd)

[ranger configuration](.config/ranger/luke_ranger_readme.md)

[list of scripts in the `~/.scripts/ directory](.scripts/SCRIPTS.md)

## Dynamic Configuration Files

Store your favorite or high-traffic folders in `~/.config/Scripts/folders` or your most important config files in `~/.config/Scripts/configs` with keyboard shortcuts. When you add things to theses files my vimrc will automatically run `~/.config/Scripts/shortcuts.sh` which will dynamically generate shortcuts for these in bash, ranger and qutebrowser!

Check out more info at the main repo for this: [shortcut-sync](https://github.com/lukesmithxyz/shortcut-sync). You will really want to take advantage of this for an extremely efficient setup.

# "Dependencies" and programs used

The programs I use here are always changing, but luckily you can just look at the installation list for [LARBS](http://larbs.xyz) here:

+ [List of programs installed by LARBS, including optional packages](https://github.com/LukeSmithxyz/LARBS/blob/master/progs.csv)

For your info, if the second column is a capital letter, that means that it's *not* installed by default, only when the user specifically requests it. Those with lowercase letters are just for classification purposes. Don't think you have to install every package to get these dotfiles working of course, but this list is a *sufficient condition* for full functionality. If you run into an error running my dotfiles, chances are the package you need is there.

The only program not listed on that list is the one you have to install manually: [Luke's st build](https://github.com/lukesmithxyz/st), which is easy enough to install.
