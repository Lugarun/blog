


# Reinstalling arch due to hard drive update and change

/mnt/
/mnt/efi

pacstrap base linux linux-firmware kakoune



directory of packages:
- kakoune
- grub
- os-prober
- networkmanager
- sudo
- pkgstats
- pulse audio
- ncpamixer
- git
- aurutils
- stack
- xorg
- dmenu
- tmux
- firefox
- xournalpp
- pandoc
- docker
- steam
- zathura
- discord
- python
- nvidia


changed into insecure uefi boot so that it would load linux in uefi mode

enable pacache.timer

XMONAD
mkdir .xmonad
git clone xmonad, xmobar, xmonad-contrib
stack init
copy xmonad.hs from xmonad-git/man/
stack build
put exec xmonad in run-xmonad
add run-xmonad to xinitrc
chmod +x run-xmonad
stack install
startx

setup ssh keys and send to github

get my xmonad.hs from github: using the method here https://www.atlassian.com/git/tutorials/dotfiles

fonts:
source code pro and nofo:
- ttf-google-fonts-git
- noto-fonts-emoji
- noto-fonts-cjk

[wpgtk](https://www.youtube.com/watch?v=jmY5NEPI4RM)
- python-pip
- python-gobject
- feh
- imagemagick

test colors with
msgcat --color=test

wpg-install.sh -ig
- lxappearance
lxappearance set icon theme flattr color and widget to flatcolor

pip install wpgtk


password store
https://medium.com/@chasinglogic/the-definitive-guide-to-password-store-c337a8f023a1



auto mount
-udisks2
bashmount


- bash-completion

TODO
https://wiki.archlinux.org/index.php/Color_output_in_console#man
st
mopidy

