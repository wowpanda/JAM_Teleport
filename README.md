# JAM_Teleport 
- A simple vMenu-style teleport-to-waypoint script.
- Default teleport key: "PAGEDOWN".

### Requirements
* [JAM_Base](https://github.com/JustAnotherModder/JAM)

## Download & Installation

### Manually
- Make sure you have all requirements (and their dependencies) installed correctly before continuing.
- Download https://github.com/JustAnotherModder/JAM_Teleport/archive/master.zip
- Extract the JAM_Teleport folder (and its contents) into your `JAM` folder, inside of your `resources` directory.
- Open `__resource.lua` in your `JAM` folder.
- Add the files to their respective locations, like so :

```
client_scripts {
	'JAM_Main.lua',
	'JAM_Utilities.lua',

	'JAM_Commands.lua',

	-- Teleport
	'JAM_Teleport/JAM_Teleport_Config.lua',
	'JAM_Teleport/JAM_Teleport_Client.lua',
}

server_scripts {	
	'JAM_Main.lua',
	'JAM_Utilities.lua',

	'@mysql-async/lib/MySQL.lua',

	-- Teleport
	'JAM_Teleport/JAM_Teleport_Config.lua',
	'JAM_Teleport/JAM_Teleport_Server.lua',
}
```
