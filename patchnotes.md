## 3.0.0

- Only English from now on

I have recoded the whole tool and many bugs seem to be gone. No more settings reset or random crashes anymore.

Changes:

I also want to introduce a new feature of the Qzeng Client. The ESP Wallhack
This Hack draws 2d or 3d Boxes around selected players. Highlighting applies here too

- Added 3D Box Feature
- Added Show for same Faction Feature
- Added Show Name Feature
- Added Show Distance Feature
- Added Show HP Bar Feature

Also you now have the possibility to change the weather like you want. You are required to have precipitation effects option ticked for it to work.

- Added Weather changing

Also a big part of this update is the keybindingsystem. You can change keybinds in the keybind tab in the settings. This system is the start of more options which will base on these in the future like a custom mail system for example.

- Added Radar Toggle, Skeleton Debug, ESP Toggle and Settings Toggle Keybindings
- To change Keybinds just left click on the Keybinding in the Options

### Tool:
 - Removed Open Moorsradar Button
 - Removed whole Skybox section
 - Removed the skeleton hack/wallhack button

### DLL:
- Most tool is now in C

### Settings:
- They are now a .json rather than just a .cfg file
- Added way more features to the tool inside lotro and there are now more customizable 
- You can now define your own players to be highlighted on radar and esp
- Colorpicking is now way nicer, just click on the box and select the one you want

### Radar:
- Added an option for the radar to move with yourself and have you always facing to "north"
- The map is now also loading outside of the moors 
- CURRENTLY DUNGEONS ARE NOT WORKING, IF YOU NEED THIS WAIT TILL NEXT VERSION

### DEFAULT KEYBINDS:

Radar Toggle: Ctrl + F5
Skeleton Hack Toggle: Ctrl + F6
ESP Toggle: CTRL + F7
Settings Toggle: CTRL + F8

### Other Changes:
- Added Distance to the Target List and Hoverinfo

### Known Issues:

- Sometimes the map bugges out and shows you on the wrong landblock. This fixes itself once you walk to the next one
- Dungeons currently have no maps, the features of the radar are still working tho

## 2.5.7 - 15.08.2026

### Debugging

- Mehr Logging im Tool hinzugefuegt / Added more logging for debugging
- Ein ungenutzer Timer wurde geloescht / Deleted an unused timer

## 2.5.6 - 13.08.2026

### XML Export

- Der XML Export des Snapshot ist zurueck / The XML-Export feature is back

### UI

- Ich habe die luecke zwischen der untersten Karte und der Connected Leiste verkleinert/I have removed the big gap under the last card

## 2.5.5 - 12.08.2026

### Radar Settings

- Man kann jetzt Farben fuer Freep, Creep und Local Player auswaehlen / You can now select colors for Local Player, Freeps and Creeps

## 2.5.4 - 10.08.2026

### Lotro Debug

- Skeletonansicht/wallhack hinzugefuegt. Aktuell nur temporaere Implementation / Added a skeleton view/wallhack

## 2.5.3 - 09.08.2026

### Main Menu

- Bei Klick auf Discordprofil oeffnet sich Context Menu mit Optionen: Link zur Webseite, Zum Logfile und Logout / Clicking on the discord avatar will open a context strip with the options : link to website, link to logfile and logout

## 2.5.2 - 07.08.2026

### Radar

- Radar Alert sollte nicht mehr random kommen, sondern nurnoch wenn ein Target in range ist / Radar Alert should no longer happen randomly
- Targetvorschlaege werden nurnoch gegeben, wenn das Target auch in range ist (etwa 85m) / Targetsuggestions will only be shown if the target is in range (about 85m)

### Radar Settings:

- Radar Position sollte jetzt korrekt gespeichert werden / Radar position should now get saved correctly

### Skybox

- Es wird keine falsche Skybox mehr zu beginn gesetzt / There will no longer a wrong skybox get set at the start

## 2.5.1 - 06.08.2026

### Skybox

- Skyboxen sind jetzt alphabetisch sortiert / Skyboxes are now sorted alphabetically

### Radar Settings:

- Max Zoom wurde auf 1.0 erhoeht / Increased maximum zoom to 1.0
- Falls Settingsladen failed versucht er noch 49 weitere Male sie zu laden, um ein Reseten zu vermeiden / If loading the settings fails, the DLL will retry up to 49 additional times to prevent settings from being reset, as long as a settings file exists

# 2.5.0 - 05.08.2026

### Skybox

- Man kann jetzt eine Skybox auswaehlen / You can now change your skybox

## 2.4.6 - 04.08.2026

### Social Tab Data Transfer

- Delving of Fror Buffs werden jetzt an die Webseite geschickt / Delving of Fror Buffs will now get transfered to the website

## 2.4.5 - 04.08.2026

### Updater

- Updater tests

## 2.4.2 - 04.08.2026

### Updater

- Updater bugfixes
- Patchnotes sind jetzt lesbarer

## 2.4.1 - 04.08.2026

### Updater

- Neuer Updater
- Updates sind nicht mehr verpflichtend ausser ich kennzeichne sie als solche
- Patchnotes sind jetzt im Updatefenster einsehbar

## 2.4.0 - 04.08.2026

### Updater

- Neuer Updater
- Updates sind nicht mehr verpflichtend ausser ich kennzeichne sie als solche
- Patchnotes sind jetzt im Updatefenster einsehbar


## 2.3.1 - 31.07.2026

### DLL

- Haengenbleiben der Map sollte hoffentlich gefixt sein
- Reseten der Settings nach Update sollte nicht mehr passieren
- Ihr muesst einmal eure Settings neu erstellen, danach sollten sie sicher gespeichert bleiben


### Icon

- Neues Icon fuer die Exe


### UI

- Start/Stop Data Transfer Button hat jetzt veraenderlichen Text je nach aktuellem Status


### Update

- Zum Updaten einfach das Tool neustarten
- Eventuell muss LOTRO vorher geschlossen werden



## 2.3.0 - 30.07.2026

### Added

- Multi-Server-Support hinzugefuegt



## 2.2.1 - 30.07.2026

### DLL

- Ein weiterer Crashgrund wurde behoben
- Fehlermeldungen bei Problemen mit der DLL Injection weisen jetzt darauf hin, dass moeglicherweise der Windows Defender die Ursache ist