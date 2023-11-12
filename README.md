# MultiplayerSessions

- Developed functionality for creating online sessions and connecting players across the internet by creating a custom Online Subsystem derived from Unreal Engine’s Online Subsystem and configured for Steam.
- Created custom functions based on the Online Subsystem’s session interface which can be called when Menu buttons like Host and Join are pressed.
- These custom functions add custom delegate objects, which are created based on the session interface’s delegate structure types to the session interface’s delegate list and perform necessary functionalities like setting up session settings, finding appropriate match   
  types, and joining and leaving sessions.
