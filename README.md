# Geode Android Launcher

Launches a vanilla copy of Geometry Dash with the Geode loader added.

## Shortcut Links

The launcher supports a handful of links as an escape hatch when the main functionality is impaired in some way (such as needing to prevent an automatic launch due to a crash).  
You can open these links by copying them into the URL bar in some browsers (like Chrome), or through ADB.

| Link                                        | Action                                                                   |
|---------------------------------------------|--------------------------------------------------------------------------|
| lightsync-launcher://main                       | Opens to the main activity, forces the user to explicitly confirm launch |
| lightsync-launcher://main/launch                | Opens to the game after the launcher is finished checking for updates    | 
| lightsync-launcher://main/launch?safe-mode=true | Opens to the game like before, but with safe mode enabled                |
| lightsync-launcher://settings                   | Opens the main settings                                                  |
| lightsync-launcher://developer-settings         | Opens the developer settings                                             |
| lightsync-launcher://logs                       | Opens the application logs                                               |
| lightsync-launcher://crashes                    | Opens the crash dumps viewer                                             |
