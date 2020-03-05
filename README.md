# Apple LED Cinema Display
Pinout for the Apple LED Cinema Displays, for use to create a cable to replace any damaged originals.

## Supported Hardware
Apple LED Cinema Display 24" (A1267)
Apple LED Cinema Display 27" (A1316)

# Pinouts
Pinouts for the cable is as follows:

## LVDS (Sink-Side)
* Needs pinout detailed, WIP

## Mini DisplayPort ( Source-Side )
Pinning | Purpose | Wire Color
:-: | :-: | :-:
Pin 1 | Ground ⏚ | Cyan Pair ( Shield )
Pin 2 | Hotplug | Green
Pin 3 | Lane 3 － | Cyan Pair
Pin 4 | ̶ ̶ ̶ ̶ | ̶ ̶ ̶ ̶ 
Pin 5 | Lane 3 ＋ | Cyan Pair
Pin 6 | ̶ ̶ ̶ ̶ | ̶ ̶ ̶ ̶ 
Pin 7 | ̶ ̶ ̶ ̶ | ̶ ̶ ̶ ̶ 
Pin 8 | ̶ ̶ ̶ ̶ | ̶ ̶ ̶ ̶ 
Pin 9 | Lane 1 ＋ | Silver Pair
Pin 10 | ̶ ̶ ̶ ̶ | ̶ ̶ ̶ ̶ 
Pin 11 | Lane 1 － | Silver Pair
Pin 12 | ̶ ̶ ̶ ̶ | ̶ ̶ ̶ ̶ 
Pin 13 | Ground ⏚ | Silver Pair ( Shield )
Pin 14 | Ground ⏚ | Magenta Pair ( Shield )
Pin 15 | ̶ ̶ ̶ ̶ | ̶ ̶ ̶ ̶ 
Pin 16 | Aux Lane ＋ | Magenta Pair
Pin 17 | ̶ ̶ ̶ ̶ | ̶ ̶ ̶ ̶ 
Pin 18 | Aux Lane － | Magenta Pair
Pin 19 | Ground ⏚ | Blue
Pin 20 | Power ＋ ( 3.3V / 500mA ) | Red
Shield | Ground ⏚ | Shield

  * Pins 1/13/14/19 MIGHT be pinned to Shield? (Needs clarification)

## Magsafe 1 (Source-Side)
Pinning | Purpose | Wire Color
:-: | :-: | :-:
Pin 1 | Ground ⏚ | Shield
Pin 2 | V ＋ ( 14.5V / 16.5V / 18.5V / 20V ) | White (Core)
Pin 3 | Charge Control | I2C Wire
Pin 4 | V ＋ ( 14.5V / 16.5V / 18.5V / 20V ) | White (Core)
Pin 5 | Ground ⏚ | Shield
Shield | Ground ⏚ | Shield

  * 14.5V for 45W
  * 16.5V for 60W
  * 18.5V for 85W
  * 20V for 85W
  * Pins 2/4 are PINNED together
  * Pins 1/5 are PINNED to Shield

## USB (Source-Side)
Pinning | Purpose | Wire Color
:-: | :-: | :-:
Pin 1 | Vʙᴜs ＋ ( 5V / 100mA ) | Red
Pin 2 | Data － | Silver
Pin 3 | Data ＋ | Green
Pin 4 | Ground ⏚ | Black
Shield | Ground ⏚ | Shield

  * Pin 4 is NOT pinned to Shield
