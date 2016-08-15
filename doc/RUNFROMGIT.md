# Run from git

## To run Nicotine+ from git master:

## GNU/Linux

* Install all the required dependencies:

    * On Redhat/Fedora based distributions:

    `sudo dnf install pygtk2 pygtk2-libglade python-mutagen`

    * On Debian/Ubuntu based distributions:

    `sudo apt-get install python-gtk2 python-glade2 python-mutagen`

* Check that the python version you are using is 2.7.X via `python -V`.

* In the git root folder run `python nicotine.py`.

### Windows

* Install all the required dependencies:

    * [Python 2.7.X](https://www.python.org/downloads/windows/) **(32bits version)**.
    * [GTK+ 2.24.X](https://sourceforge.net/projects/gtk-win/) (last sourceforge bundle).

      (will check if we can use [the hexchat build](https://github.com/hexchat/gtk-win32) which is more up to date)
    * [PyGTK 2.24.X](http://ftp.gnome.org/pub/GNOME/binaries/win32/pygtk/2.24/) **(will not found python install path if you're using python x86-64)**.
    * [mutagen](https://github.com/quodlibet/mutagen) via pip: `python.exe -m pip install mutagen`.


* Launch Nicotine+ either via:

    * Right click =>  'Open with' and find `python.exe` in `C:\Python27`.
    * From the git root folder run via cmd.exe or Powershell `python.exe nicotine.py`.

#### Optional dependencies

* On Redhat/Fedora based distros:

    `sudo dnf install notify-python python-GeoIP python-miniupnpc`

* On Debian/Ubuntu based distros:

    `sudo apt-get install python-notify python-geoip python-miniupnpc`

* On Windows: I'm working on it :)