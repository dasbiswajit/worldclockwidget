
World Clock & Weather
=====================

**This is active project maintained repository!**

A simple application to display the local time and current weather conditions in places all over the world.
It comes with two home screen widgets which show weather and time or time only.

.. image:: https://travis-ci.org/dasbiswajit/worldclockwidget.svg?branch=master
    :target: https://travis-ci.org/dasbiswajit/worldclockwidget



Features
--------

* Generate own api key via signup. Process described at Settings -> GENERAL -> !!!Important!!!
* Show local time and weather conditions in more than 4000 places.
* Add your own places: Add a place in the same time zone and change its name and coordinates to your desired location to show the actual weather condition there!
* A compact clock widget, displaying the local time in your favorite locations.
* A widget showing the time and weather, which is re-sizable to show multiple locations on the home screen.
* Simple and clean UI
* Customizable widget colors (including transparent background)

The Internet connectivity permission is **only** used to retrieve current weather conditions.

Download
--------

 `F-Droid <https://f-droid.org/repository/browse/?fdid=ch.corten.aha.worldclock>`_.
 `Google Play <https://play.google.com/store/apps/details?id=ch.corten.aha.worldclock>`_.


Screenshots
-----------
`wiki/Screenshots <https://github.com/dasbiswajit/worldclockwidget/wiki/Screenshots>`_

Building
--------

We use `Gradle <http://www.gradle.org/>`__.
Run ``./gradlew assembleDebug`` to create a debug build or ``./gradlew assembleRelease`` to create a release build.

OpenWeatherMap API key
######################

Using the OpenWeatherMap API requires an API key. A default key is stored in the file ``./worldclockwidget/default_owm_api_key``. It can be overwritten by setting the Gradle project property ``owmApiKey``.
It is recomended that you shoould generate your own API key. Process described at Application Settings -> GENERAL -> !!!Important!!!

Libraries
---------

The app uses and includes the following libraries:

* `ActionBarSherlock <http://actionbarsherlock.com/>`_ (also on `GitHub <https://github.com/JakeWharton/ActionBarSherlock>`__)
* `ColorPickerPreference <https://github.com/attenzione/android-ColorPickerPreference>`_
* `google-gson <https://code.google.com/p/google-gson/>`_
* `joda-time-android <https://github.com/dlew/joda-time-android>`_

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
along with this program.  If not, see `gnu <http://www.gnu.org/licenses/>`__.
