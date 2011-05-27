## gnome-shell-extension-weather

gnome-shell-extension-weather is a simple extension for displaying weather notifications in Gnome Shell.

Currently, the weather report including forecast for today and tomorrow is fetched from [Yahoo](http://weather.yahoo.com/).

### Screenshot

![Screenshot](https://github.com/simon04/gnome-shell-extension-weather/raw/master/screenshot.png)

### Installation

1. Change `YAHOO_ID` to your location in extension.js (cf. [WOEID](http://developer.yahoo.com/geo/geoplanet/guide/concepts.html))
2. Put directory `weather@venemo.com/` in `~/.local/share/gnome-shell/extensions/
3. Put files 'downloader.class' and 'runme'`in ~/.icons/
4. Open a terminal and run the following commands
      $cd ~/.icons
      $sh runme
5. If you'd like the map automatic to update create a cronjob to run '$sh runme' daily 
6. Restart Gnome Shell (`[Alt]+[F2]`, `r`)
7. Enjoy, contribute, ...

### Licence

Copyright (C) 2011
Timur Kristóf <venemo@msn.com>,
Elad Alfassa <elad@fedoraproject.org>,
Simon Legner <Simon.Legner@gmail.com>,
Zach Tomkoski <hello.zt@gmail.com>

This file is a modified version of gnome-shell-extension-weather.  I have added a forecast image to the bottom of the file. It's not the cleanest install and hopefully someone has plans that may help improve it to integrate it better. 

gnome-shell-extension-weather is free software: you can redistribute it and/or modify it under the terms of the **GNU General Public License as published by the Free Software Foundation, either version 3** of the License, or (at your option) any later version.

gnome-shell-extension-weather is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with gnome-shell-extension-weather.  If not, see <http://www.gnu.org/licenses/>.

