This map editor is in development and is likely to have bugs.

The settings of the map editor can be edited in the Settings.json file found in the Settings directory of this folder.
To edit the settings, open the Settings.json file and edit the text between the "" that is after the setting you want to change.

For example in order to change the background edit the https address as shown below

{"BackgroundURL":"https://raw.githubusercontent.com/User8426/ThreeSpies/main/ThreeSpies/assets/WorldMap.png","MapSaveName":"Map",

which can be changed to

{"BackgroundURL":"BackgroundLocation.png","MapSaveName":"Map",

When changing the save location, use the expressions at https://wiki.gdevelop.io/gdevelop5/all-features/expressions-reference in the filesystem section.

In order to use a custom map, maps need to be in the host's Maps folder inside of their game directory. Only a map with the name Map.json will be selected.

In order to create a new map, make sure there are no maps in the map folder that could be overwritten.

To move the camera, use the arrow keys. In order to change the camera zoom, use the mouse wheel.

Map creation is split into 5 stages, each explained in detail below.

Stage 1
This stage allows you to add and delete cities from the map. You can also adjust their size.
This is done by clicking on the buttons to choose your action, then click where you want the city.
To change the size, simply drag the slider until the mouse is a city that is the right size.
(Not Implemented yet) Click the Bonus City button to add bonus cities instead of normal cities.

Stage 2
This stage allows you to add and delete roads. 
This is done by clicking on the buttons to choose your action, then click which cities you want to be connected.

Stage 3 
This stage allows you to set each players spawn.
This is done by clicking on the buttons to choose which player spawns, then click the city you want them to spawn at.

Stage 4
This stage allows you to name each city.
This is done by clicking on the button to add a name, then click where you want the name. The editor will then show whatever you input.
In order to finish typing a name, press the ENTER key.
In order to change a name, use the delete button and click the name.

Stage 5
This stage allows you to set the lockdown route. (Not Implemented)
To set the order of lockdowns, click each city in the order of lockdowns. For example, if you wanted London locked down first, the first city you click should be London.
If you want London to be the second city to lock down, click it as the second city.