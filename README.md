Gentoo world
============

My Gentoo world.

Installed
---------

* app-dicts/aspell-*                 emacs spell checker
* app-misc/cv                        Linux tool to show progress for cp, rm, dd, ... <https://github.com/Xfennec/cv>
* app-misc/jq                        json console formater <http://stedolan.github.io/jq/tutorial>, <http://stackoverflow.com/questions/352098/how-can-i-pretty-print-json#15231463>
* media-fonts/fantasque-sans         fantastic monospace font
* media-fonts/fira-sans              thin sans font
* media-fonts/libertine-ttf          sans-serif font used by Wikipedia
* media-fonts/terminus-font          user in console (ter-v16n)
* media-gfx/argyllcms                fix t400s default display colors <https://wiki.archlinux.org/index.php/ICC_Profiles#Argyll_CMS>
* media-gfx/pngcrush                 PNG image size optimizing <http://en.wikipedia.org/wiki/Pngcrush>
* media-gfx/ristretto                xfce image viewer <https://wiki.xfce.org/recommendedapps#ristretto>, <http://www.ohloh.net/p/ristretto>
* media-sound/sox                    `play` audio files from cli
* media-video/mpv                    mplayer replacement <https://github.com/mpv-player/mpv>
* net-dns/bind-tools                 `dig`, `host` and `nslookup`
* net-misc/httpie                    curl replacement <http://httpie.org>
* net-proxy/torsocks                 torify (tor wraper) will fail if you do not have torsocks installed <http://wiki.gentoo.org/wiki/Tor#Torify>
* net-wireless/bluez                 /etc/init.d/bluetooth start <http://wiki.gentoo.org/wiki/Bluetooth#Boot_service>
* net-wireless/rfkill                enabled bluetooth <http://wiki.gentoo.org/wiki/Bluetooth#Software>
* sys-fs/gt5                         baobab replacement; diskspace usage <http://gt5.sourceforge.net>
* sys-power/hibernate-script         `hibernate` and `hibernate-ram` s3 aka suspend to ram aka sleep
* sys-process/glances                htop replacement <https://github.com/nicolargo/glances>
* x11-apps/xdm                       starting slim display manager <http://wiki.gentoo.org/wiki/SLiM#OpenRC>
* x11-apps/xev
* x11-misc/dex                       execute commands on window manager startup <http://superuser.com/questions/130242/how-can-i-execute-commands-on-startup-in-awesome#326626>
* x11-misc/dunst                     minimalistic notification daemon (notify-osd from canonical replace) <http://knopwob.org/dunst>, <http://github.com/knopwob/dunst>, <https://wiki.archlinux.org/index.php/Desktop_notifications#Standalone>
* x11-misc/i3lock                    xscreensaver replacement
* x11-misc/parcellite                copy and paste between xorg and terminal clipboard
* x11-misc/skippy-xd                 ala compiz scale (osx expose) <https://github.com/richardgv/skippy-xd>, <https://code.google.com/p/skippy-xd>
* x11-misc/unclutter                 hide mouse cursor after while <https://wiki.archlinux.org/index.php/unclutter>
* x11-misc/wmctrl                    show desktop and more <http://rox.sourceforge.net/desktop/book/export/html/188.html>
* x11-misc/xautolock                 used by i3lock
* x11-misc/xclip                     tmux and xorg clipboard integration <https://github.com/tmux-plugins/tmux-yank#linux-requirements>
* x11-misc/xdotool                   simulate keyboard input in xchainkeys
* x11-misc/xsel                      copy selection in termina to the xorg clipboard <https://wiki.archlinux.org/index.php/rxvt-unicode#Automatic_Script_Management>
* x11-misc/xxkb                      keyboard layout indicator for tray
* x11-themes/sound-theme-freedesktop my 'complete' sound
* xfce-extra/tumbler                 thumbnails generator for thunar and ristretto <https://wiki.archlinux.org/index.php/thunar#Plugins_and_addons>, <http://www.ohloh.net/p/tumbler>
* xfce-extra/xfce4-genmon-plugin     load average in xfce panel <http://goodies.xfce.org/projects/panel-plugins/start#xfce4-genmon-plugin>
* xfce-extra/xfce4-screenshooter     screen capture <https://wiki.archlinux.org/index.php/Taking_a_screenshot>

On demand
---------

* app-admin/apache-tools
* app-text/convmv                    convert filenames to utf8
* app-text/dos2unix
* app-text/sloccount
* dev-perl/rename                    rename files by regexp <http://stackoverflow.com/questions/2709458/bash-script-to-replace-spaces-in-file-names#2709619>
* mail-client/mutt
* media-gfx/argyllcms                fix t400s default display colors <https://wiki.archlinux.org/index.php/ICC_Profiles#Argyll_CMS>
* media-gfx/gimp
* media-gfx/openscad                 3D printer modeller
* net-irc/weechat
* net-misc/wrk                       HTTP benchmarking <https://github.com/wg/wrk>
* x11-apps/mesa-progs                `glxgears` opengl frames per second (fps) benchmark
* x11-apps/xdpyinfo                  show dpi

Uninstalled
-----------

* app-text/mupdf                     pdf viewer recommended by xfce (unfortunately there is no toc) <https://wiki.xfce.org/recommendedapps#mupdf>
* x11-misc/i3status                  generates status bar for i3
* x11-misc/tint2                     does not work in stumpwm <https://code.google.com/p/tint2/issues/detail?id=157>

Copying
-------

Copyright (C) 2014 Danil Kutkevich <danil@kutkevich.org>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. See COPYING file.
If not, see <http://www.gnu.org/licenses/>.
