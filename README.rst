
World Clock & Weather (This is maintained repository!)
======================================================================


A simple application to display the local time and current weather conditions in places all over the world.
It comes with two home screen widgets which show weather and time or time only.

.. image:: https://travis-ci.org/dasbiswajit/worldclockwidget.svg?branch=master
    :target: https://travis-ci.org/dasbiswajit/worldclockwidget

Download
--------

.. image:: https://gitlab.com/fdroid/artwork/raw/master/badge/get-it-on.png
    :target: https://f-droid.org/repository/browse/?fdid=ch.corten.aha.worldclock
    
.. image:: https://images-na.ssl-images-amazon.com/images/G/01/mobile-apps/devportal2/res/images/amazon-appstore-badge-english-white.png
    :target: https://www.amazon.com/gp/product/B07HJVH3MW/ref=Biswajit-Das-World-Weather-Widget

OpenWeatherMap API key(Only on Fdroid version)
######################

**Fdroid version requires an API key**.

`fdroid key update problem <https://forum.f-droid.org/t/hide-key-and-credentials/4972>`_

Check wiki(https://github.com/dasbiswajit/worldclockwidget/wiki) for details. 


Features
--------

* Show local time and weather conditions in more than 4000 places.
* Add your own places: Add a place in the same time zone and change its name and coordinates to your desired location to show the actual weather condition there!
* A compact clock widget, displaying the local time in your favorite locations.
* A widget showing the time and weather, which is re-sizable to show multiple locations on the home screen.
* Simple and clean UI
* Customizable widget colors (including transparent background)
* Auto detect location (Google play version only)

Permissions
-----------

* The Internet connectivity permission is **only** used to retrieve current weather conditions. 
* Google Play version required GPS for detecting your location automatically.


Screenshots
-----------
`wiki/Screenshots <https://github.com/dasbiswajit/worldclockwidget/wiki/Screenshots>`_

Building
--------

We use `Gradle <http://www.gradle.org/>`__.
Run ``./gradlew assembleDebug`` to create a debug build or ``./gradlew assembleRelease`` to create a release build.


Libraries
---------

The app uses and includes the following libraries:

* `ActionBarSherlock <http://actionbarsherlock.com/>`_ (also on `GitHub <https://github.com/JakeWharton/ActionBarSherlock>`__)
* `ColorPickerPreference <https://github.com/attenzione/android-ColorPickerPreference>`_
* `google-gson <https://code.google.com/p/google-gson/>`_
* `Time4A <https://github.com/MenoData/Time4A>`_

Acknowledgements
----------------

* Special Thanks to `Armin <https://github.com/arminha/>`_ for earlier maintanence.
* Special thanks to `vyick <http://vyick.wordpress.com/>`_ for beta testing and feature suggestions!
* Weather data is provided by `Open Weather Map <https://openweathermap.org/>`_.
* The weather icons are based on `Meteocons <http://www.alessioatzeni.com/meteocons/>`_ from Alessio Atzeni.
* Time zone and geographical data is provided by `GeoNames <http://www.geonames.org/>`_.


License
----------------
World Clock & Weather

**Prohibited for commercial use!!**

* Copyright (C) 2018 Biswajit Das
* Copyright (C) 2014  Armin Häberling

This program is free software: you can use as referance 
under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version. You must recieve a concert 
from the above developers

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program also from the auther.
