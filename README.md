# Arduino Language Support for VS Code
## Why?
I am a robotics enthusiast and wanted to edit my arduino project in Visual Studio Code.

However the following issues arose which convinced me to make my own extension for it.
- When using C++ as the language mode when using .ino files, it doesn't recognize any of the arduino specific functions and treats them as an error.
- Microsoft's extension for arduino only has "arduino output" as an option for language mode. 

## What's wrong with Microsoft's Arduino extension?
By default, "arduino output" does't use Syntax Highlighting which makes it difficult to edit/create programs as it becomes confusing to navigate through it, and monotonus enough to make a person call it quits.

## What I intend to include
In this extension I do the following at the moment
- Include Syntax Highlighting
- Add Arduino as default language for .ino files, this will disable C++ linter automatically each time you open .ino file allowing you to avoid the numerous errors formed due to arduino-specific functions
- Include 2 Themes as a bonus for users who prefer the Arduino IDE's charming looks
    - Arduino IDE Light
    - Arduino IDE Dark

## Themes
### Arduino IDE Light
![Homepage](images/screenshots/Screenshot%20(4).png)
![Editor](images/screenshots/Screenshot%20(2).png)
### Arduino IDE Dark
![Homepage](images/screenshots/Screenshot%20(5).png)
![Editor](images/screenshots/Screenshot%20(1).png)

## Configure Language
If not set by default, click on the language mode button in the status bar.<br> It is most likely in the bottom right, with either "C++" or "Plain Text" written on it.
That will open this menu:<br>
![Language Mode Menu](images/screenshots/Screenshot%20(6).png)<br>
Click on Arduino to use it or, click on "Configure File Association for '.ino'" and then click on Arduino to set it up permanently