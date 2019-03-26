**Original software copyright of Fabien Loison.**


ALSA Tray Provides a systray icon and a command line interface for
setting the volume of the ALSA Mixers.


# Dependencies
- [Needed  ] [pyAlsaAudio](http://pyalsaaudio.sourceforge.net/)

- [Optional] [Python XDG](http://freedesktop.org/wiki/Software/pyxdg) (for finding the best place for the config file)

- [Optional] [PyGTK 2.x](http://pygtk.org/) (for having a systray icon)

- [Optional] [DBus Python](http://cgit.freedesktop.org/dbus/dbus-python/) (for the support of multimedia keys)

- [Optional] [HAL](http://www.freedesktop.org/wiki/Software/hal) (for the support of multimedia keys)

- [Optional] [pyNotify](http://www.galago-project.org/) (for the notifications)


Building dependencies:
* [Optional] GNU gettext <http://www.gnu.org/software/gettext/>


# Usage
Run `alsa-tray` for launching ALSA Tray in systray.

Run `alsa-tray --help` or `man alsa-tray` for help with CLI options.


# Install
To install ALSA Tray, run `./install.sh --install` as root.


# Uninstall
To uninstall ALSA Tray, run `./install.sh --remove` as root.
