
# Aimbot for MM2

This script is a smooth and accurate aimbot designed for use in Roblox, particularly for the game *Murder Mystery 2 (MM2)*.

## Features
- Locks onto the torso of targets with high accuracy.
- Displays target boxes for better visualization.
- Adjustable settings for smoothness, sensitivity, and more.
- Works seamlessly with MM2.

## Installation

### Using Loadstring
1. Copy the following loadstring:
   ```lua
   loadstring(game:HttpGet("https://raw.githubusercontent.com/chika200/aimbot-mm2/main/aimbot.lua"))()
   ```
2. Paste it into your Roblox executor.
3. Execute the script.

### Manual Installation
1. Go to the [aimbot script repository](https://github.com/chika200/aimbot-mm2/blob/main/aimbot).
2. Copy the contents of `aimbot.lua`.
3. Paste it into your Roblox executor and run.

## Customization
You can edit the script settings for more tailored performance:
- **LockPart**: Adjust the body part to lock onto (default: `Torso`).
- **Sensitivity**: Controls smoothness of locking.
- **Sensitivity2**: Adjusts aiming speed (higher value = faster).
- **Boxes**: Toggle target boxes (default: `true`).

### Example Settings Adjustment
To lock accurately onto the torso with fast and smooth movement:
```lua
ExunysDeveloperAimbot.Settings.LockPart = "Torso"
ExunysDeveloperAimbot.Settings.Sensitivity = 0.2
ExunysDeveloperAimbot.Settings.Sensitivity2 = 5
ExunysDeveloperAimbot.Settings.Boxes = true
```

## Notes
- For any issues or improvements, feel free to contribute or create an issue on the [GitHub repository](https://github.com/chika200/aimbot-mm2).

