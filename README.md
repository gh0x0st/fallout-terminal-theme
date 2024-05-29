# Fallout Terminal Theme

With the recent success of the Fallout television series, I've found myself exploring The Commonwealth again, which has also influenced my daily workspace, starting with customizing my Windows Terminal.

![Theme Example](https://github.com/gh0x0st/fallout-terminal-theme/blob/main/example.png)

## Setup

### Open the JSON Configuration File

To access your configuration file, open the Windows Terminal, click the down arrow, select settings then select Open JSON file on the bottom left and 

### Add a New Profile to the List

Find the _profiles_ section in your configuration file and add the following object as a new element of the list array.

```JSON
{
    "backgroundImageOpacity": 1.0,
    "colorScheme": "Fallout Terminal",
    "cursorShape": "filledBox",
    "experimental.retroTerminalEffect": true,
    "font": 
    {
        "face": "Lucida Sans Typewriter"
    },
    "guid": "{574e775e-4f2a-5b96-ac1e-a2962a402336}",
    "hidden": false,
    "name": "PowerShell",
    "source": "Windows.Terminal.PowershellCore"
}
```

### Add a New Scheme

Find the _schemes_ section of your configuration file and add the following object as a new element of that same array.

```JSON
{
    "background": "#0C0C0C",
    "black": "#0C0C0C",
    "blue": "#0C0C0C",
    "brightBlack": "#26E476",
    "brightBlue": "#3B78FF",
    "brightCyan": "#61D6D6",
    "brightGreen": "#26E476",
    "brightPurple": "#B4009E",
    "brightRed": "#E74856",
    "brightWhite": "#26E476",
    "brightYellow": "#26E476",
    "cursorColor": "#26E476",
    "cyan": "#26E476",
    "foreground": "#26E476",
    "green": "#26E476",
    "name": "Fallout Terminal",
    "purple": "#881798",
    "red": "#C50F1F",
    "selectionBackground": "#26E476",
    "white": "#26E476",
    "yellow": "#C19C00"
}
```
