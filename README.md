## Firefox-Updater

An Android app to install and/or update Firefox for Android on your device, without using the Google Play Store.

Shows the currently installed Firefox version (if available) and allows to query Mozilla's [releases directory site](https://archive.mozilla.org/pub/mobile/releases/) for the latest Firefox for Android release. It also lets a user start downloading the latest release version.

Currently the app is an activity with a two-button GUI. Checks for and displays the most current available version when
the "Check available version"-button is tapped. The "Download Firefox" button starts an intent to download the last version
from a URL described in Mozilla's [README.txt](https://archive.mozilla.org/pub/mobile/releases/latest/README.txt). However, the plan is to move this to an Android service to perform periodical update checks and download/install from within the app itself.

## History

Since Mozilla [shut down their FTP server on 2015-08-05](https://blog.mozilla.org/it/2015/07/27/product-delivery-migration-what-is-changing-when-its-changing-and-the-impacts/), non-playstore updates of Firefox have to be done by third-party apps such as this one.

There is a ticket about non-playstore updates with Mozilla:

https://bugzilla.mozilla.org/show_bug.cgi?id=1192279

Another related issue is tracker at:

https://bugzilla.mozilla.org/show_bug.cgi?id=1220773

Mozilla now uses a uniform URL to point to the latest release, see

https://archive.mozilla.org/pub/mobile/releases/latest/README.txt
https://download.mozilla.org/?product=fennec-latest&os=android&lang=multi

## License

FFUpdater -- a simple Android app to update Firefox.
Copyright (C) 2015 Boris Kraut <krt@nurfuerspam.de>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see <http://www.gnu.org/licenses/>.
