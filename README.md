# custom-workspacer-config
This is my custom config file for the workspacer application on windows. My goals were simple...
- Preserve as similar to default functionality as possible
- Reduce conflict with hotkeys from other programs

| Hotkeys                | Description                             |
| ---------------------- | --------------------------------------- |
| alt + (#)              | Switch to workspace #                   |
| alt + Left             | Switch to previous workspace            |
| alt + Right            | Switch to next workspace                |
| alt + P                | Show menu                               |
| alt + Esc              | Toggle enable/ disable                  |
| alt + I                | Toggle console window                   |
| alt + Shift + Left     | Move focused window to previous monitor |
| alt + Shift + Right    | Move focused window to next monitor     |
| alt + Shift + H        | Shrink primary area                     |
| alt + Shift + L        | Expand primary are                      |
| alt + Shift + K        | Swap focus and next window              |
| alt + Shift + J        | Swap focus and previous window          |
| win + Shift + Add      | Increment outer gap                     |
| win + Shift + Subtract | Decrement inner gap                     |
| alt + Shift + (#)      | Move focused window to workspace #      |
| alt + Shift + Add      | Increment inner gap                     |
| alt + Shift + Subtract | Decrement inner gap                     |
| alt + Shift + Space    | Next layout engine                      |
| win + Shift + Space    | Previous layout engine                  |
| alt + Shift + C        | Close focused window                    |
| alt + Shift + R        | Restart workspacer                      |
| alt + Shift + Q        | Quit workspacer                         |


Feel free to fork and use how you like. I also dont have a lot of expertise in c#, I would love a pull request that would add the ability to disable the tiling in a chosen window. This would be useful for things like GODOT that have lots of seperate windows that I dont necessarily want tiled.

Hope you enjoy!