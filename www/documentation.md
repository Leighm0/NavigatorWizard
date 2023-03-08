# Navigator Wizard

Control4 Driver to programmatically change the Visibility of Devices in Room(s) on the Navigator UI

#### Key Factors:

- Supported Navigator Menus: Comfort, Lights, Listen, Security, Shades, Watch
- Multiple Room Selections are possible to change device visibility on several rooms at once
- Set Refresh Navigators Property to On will issue a "refresh navigators" after programming is executed.

Note: There is currently no way to filter available devices based on Room or Navigator selection due to the way Driver Commands works, as such you will have to determine which rooms have what devices yourself.

#### Example Programmning Action:

![i](//navigatorwizard.png)

#### Release Notes:

- Version 1: Initial Release
- Version 2: Expanded AV Device Selections, added Refresh Navigators property.
- Version 3: Added all Navigator Menus and a lot more device proxy types to cover these navigators.
