
> Open this page at [https://ondrejseman.github.io/pxt-lcd-display/](https://ondrejseman.github.io/pxt-lcd-display/)

This is simple TFT LCD Display Library, copied from [https://github.com/joy-it/pxt-rb-tft1.8]

## Wiring
| RB-TFT1.8     | Micro:bit     |
| ------------- |:-------------:|
| VCC           | 3V            |
| GND           | GND           |
| SCL/SCK       | P13           |
| SDA           | P15           |
| RS/DC/A0      | P1            |
| RES/RESET     | 3V            |
| CS            | P0            |
| LED           | 3V            |

There are a few

## Changes/Additional features
- changed wiring of the display: CS was on P16, but this PIN ist not usable on Elecfreaks Wukong board, so I changed it to P0. In future I plan to make this configurable
- new function to set orientation of the display
- faster SPI clock setting
  
## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/ondrejseman/pxt-lcd-display** and import

## Edit this project

To edit this repository in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/ondrejseman/pxt-lcd-display** and click import

#### Metadata (used for search, rendering)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
