# m5core2-clock

Simple UIFlow clock with weather and moon phases for M5Core2.

Created to teach myself M5 UIFlow.

Demonstrates advanced UIFlow features.

## Features

 * NTP date sync
 * Use OpenWeather API
 * Display (approximate) moon phases
 * Screen dim after 15 sec
 * Press A to re-synchronize NTP

## Usage

Open in [UIFlow](https://flow.m5stack.com/).

Enter a valid [OpenWeatherMap](https://openweathermap.org/) API key and setup your location.

![](https://raw.githubusercontent.com/sixty-nine/m5core2-clock/main/apikey.png)

Run.

## Limitations

There are hard-coded stuff that could annoy you:

 * Units are metric
 * Date format is d-m-y
 * Time format is 24:00
 * Uses EU NTP server

## Credits

 * Moon phase images from [unicode-table.com](https://unicode-table.com/en/sets/moon/)
 * [Original moon phase algorithm](http://www.voidware.com/moon_phase.htm)
