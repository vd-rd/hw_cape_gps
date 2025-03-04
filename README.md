## Overview
Designed for accurate positioning inside embedded projects, this GPS cape offers extended telemetry information, as well as multiple choices for antenna type and placing as well as SoC options.
 The module is designed to accept either:
  - Fibocom GTS-4E-60 (tested)
  - Simcom SIM-28
  - uBlox Neo-M6/7/8
 Regarding connectivity options, the module can be equipped with either an active or passive antenna, connected via a standard u.Fl connector or placed on the carrier PCB.
Detailed information about positioning capabilities of the module can be found in the [GPS](/doc/gps.md) page.

### Project notes
Current development is on the master branch. Earlier revisions have been moved on the archive branch.

### Resources
You can find all necesary information to build or evaluate the module here:
   - [View 3D board render](https://a360.co/2DnqBSM)
   - [Fabrication files](https://github.com/vd-rd/hw_cape_gps/releases)
 
## Features
 - Low power consumption (<30mA)
 - Board can be placed in a true shutdown state (<20uA)
 - Extended temperature range of operation (-40C - 85)
 Detailed information about technical capabilities of the module can be found in the [hardware description](/docs/hardware.md) page.

## Telemetry data
 The module is able to provide standard NMEA sentences on a UART interface. Supported sentences:
 - $GPGGA - Time, position and fix type data
 - $GPGSA - GPS receiver operating mode, satellites used in the position solution, and DOP values
 - $GPGSV - Number of GPS satellites in view satellite ID numbers, elevation, azimuth, & SNR values
 - $GPRMC - Time, date, position, course and speed data
Detailed information about the sentences and parameters can be found in [telemetry](/docs/telemetry.md) page.

## Production
 The module is designed on a 40x40mm double layer PCB, with components placed on a single side for easy assembly.
 The total height of the module (without connectors mounted) is 3mm without the passive antenna mounted and 10mm otherwise.
 Detailed information about the stack-up, BOM and configuration options can be found on the [manufacturing](/docs/manufacturing.md) page.
