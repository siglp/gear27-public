# Gear27

[Czech version (Česká verze)](https://github.com/siglp/gear27-public/blob/main/README-CZ.md)

## Data field for Garmin

If you like this field please rate it!

Gear27 is data field for Garmin. It is used for showing and recording data from shifting sensor.

The goal of this field is to be customizable. You can choose, what values are important for you and let them show. For example, if you want to see just rear gear index, you can disable other data (gear sizes, label etc.).

It is tested on SRAM AXS shifting and real Garmin devices Fenix 5x Plus, Fenix 7x Pro and Edge MTB.

## Settings
- #### Background color
    - Define background color or let device choose automatically (B&W displays has only Black and White colors)
        - Automatic
        - White
        - Light Gray 
        - Dark Gray
        - Black
        - Red
        - Dark Red
        - Orange
        - Yelllow
        - Green
        - Dark Green
        - Blue
        - Dark Blue
        - Purple
        - Pink
- #### Foreground color
    - Define font color or let device choose automatically (B&W displays has only Black and White colors)
        - Automatic
        - White
        - Light Gray 
        - Dark Gray
        - Black
        - Red
        - Dark Red
        - Orange
        - Yelllow
        - Green
        - Dark Green
        - Blue
        - Dark Blue
        - Purple
        - Pink
- #### F./R. separator
    - Char used between values
        - Slash ' / '
        - Hyphen ' - '
        - Colon ' : '
        - Space '   '
- #### Show space in value
    - Show space between chars and separator in value
       - Yes / No
- #### Main value
    - Which value will be shown in data field as main
        - Gear Index
        - Gear Size
- #### Second value (smaller)
    - Which value will be shown in data field as second (smaller)
        - Gear Index
        - Gear Size
- #### Show label (if possible)
    - Show label in data field if it is possible according to size of the field
        - Yes / No
- #### Show second value (if possible)
    - Show also second value in data field if it is possible according to size of the field
        - Yes / No
- #### Show front value
    - Show actual front value in data field
       - Yes / No
- #### Show rear value
    - Show actual rear value in data field
        - Yes / No
- #### Label position correction (x,y)
    - Correction of label position by +/- pixels on x-axis and +/- pixels on y-axis
    - Insert here count of pixels, which you needed correct position of label
        - always insert 2 values separated by comma, 0 means no correction
        - ex. 10,15: move by 10 pixels to the right and 15 pixels down
        - ex. -10,-15: move by 10 pixels to the left and 15 pixels up
- #### Main value position correction (x,y)
    - Correction of main value position by +/- pixels on x-axis and +/- pixels on y-axis
    - Insert here count of pixels, which you needed correct position of main value
        - always insert 2 values separated by comma, 0 means no correction
        - ex. 10,15: move by 10 pixels to the right and 15 pixels down
        - ex. -10,-15: move by 10 pixels to the left and 15 pixels up
- #### Second value position correction (x,y)
    - Correction of second value by +/- pixels on x-axis and +/- pixels on y-axis
    - Insert here count of pixels, which you needed correct position of second value
        - always insert 2 values separated by comma, 0 means no correction
        - ex. 10,15: move by 10 pixels to the right and 15 pixels down
        - ex. -10,-15: move by 10 pixels to the left and 15 pixels up
- #### Front gear index override
    - Insert here csv for your own front gear index definition
        - ex. normal bike order: 1,2,3
        - ex. reverse bike order: 3,2,1
        - not necessary to override all values
- #### Front gear size override
    - Insert here csv for your own front gear size definition
        - ex. (3 gears): 22,32,42
        - ex. (1 gear): 32
        - not necessary to override all values
- #### Rear gear index override
    - Insert here csv for your own front gear index definition
        - ex. normal bike order: 12,11,10,9,8,7,6,5,4,3,2,1
        - ex. reverse bike order: 1,2,3,4,5,6,7,8,9,10,11,12
        - not necessary to override all values
- #### Rear gear size override
    - Insert here csv for your own front gear size definition
        - ex. (SRAM 10-52): 52,42,36,32,28,24,21,18,16,14,12,10
        - not necessary to override all values, ex. 52 will override size only "for real index = 1", others will be taken from sensor
- #### Fix connection lost
    - If connection is lost, use last known values and not '-'
        - Yes / No

## Supported devices

### Full activity recording supported
Watches which should record lap fields and session usage of gears.

 - 	D2™ Mach 1
 - 	D2™ Mach 2 Pro
 - 	D2™ Mach 2
 - 	Descent™ Mk2 / Mk2i
 - 	Descent™ Mk2 S
 - 	Descent™ Mk3 43mm / Mk3i 43mm
 - 	Descent™ Mk3i 51mm
 - 	Edge® 1030 Plus
 - 	Edge® 1030
 - 	Edge® 1040 / 1040 Solar
 - 	Edge® 1050
 - 	Edge® 530
 - 	Edge® 540 / 540 Solar
 - 	Edge® 550
 - 	Edge® 830
 - 	Edge® 840 / 840 Solar
 - 	Edge® 850
 - 	Edge® MTB
 - 	Enduro™ 3
 - 	epix™ (Gen 2) / quatix® 7 Sapphire
 - 	epix™ Pro (Gen 2) 42mm
 - 	epix™ Pro (Gen 2) 47mm / quatix® 7 Pro
 - 	epix™ Pro (Gen 2) 51mm / D2™ Mach 1 Pro / tactix® 7 – AMOLED Edition
 - 	fēnix® 5 Plus
 - 	fēnix® 5S Plus
 - 	fēnix® 5X Plus
 - 	fēnix® 6 Pro / 6 Sapphire / 6 Pro Solar / 6 Pro Dual Power / quatix® 6
 - 	fēnix® 6S Pro / 6S Sapphire / 6S Pro Solar / 6S Pro Dual Power
 - 	fēnix® 6X Pro / 6X Sapphire / 6X Pro Solar / tactix® Delta Sapphire / Delta Solar / Delta Solar - Ballistics Edition / quatix® 6X / 6X Solar / 6X Dual Power
 - 	fēnix® 7 / quatix® 7
 - 	fēnix® 7 Pro - Solar Edition (no Wi-Fi)
 - 	fēnix® 7 Pro
 - 	fēnix® 7S Pro
 - 	fēnix® 7S
 - 	fēnix® 7X / tactix® 7 / quatix® 7X Solar / Enduro™ 2
 - 	fēnix® 7X Pro - Solar Edition (no Wi-Fi)
 - 	fēnix® 7X Pro
 - 	fēnix® 8 43mm
 - 	fēnix® 8 47mm / 51mm / tactix® 8 47mm / 51mm / quatix® 8 47mm / 51mm
 - 	fēnix® 8 Pro 47mm / 51mm / MicroLED / quatix® 8 Pro 47mm / 51mm
 - 	fēnix® 8 Solar 47mm
 - 	fēnix® 8 Solar 51mm / tactix® 8 Solar 51mm
 - 	fēnix® E
 - 	Forerunner® 745
 - 	Forerunner® 945 LTE
 - 	Forerunner® 945
 - 	Forerunner® 955 / Solar
 - 	Forerunner® 965
 - 	Forerunner® 970
 - 	MARQ® (Gen 2) Athlete / Adventurer / Captain / Golfer / Carbon Edition / Commander - Carbon Edition
 - 	MARQ® (Gen 2) Aviator
 - 	MARQ® Adventurer
 - 	MARQ® Athlete
 - 	MARQ® Aviator
 - 	MARQ® Captain / MARQ® Captain: American Magic Edition
 - 	MARQ® Commander
 - 	MARQ® Driver
 - 	MARQ® Expedition
 - 	MARQ® Golfer
 - 	Venu® 4 41mm
 - 	Venu® 4 45mm / D2™ Air X15
 - 	Venu® X1

### Not supported because of very small (32K) memory
Watches / devices with only 32K for field memory are NO MORE supported (from version 2.0.0). Please use **Gear27-32K** forked from 1.12.0 version.

- Enduro™
- fēnix® 6 / 6 Solar / 6 Dual Power
- fēnix® 6S / 6S Solar / 6S Dual Power

### Garmin Edge Explorer, Edge Explorer 2, Forerunner 1xx, 2xx, 6xx
The Garmin Edge Explorer, Garmin Edge Explorer 2, Forerunner 1xx, 2xx and 6xx doesn't support Shifting API, so field will NOT work and devices are NOT supported.

[//]: # (WIKI)

## Issues and proposals
You can report issues and proposals here: https://github.com/siglp/gear27-public/issues

Please always fill:
- Gear27 application version.
- Your garmin device type.
- Your phone device / type, if problem is in ConnectIQ or settings.

## Localization into another language
If there is someone who can and would like to help with translation into another language, it would help me a lot. Please contact me through the Garmin Connect IQ Store.

## Versions
### Released
- #### 2.1.0 - [ 10.7.2026 ]
    - Added total count of used gears into activity
    - Support for new device (D2 Mach 2 Pro)
    - Support for DEBUG of application (if needed)
    - Removed compatibility for devices which does not support shifting API according to manual (Edge Explore 2, Forerunner 1xx, 2xx, 5xx, 6xx, Instinct 3 etc.)
    - Moved project to GitHub
- #### 2.0.0 - [ 9.12.2025 ]
    - SW option to fix connection lost between device and gear (last known value is used)
    - Support for devices with only 32K array memory removed (Enduro, Fenix 6 / 6 Solar / 6 Dual Power, Fenix 6S / 6S Solar / 6S Dual Power, Forerunner 245, Forerunner 645, Instinct E 40mm, Instinct E 45mm, Instinct 3 Solar 45mm / 50mm). This limitation was no longer possible to circumvent and hindered further development of this field. For these devices please use Gear27-32K.
- #### 1.12.0 - [ 3.11.2025 ]
    - Support for new device (D2 Mach 2)
    - Changes in German translation (thanks to Tobias Fengels)
- #### 1.11.0 - [ 13.10.2025 ]
    - Support for new devices (Edge 550, Edge 850, quatix 8 47mm / 51 mm, Fenix 8 Pro 47mm / 51 mm / MicroLED, Instinct Crossover AMOLED, Venu 4 41mm / 51mm)
    - Possibility for correction of display position on screen
    - Added German (by AI)
- #### 1.10.0 - [ 19.6.2025 ]
    - Support for new devices (Edge MTB, Venu X1)
- #### 1.9.0 - [ 20.5.2025 ]
    - Support for new devices (Forerunner 570 42mm / 47mm, Forerunner 970)
- #### 1.8.0 - [ 12.5.2025 ]
    - Support for new devices (Descent G2, tactix 8 47mm / 51mm / Solar 51mm, Instinct 3 AMOLED 45mm / 50 mm / Solar 45mm / Solar 50mm, Instinct E 40mm / 45mm)
- #### 1.7.0 - [ 9.10.2024 ]
    - Support for new device (Enduro 3)
- #### 1.6.0 - [ 4.9.2024 ]
    - Support for new devices (Fenix 8 43mm / 47mm / 51mm / Solar 47mm / Solar 51mm, Fenix E)
- #### 1.5.0 - [ 26.7.2024 ]
    - Support for new devices (Descent Mk3/Mk3i 43mm/51mm, Edge 1050, Forerunner 165/165 Music, Fenix 7 Pro/7X Pro (no Wi-Fi))
- #### 1.4.0 - [ 28.7.2023 ]
    - Support for new devices (Epix2 42mm/47mm/51mm, Fenix 7 Pro/7s Pro/7x Pro)
- #### 1.3.0 - [ 3.5.2023 ]
    - Support for new devices (Edge 540/840, Forerunner 265/965)
- #### 1.2.1 - [ 28.3.2023 ]
    - Bugfix - Background color in dark mode
- #### 1.2.0 - [ 13.3.2023 ]
    - Bugfix - transparency and stats (again...).
- #### 1.1.0 - [ 6.3.2023 ]
    - Bugfix.
    - Added French (thanks to Anthony Humeau)
- #### 1.0.0 - [ 3.3.2023 ]
    - Bugfix
    - Possibility for showing / not showing space in value.
    - Possibility for define background and foreground colors.
    - Revision of supported devices (removed devices without Shifting API support, added new devices)
- #### 0.6.0 - [ 23.6.2022 ]
    - Count statistics for each gear (ex. how long it was used). For devices with field memory above 32K and some exceptions with only 32K.
    - Record statistics into activity.
    - Big code refactoring because of memory limits (especially for devices with field memory 32K)
- #### 0.5.0 - [ 8.6.2022 ]
    - Possibility for redefine gear size in field (some old watches does not provide 45+ rear gear size and on some it is not possible to define right size of front gear size).
    - Possibility for redefine gear index in field (smallest gear = 1 and not 12).
    - Support for most Garmin devices (according to simulator tests).    
- #### 0.4.0 - [ 3.6.2022 ]
    - Refactoring of problematic code on some real devices.
- #### 0.3.x (0.3.0 and 0.3.1) - [ 2.6.2022 ]
    - **WARNING** - there are problems with settings in this version on some real devices (Fenix5x, Fenix6). I am working on refactoring of parts, which should be responsible for it. Workaround is NOT changing default settings. Sorry for that...
- #### 0.3.1 - [ 2.6.2022 ]
    - Try to fix problem with showing / not showing label on some devices.
        - It is really try, because simulators, alfa version (sideload) and beta version (ConnectIQ) are working correctly...
- #### 0.3.0 - [ 2.6.2022 ]
    - **WARNING** - there were some changes in definition file for charts / graphs in activity, some older activities should be now represented not correctly.
    - Fix 1-8 field UI.
    - Possibility for selecting between gear index and gear size to show in field (or both).
    - Recording gear size into activity and show in graphs.
    - Record gear ratio into activity and show in graph.
- #### 0.2.0 - [ 23.5.2022 ]
    - Settings for field look.
    - Recording gear index into activity and show in graphs.
    - Support for 1-4 field UI on rounded watches.
- #### 0.1.0 - [ 22.5.2022 ]
    - Initial testing release - not public.

### Planned (future)
- #### 2.x.y ??? - [ ??? ]
    - ??? Bugfix.
    - ??? Possibility for define font size and align.
    - ??? Battery status.
    - ??? Maybe possibility to define, which data record and which not.
    - ??? Manual settings of GUI via Connect IQ.
    - ??? More proposals.
