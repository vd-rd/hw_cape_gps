# GPS cape 
The cape can be viewed in the current version at https://a360.co/2DnqBSM
<iframe src="https://myhub.autodesk360.com/ue2949173/shares/public/SH7f1edQT22b515c761ec892ef97e15452c9?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

## Description
 Designed for accurate positioning inside embedded projects, this GPS cape offers extended telemetry information, as well as multiple choices for antenna type and placing as well as SoC options.
 The module is designed to accept either:
  - Fibocom GTS-4E-60 (tested)
  - Simcom SIM-28
  - uBlox Neo-M6/7/8
 Regarding connectivity options, the module can be equipped with either an active or passive antenna, connected via a standard u.Fl connector or placed on the carrier PCB.
Detailed information about positioning capabilities of the module can be found in the [GPS](/doc/gps.md) page.

## Features
 - Low power consumption (<30mA)
 - Board can be placed in a true shutdown state (<20uA)
 - Extended temperature range of operation (-40C - 85)
 Detailed information about technical capabilities of the module can be found in the [hardware description](/doc/hardware.md) page.

## Telemetry data
 The module is able to provide standard NMEA sentences on a UART interface. Supported sentences:
 - $GPGGA - Time, position and fix type data
 - $GPGSA - GPS receiver operating mode, satellites used in the position solution, and DOP values
 - $GPGSV - Number of GPS satellites in view satellite ID numbers, elevation, azimuth, & SNR values
 - $GPRMC - Time, date, position, course and speed data
Detailed information about the sentences and parameters can be found in [telemetry](/doc/telemetry.md) page.

## Production
 The module is designed on a 40x40mm double layer PCB, with components placed on a single side for easy assembly.
 The total height of the module (without connectors mounted) is 3mm without the passive antenna mounted and 10mm otherwise.
 Detailed information about the stack-up, BOM and configuration options can be found on the [manufacturing](/doc/manufacturing.md) page.