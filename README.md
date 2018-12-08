#Xbox controllers player manager for Unity
By Ludovic Aubut-Lussier
------------------------------------------

The 'Xbox controllers players manager for Unity' package is designed to manage player controls in multiplayer games played on a single Window computer. As implied by its name, the package is provided with an input map (located in the 'InputManager.asset' file) corresponding the Xbox controller joysticks and buttons. But as a bonus, it also accepts keyboard and mouse inputs mapping

To install the 'Xbox controllers players manager for Unity' package, follow these steps:

1. Import our .unitypackage file in your Unity project.

2. Replace the 'InputManager.asset' file located in your project folder under 'ProjectSettings'
with the corresponding included file.

3. From the Prefabs/Essentials folder, drag and drop everything to your scene.

Installation is then complete.

Press play to launch the game and observe how players can now join the game by a push of the Xbox controller 'A' button (Z, U or dpad-7 on a keyboard and left click on a mouse). A player may also leave the game by pressing the Xbox controller 'B' button (X, i or dpad-9 on a keyboard and right click on a mouse).
Up to 15 players may join the game, provided a keyboard, a mouse and enough Xbox controllers are connected to the computer. Even more players could join if you decide to map more keyboard buttons.

Use the listOfPlayers variable to access the list of players that have joined the game. Every 'PlayerId' object provides its own 'Controls' object that is publicly accessible. The 'Controls' object let you access the different joysticks and buttons assigned to that PlayerId.

Note that the 'InputManager.asset' map all the controls for 11 different Xbox controllers as well as the default controls usually provided by default in a Unity project. The only exceptions are the two trigger buttons (axis 9 and 10 of a Xbox controller). It is a known issue with Window's drivers that the behaviour of these two buttons becomes unpredictable when more then one Xbox controller is plugged in a Window machine.