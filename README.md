# terminal
combine Windows Terminal and MSYS2  

### Prerequirements  
1. <a href="https://github.com/microsoft/terminal/releases" target="_blank">Windows Terminal</a>  
2. [MSYS2](https://www.msys2.org/docs/installer/)  

### File Tree
Terminal
└─MSYS2

this is my setting.json
```json
{
    "$help": "https://aka.ms/terminal-documentation",
    "$schema": "https://aka.ms/terminal-profiles-schema",
    "actions": 
    [
        {
            "command": 
            {
                "action": "copy",
                "singleLine": false
            },
            "keys": "ctrl+c"
        },
        {
            "command": "paste",
            "keys": "ctrl+v"
        },
        {
            "command": "find",
            "keys": "ctrl+shift+f"
        },
        {
            "command": 
            {
                "action": "splitPane",
                "split": "auto",
                "splitMode": "duplicate"
            },
            "keys": "alt+shift+d"
        }
    ],
    "alwaysShowNotificationIcon": false,
    "centerOnLaunch": true,
    "copyFormatting": "none",
    "copyOnSelect": false,
    "defaultProfile": "{1244a880-23e9-4814-af67-d15f183c24f5}",
    "firstWindowPreference": "defaultProfile",
    "focusFollowMouse": false,
    "initialCols": 120,
    "newTabMenu": 
    [
        {
            "type": "remainingProfiles"
        }
    ],
    "newTabPosition": "afterLastTab",
    "profiles": 
    {
        "defaults": 
        {
            "adjustIndistinguishableColors": "indexed",
            "backgroundImage": "ms-appx:///Images/background.jpg",
            "backgroundImageOpacity": 0.2,
            "backgroundImageStretchMode": "uniformToFill",
            "colorScheme": "GruvboxDarkHard",
            "cursorShape": "filledBox",
            "experimental.retroTerminalEffect": false,
            "font": 
            {
                "face": "Cascadia Code",
                "size": 16.0,
                "weight": "bold"
            },
            "intenseTextStyle": "all"
        },
        "list": 
        [
            {
                "commandline": "%SystemRoot%\\System32\\WindowsPowerShell\\v1.0\\powershell.exe",
                "guid": "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",
                "hidden": false,
                "name": "Windows PowerShell"
            },
            {
                "commandline": "%SystemRoot%\\System32\\cmd.exe",
                "guid": "{0caa0dad-35be-5f56-a8ff-afceeeaa6101}",
                "hidden": false,
                "name": "\u547d\u4ee4\u63d0\u793a\u5b57\u5143"
            },
            {
                "guid": "{2c4de342-38b7-51cf-b940-2309a097f518}",
                "hidden": true,
                "name": "Ubuntu",
                "source": "Windows.Terminal.Wsl"
            },
            {
                "guid": "{b453ae62-4e3d-5e58-b989-0a998ec441b8}",
                "hidden": false,
                "name": "Azure Cloud Shell",
                "source": "Windows.Terminal.Azure"
            },
            {
                "guid": "{624e90fe-7935-5c55-8d9b-9dffdc63e58f}",
                "hidden": false,
                "name": "Developer Command Prompt for VS 2022",
                "source": "Windows.Terminal.VisualStudio"
            },
            {
                "guid": "{cd95ac0e-2cf0-56fd-a274-564c3b73438a}",
                "hidden": false,
                "name": "Developer PowerShell for VS 2022",
                "source": "Windows.Terminal.VisualStudio"
            },
            {
                "guid": "{97a006c5-0d47-5168-a0df-140b4e26bc15}",
                "hidden": true,
                "name": "Developer Command Prompt for VS 2019",
                "source": "Windows.Terminal.VisualStudio"
            },
            {
                "guid": "{c0cff0a5-2c45-5f3c-bf4e-48b07f7f2c0d}",
                "hidden": true,
                "name": "Developer PowerShell for VS 2019",
                "source": "Windows.Terminal.VisualStudio"
            },
            {
                "guid": "{51855cb2-8cce-5362-8f54-464b92b32386}",
                "hidden": false,
                "name": "Ubuntu",
                "source": "CanonicalGroupLimited.Ubuntu_79rhkp1fndgsc"
            },
            {
                "commandline": "msys64\\usr\\bin\\bash.exe -i -l",
                "guid": "{1244a880-23e9-4814-af67-d15f183c24f5}",
                "hidden": false,
                "icon": "ms-appx:///ProfileIcons/msys2.ico",
                "name": "MSYS2",
                "startingDirectory": "%USERPROFILE%"
            }
        ]
    },
    "schemes": 
    [
        {
            "background": "#2C2B2B",
            "black": "#000000",
            "blue": "#0225C7",
            "brightBlack": "#686868",
            "brightBlue": "#6871FF",
            "brightCyan": "#60FDFF",
            "brightGreen": "#5FFA68",
            "brightPurple": "#FF77FF",
            "brightRed": "#FF6E67",
            "brightWhite": "#FFFFFF",
            "brightYellow": "#FFFC67",
            "cursorColor": "#C7C7C7",
            "cyan": "#00C5C7",
            "foreground": "#D5A200",
            "green": "#00C200",
            "name": "Apple Classic",
            "purple": "#CA30C7",
            "red": "#C91B00",
            "selectionBackground": "#6B5B02",
            "white": "#C7C7C7",
            "yellow": "#C7C400"
        },
        {
            "background": "#1E1E1E",
            "black": "#1A1A1A",
            "blue": "#0869CB",
            "brightBlack": "#464646",
            "brightBlue": "#0A84FF",
            "brightCyan": "#76D6FF",
            "brightGreen": "#32D74B",
            "brightPurple": "#BF5AF2",
            "brightRed": "#FF453A",
            "brightWhite": "#FFFFFF",
            "brightYellow": "#FFD60A",
            "cursorColor": "#98989D",
            "cyan": "#479EC2",
            "foreground": "#FFFFFF",
            "green": "#26A439",
            "name": "Apple System Colors",
            "purple": "#9647BF",
            "red": "#CC372E",
            "selectionBackground": "#3F638B",
            "white": "#98989D",
            "yellow": "#CDAC08"
        },
        {
            "background": "#0C0C0C",
            "black": "#0C0C0C",
            "blue": "#0037DA",
            "brightBlack": "#767676",
            "brightBlue": "#3B78FF",
            "brightCyan": "#61D6D6",
            "brightGreen": "#16C60C",
            "brightPurple": "#B4009E",
            "brightRed": "#E74856",
            "brightWhite": "#F2F2F2",
            "brightYellow": "#F9F1A5",
            "cursorColor": "#FFFFFF",
            "cyan": "#3A96DD",
            "foreground": "#CCCCCC",
            "green": "#13A10E",
            "name": "Campbell",
            "purple": "#881798",
            "red": "#C50F1F",
            "selectionBackground": "#FFFFFF",
            "white": "#CCCCCC",
            "yellow": "#C19C00"
        },
        {
            "background": "#012456",
            "black": "#0C0C0C",
            "blue": "#0037DA",
            "brightBlack": "#767676",
            "brightBlue": "#3B78FF",
            "brightCyan": "#61D6D6",
            "brightGreen": "#16C60C",
            "brightPurple": "#B4009E",
            "brightRed": "#E74856",
            "brightWhite": "#F2F2F2",
            "brightYellow": "#F9F1A5",
            "cursorColor": "#FFFFFF",
            "cyan": "#3A96DD",
            "foreground": "#CCCCCC",
            "green": "#13A10E",
            "name": "Campbell Powershell",
            "purple": "#881798",
            "red": "#C50F1F",
            "selectionBackground": "#FFFFFF",
            "white": "#CCCCCC",
            "yellow": "#C19C00"
        },
        {
            "background": "#000000",
            "black": "#0C0C0C",
            "blue": "#0037DA",
            "brightBlack": "#767676",
            "brightBlue": "#3B78FF",
            "brightCyan": "#61D6D6",
            "brightGreen": "#16C60C",
            "brightPurple": "#B4009E",
            "brightRed": "#E74856",
            "brightWhite": "#F2F2F2",
            "brightYellow": "#F9F1A5",
            "cursorColor": "#FFFFFF",
            "cyan": "#3A96DD",
            "foreground": "#FFFFFF",
            "green": "#13A10E",
            "name": "Color Scheme 11",
            "purple": "#881798",
            "red": "#C50F1F",
            "selectionBackground": "#FFFFFF",
            "white": "#CCCCCC",
            "yellow": "#C19C00"
        },
        {
            "background": "#1B1B1B",
            "black": "#1B1B1B",
            "blue": "#458588",
            "brightBlack": "#928374",
            "brightBlue": "#83A598",
            "brightCyan": "#8EC07C",
            "brightGreen": "#B8BB26",
            "brightPurple": "#D3869B",
            "brightRed": "#FB4934",
            "brightWhite": "#EBDBB2",
            "brightYellow": "#FABD2F",
            "cursorColor": "#EBDBB2",
            "cyan": "#689D6A",
            "foreground": "#EBDBB2",
            "green": "#98971A",
            "name": "GruvboxDarkHard",
            "purple": "#B16286",
            "red": "#CC241D",
            "selectionBackground": "#665C54",
            "white": "#A89984",
            "yellow": "#D79921"
        },
        {
            "background": "#282C34",
            "black": "#282C34",
            "blue": "#61AFEF",
            "brightBlack": "#5A6374",
            "brightBlue": "#61AFEF",
            "brightCyan": "#56B6C2",
            "brightGreen": "#98C379",
            "brightPurple": "#C678DD",
            "brightRed": "#E06C75",
            "brightWhite": "#DCDFE4",
            "brightYellow": "#E5C07B",
            "cursorColor": "#FFFFFF",
            "cyan": "#56B6C2",
            "foreground": "#DCDFE4",
            "green": "#98C379",
            "name": "One Half Dark",
            "purple": "#C678DD",
            "red": "#E06C75",
            "selectionBackground": "#FFFFFF",
            "white": "#DCDFE4",
            "yellow": "#E5C07B"
        },
        {
            "background": "#FAFAFA",
            "black": "#383A42",
            "blue": "#0184BC",
            "brightBlack": "#4F525D",
            "brightBlue": "#61AFEF",
            "brightCyan": "#56B5C1",
            "brightGreen": "#98C379",
            "brightPurple": "#C577DD",
            "brightRed": "#DF6C75",
            "brightWhite": "#FFFFFF",
            "brightYellow": "#E4C07A",
            "cursorColor": "#4F525D",
            "cyan": "#0997B3",
            "foreground": "#383A42",
            "green": "#50A14F",
            "name": "One Half Light",
            "purple": "#A626A4",
            "red": "#E45649",
            "selectionBackground": "#4F525D",
            "white": "#FAFAFA",
            "yellow": "#C18301"
        },
        {
            "background": "#002B36",
            "black": "#002B36",
            "blue": "#268BD2",
            "brightBlack": "#073642",
            "brightBlue": "#839496",
            "brightCyan": "#93A1A1",
            "brightGreen": "#586E75",
            "brightPurple": "#6C71C4",
            "brightRed": "#CB4B16",
            "brightWhite": "#FDF6E3",
            "brightYellow": "#657B83",
            "cursorColor": "#FFFFFF",
            "cyan": "#2AA198",
            "foreground": "#839496",
            "green": "#859900",
            "name": "Solarized Dark",
            "purple": "#D33682",
            "red": "#DC322F",
            "selectionBackground": "#FFFFFF",
            "white": "#EEE8D5",
            "yellow": "#B58900"
        },
        {
            "background": "#FDF6E3",
            "black": "#002B36",
            "blue": "#268BD2",
            "brightBlack": "#073642",
            "brightBlue": "#839496",
            "brightCyan": "#93A1A1",
            "brightGreen": "#586E75",
            "brightPurple": "#6C71C4",
            "brightRed": "#CB4B16",
            "brightWhite": "#FDF6E3",
            "brightYellow": "#657B83",
            "cursorColor": "#002B36",
            "cyan": "#2AA198",
            "foreground": "#657B83",
            "green": "#859900",
            "name": "Solarized Light",
            "purple": "#D33682",
            "red": "#DC322F",
            "selectionBackground": "#073642",
            "white": "#EEE8D5",
            "yellow": "#B58900"
        },
        {
            "background": "#000000",
            "black": "#000000",
            "blue": "#3465A4",
            "brightBlack": "#555753",
            "brightBlue": "#729FCF",
            "brightCyan": "#34E2E2",
            "brightGreen": "#8AE234",
            "brightPurple": "#AD7FA8",
            "brightRed": "#EF2929",
            "brightWhite": "#EEEEEC",
            "brightYellow": "#FCE94F",
            "cursorColor": "#FFFFFF",
            "cyan": "#06989A",
            "foreground": "#D3D7CF",
            "green": "#4E9A06",
            "name": "Tango Dark",
            "purple": "#75507B",
            "red": "#CC0000",
            "selectionBackground": "#FFFFFF",
            "white": "#D3D7CF",
            "yellow": "#C4A000"
        },
        {
            "background": "#FFFFFF",
            "black": "#000000",
            "blue": "#3465A4",
            "brightBlack": "#555753",
            "brightBlue": "#729FCF",
            "brightCyan": "#34E2E2",
            "brightGreen": "#8AE234",
            "brightPurple": "#AD7FA8",
            "brightRed": "#EF2929",
            "brightWhite": "#EEEEEC",
            "brightYellow": "#FCE94F",
            "cursorColor": "#000000",
            "cyan": "#06989A",
            "foreground": "#555753",
            "green": "#4E9A06",
            "name": "Tango Light",
            "purple": "#75507B",
            "red": "#CC0000",
            "selectionBackground": "#555753",
            "white": "#D3D7CF",
            "yellow": "#C4A000"
        },
        {
            "background": "#300A24",
            "black": "#171421",
            "blue": "#0037DA",
            "brightBlack": "#767676",
            "brightBlue": "#08458F",
            "brightCyan": "#2C9FB3",
            "brightGreen": "#26A269",
            "brightPurple": "#A347BA",
            "brightRed": "#C01C28",
            "brightWhite": "#F2F2F2",
            "brightYellow": "#A2734C",
            "cursorColor": "#FFFFFF",
            "cyan": "#3A96DD",
            "foreground": "#FFFFFF",
            "green": "#26A269",
            "name": "Ubuntu-ColorScheme",
            "purple": "#881798",
            "red": "#C21A23",
            "selectionBackground": "#FFFFFF",
            "white": "#CCCCCC",
            "yellow": "#A2734C"
        },
        {
            "background": "#000000",
            "black": "#000000",
            "blue": "#000080",
            "brightBlack": "#808080",
            "brightBlue": "#0000FF",
            "brightCyan": "#00FFFF",
            "brightGreen": "#00FF00",
            "brightPurple": "#FF00FF",
            "brightRed": "#FF0000",
            "brightWhite": "#FFFFFF",
            "brightYellow": "#FFFF00",
            "cursorColor": "#FFFFFF",
            "cyan": "#008080",
            "foreground": "#C0C0C0",
            "green": "#008000",
            "name": "Vintage",
            "purple": "#800080",
            "red": "#800000",
            "selectionBackground": "#FFFFFF",
            "white": "#C0C0C0",
            "yellow": "#808000"
        }
    ],
    "showTabsInTitlebar": true,
    "snapToGridOnResize": true,
    "theme": "dark",
    "themes": [],
    "useAcrylicInTabRow": true
}
```
