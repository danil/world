# Gentoo worlds

# Firmware

## Installed

### h9

* sys-firmware/iwl7260-ucode         wifi
* sys-firmware/nvidia-firmware       kernel and mesa firmware for nouveau video acceleration

### h10

* sys-kernel/linux-firmware          wifi

## Uninstalled

* sys-firmware/iwl5000-ucode         wifi

# Server

## Installed

* app-text/dos2unix
* dev-util/icdiff                    two columns diff
* mail-mta/exim                      deliver local mail to /var/mail
* net-mail/mailutils                 read local mail from /var/mail
* net-misc/tlsdate                   ntp replacement
* sys-apps/lsb-release               release version compliant to Linux Standard Base (LSB)

### h2

* app-admin/apache-tools

## On demand

* app-misc/reptyr                    move running program to tmux <https://github.com/nelhage/reptyr>
* app-text/catdoc                    convert doc, xls, ppt and rtf files to text
* app-text/convmv                    convert filenames to utf8
* app-text/sloccount
* dev-perl/rename                    rename files by regexp <http://stackoverflow.com/questions/2709458/bash-script-to-replace-spaces-in-file-names#2709619>
* dev-util/indent                    reformats c/c++ indentation
* mail-client/mutt
* media-gfx/openscad                 3D printer modeller
* net-analyzer/masscan               port scanner <https://github.com/robertdavidgraham/masscan>
* net-mail/notmuch                   mail indexer <http://notmuchmail.org>
* net-misc/wrk                       HTTP benchmarking <https://github.com/wg/wrk>
* sys-apps/hdparm                    SSD TRIM verify <https://wiki.archlinux.org/index.php/Solid_State_Drives#Verify_TRIM_Support>
* sys-apps/iproute2
* sys-apps/pciutils                  lspci <https://www.gentoo.org/doc/en/handbook/handbook-amd64.xml?style=printable&part=1&chap=7#doc_chap2>
* sys-apps/usbutils                  lsusb
* sys-power/powertop
* sys-process/atop
* sys-process/iotop

### Ruby on Rails

* app-misc/sphinx
* dev-db/mariadb
* media-gfx/imagemagick
* www-client/phantomjs

## Uninstalled

* dev-db/sqlite                      used by feed2email ruby gem

# Desktop

## Installed

* app-dicts/aspell-*                 emacs spell checker
* app-misc/cv                        progress bar for cp, rm, dd, ... <https://github.com/Xfennec/cv>
* app-misc/jq                        json console formater <http://stedolan.github.io/jq/tutorial>, <http://stackoverflow.com/questions/352098/how-can-i-pretty-print-json#15231463>
* dev-libs/libyaml                   required by RVM
* dev-util/source-highlight          highlighted source code in less
* dev-util/source-highlight          less filter
* gnome-extra/connman-gnome          wifi tray icon
* media-fonts/fantasque-sans         fantastic monospace font
* media-fonts/fira-sans              thin sans font
* media-fonts/libertine-ttf          sans-serif font used by Wikipedia
* media-fonts/terminus-font          used in console (ter-v16n)
* media-gfx/gimp
* media-gfx/pngcrush                 PNG image size optimizing <http://en.wikipedia.org/wiki/Pngcrush>
* media-gfx/ristretto                xfce image viewer <https://wiki.xfce.org/recommendedapps#ristretto>, <http://www.ohloh.net/p/ristretto>
* media-gfx/wkhtmltopdf              html to pdf converter
* media-sound/sox                    `play` audio files from cli
* media-video/mpv                    mplayer replacement <https://github.com/mpv-player/mpv>
* net-dns/bind-tools                 `dig`, `host` and `nslookup`
* net-misc/httpie                    curl replacement <http://httpie.org>
* net-misc/seafile-client            dropbox replacement
* net-proxy/torsocks                 torify (tor wraper) will fail if you do not have torsocks installed <http://wiki.gentoo.org/wiki/Tor#Torify>
* net-wireless/bluez                 /etc/init.d/bluetooth start <http://wiki.gentoo.org/wiki/Bluetooth#Boot_service>
* net-wireless/rfkill                enabled bluetooth <http://wiki.gentoo.org/wiki/Bluetooth#Software>
* sci-mathematics/genius             console-based calculator
* sys-apps/mdp                       markdown presentation tool
* sys-devel/bc                       used by bash prompt
* sys-fs/gt5                         baobab replacement; diskspace usage <http://gt5.sourceforge.net>
* sys-power/hibernate-script         `hibernate` and `hibernate-ram` s3 aka suspend to ram aka sleep
* sys-process/glances                htop replacement <https://github.com/nicolargo/glances>
* x11-apps/wmutils                   get active window `pfw` and kill it `killw` <https://github.com/wmutils/core> 
* x11-apps/xbacklight                screen backlight <https://wiki.archlinux.org/index.php/backlight#xbacklight>
* x11-apps/xev
* x11-apps/xrandr                    enable/disable external monitor
* x11-misc/cdm                       starting x11 <https://wiki.archlinux.org/index.php/CDM>
* x11-misc/dex                       execute commands on window manager startup <http://superuser.com/questions/130242/how-can-i-execute-commands-on-startup-in-awesome#326626>
* x11-misc/dunst                     minimalistic notification daemon (notify-osd from canonical replace) <http://knopwob.org/dunst>, <http://github.com/knopwob/dunst>, <https://wiki.archlinux.org/index.php/Desktop_notifications#Standalone>
* x11-misc/dzen                      status bar
* x11-misc/i3lock                    xscreensaver replacement
* x11-misc/i3status                  generate status for dzen2 status bar
* x11-misc/skippy-xd                 ala compiz scale (osx expose) <https://github.com/richardgv/skippy-xd>, <https://code.google.com/p/skippy-xd>
* x11-misc/unclutter                 hide mouse cursor after while <https://wiki.archlinux.org/index.php/unclutter>
* x11-misc/wmctrl                    show desktop and more <http://rox.sourceforge.net/desktop/book/export/html/188.html>
* x11-misc/xautolock                 used by i3lock
* x11-misc/xclip                     tmux and xorg clipboard integration <https://github.com/tmux-plugins/tmux-yank#linux-requirements>
* x11-misc/xdotool                   simulate keyboard input in xchainkeys
* x11-misc/xsel                      copy selection in termina to the xorg clipboard (used by emacs and urxvt) <https://wiki.archlinux.org/index.php/rxvt-unicode#Automatic_Script_Management>
* x11-misc/xxkb                      keyboard layout indicator for tray
* x11-themes/sound-theme-freedesktop my 'complete' sound
* xfce-extra/tumbler                 thumbnails generator for thunar and ristretto <https://wiki.archlinux.org/index.php/thunar#Plugins_and_addons>, <http://www.ohloh.net/p/tumbler>
* xfce-extra/xfce4-genmon-plugin     load average in xfce panel <http://goodies.xfce.org/projects/panel-plugins/start#xfce4-genmon-plugin>
* xfce-extra/xfce4-screenshooter     screen capture <https://wiki.archlinux.org/index.php/Taking_a_screenshot>

## On demand

* media-gfx/argyllcms                load icc/icm display color profiles <https://wiki.archlinux.org/index.php/ICC_Profiles#Argyll_CMS>
* media-libs/hal-flash               drm video support <https://github.com/cshorler/hal-flash>
* media-tv/popcorntime               torrent video player
* net-irc/weechat
* x11-apps/mesa-progs                `glxgears` opengl frames per second (fps) benchmark
* x11-apps/xdpyinfo                  show dpi
* x11-misc/xcalib                    load icc/icm display color profiles (only calibration curves) <https://wiki.archlinux.org/index.php/ICC_Profiles#xcalib>

## Xfce

x11-themes/gtk-engines-xfce:0
x11-themes/hicolor-icon-theme
xfce-base/xfce4-appfinder
xfce-base/xfce4-session
xfce-base/xfce4-settings
xfce-base/xfdesktop
xfce-base/xfwm4

## Uninstalled

* app-text/mupdf                     pdf viewer recommended by xfce (unfortunately there is no toc) <https://wiki.xfce.org/recommendedapps#mupdf>
* lxqt-base/lxqt-powermanagement     stand alone power manager
* net-misc/connman-ui                wifi tray icon
* x11-apps/xdm                       starting slim display manager <http://wiki.gentoo.org/wiki/SLiM#OpenRC>
* x11-misc/parcellite                copy and paste between xorg and terminal clipboard
* x11-misc/tint2                     does not work in stumpwm <https://code.google.com/p/tint2/issues/detail?id=157>
* xfce-extra/xfce4-power-manager

# License

Copyright (C) 2014 Danil Kutkevich <danil@kutkevich.org>  
See the `LICENSE` file for license rights and limitations (MIT)
