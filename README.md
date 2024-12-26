# Axon Fleet 3 OBS

## Author
- [**Wyatt Johnson**](https://github.com/realendie)

## Table of Contents

- [About](#about)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)

## About

A fork of [MrGriefs FiveM Axon Body 3 OBS](https://github.com/TFNRP/axonbody3-obs) made to work look like an Axoon Fleet 3 system.  
[Axon Fleet 3 OBS](https://github.com/realendie/axonbody3-obs/tree/Axon-Fleet-3) is out of the box and requires no dependencies.

## Installation

No special installation or dependencies required.  
Clone from Git or [download manually](https://github.com/realendie/axonbody3-obs/releases/tag/v1.0.0).  

```bash
$ git clone https://github.com/realendie/axonbody3-obs
```

## Usage

1. Create a new Browser Source Component (Right Click in Preview -> `Add` -> `Browser`).

1. Check `Local file`, click `Browse` and locate `index.html` from the directory you donwloaded [Axon Fleet 3 OBS](https://github.com/realendie/axonbody3-obs/releases/tag/v1.0.0).  
1. Select `Properties` configure `Width` and `Height` to your Canvas resolution (usually 1920 by 1080).  
1. Click `OK`. Now you should have a functioning Axon Fleet 3 overlay in OBS.  

## Configuration

We also supply a `config.js` for further ehancement:  

- `CustomCameraId`: If you'd like to use a custom id for the overlay. It will replace the randomly generated id.  
- `ForceUTCTimeZoneOffset`: Can be `false` or a numebr. Setting this to a number will override the UTC offset instead of using your current UTC offset.  
- `CalculateDaylightSavingsTime`: Can be `true` or `false`. Setting this to `true` will make the overlay advance an hour ahead during [Daylight Saving Time](https://en.wikipedia.org/wiki/Daylight_saving_time).  
- `BeepVolume`: Can be a number. This will determine the volume of interval beeps, which occur every two minutes. Set this to `0` if you do not want beeping.  
