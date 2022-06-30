
# SHIP INFO
![image](https://user-images.githubusercontent.com/93654396/152546655-1ff442e4-1ae7-434b-bbdd-e1bbcb886ff9.png)

## INSTALLATION
Link core, databank, screen(s) and hub(s) in any order.
Configure max capacity for hubs linked

## DESCRIPTION
Various ship monitors and infos gathered in a single script. Uses LUA screen API.
Idea is to keep a strong focus on performances and provide lots of customization options.
support and feedback: https://discord.gg/BfnbtFyHrt

Features:
- Main screen with fuel tanks and hubs monitoring, tracks various weight info: container hubs, fuel, docked constructs and boarded players
- Repair screen to help finding damaged elements
- Docked construct screen to see and undock constructs
- Boarded players screen to see and unboard players
- Configuration screen
- Several themes to choose from, or you can create your own
- Touch screen, multi-screen
- Databank for persistance

![image](https://user-images.githubusercontent.com/93654396/148534290-fe6fad69-54af-4dc9-9dfb-1d578c011862.png)
![image](https://user-images.githubusercontent.com/93654396/148816214-c93df243-e73f-4ee8-b8f2-36b6d7978b81.png)
![image](https://user-images.githubusercontent.com/93654396/148828635-d335d96a-49cf-42af-b739-a87f0670adb7.png)

## ShipInfo Changelog

### v0.7
Updated for Mercury

### v0.69
Replaced getTime with getArkTime

Added an option to use tanks element labels instead of shortened names

Fixed repair screen not showing damaged elements

### v0.68
Fix attempt to active / inactive state

Reduced load when several screens plugged

### v0.67
Added tanks size in labels

### v0.66
Added an indicator when script is not running

### v0.65
Exit script when databank is out of range (previousy generated a script error)

### v0.64
Added onscreen info for damaged elements

Added screens activation on start

Removed autostop if too far

### v0.63
Fixed boarded players with empty names (now showing ID if name cannot be obtained)

### v0.62
Fixed script crash when changing theme

### v0.61
Code cleaning

Shortened / normalized tanks labels

Fixed layout option

### v0.6
Replaced "Configuration Screen" with "Theme Screen" and more customization options (layout still wip)

Databank should now store correctly configuration

### v0.51
Fixed starting error on undamaged ship

### v0.5
Repaired repair screen!

Added "Boarded Players Screen" to select and unboard players

Added databank (required on start)

Added "Configuration Screen", for now only with theme selection

minor UI updates

### v0.3
Added "Docked Contructs Screen" to select and undock constructs

minor UI updates

### v0.24
Repair screen: can now select damaged element shown with arrows

fixed arrows not cleared

minor UI updates

### v0.23
Repair screen should now work correctly

minor UI tweaks

### v0.22
updated repair screen

minor UI updates

added themes

### v0.21
added single hub screen

### v0.2
added repair screen

### v0.1
first version
