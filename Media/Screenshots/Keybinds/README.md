# How to create Keyboard images for Keybinds

1. Go to https://www.keyboard-layout-editor.com/
2. Select a Preset: `ANSI 104` for a full keyboard with arrow keys and numpad
3. Select each key in the keybinds, and type in a short name for each action into the `Properties` tab:
  - Add the word `Space` to the top-left of the Spacebar for consistency
  - `Pause` is on `Esc`
  - Copy-paste symbols `↑` `←` `↓` `→` for directional inputs
  - `Skill` and `Tool` on separate lines
  - `Ndln` is short for Needolin
  - `Hrpn` is short for Harpoon
  - `QMap` is short for Quick Map
  - `Inv` is short for Inventory
  - `Jrnl` is short for Journal
  - `Chlng` is short for Challenge
4. Unselect by clicking somewhere else before saving it as an image.

Save the layouts as `.json` files with the `Download` button -> `Download JSON`, and save them as `.png` files with the `Download` button -> `Download PNG`.

Those JSON files can be imported back into the website with the `Raw data` tab -> `Upload JSON` for editing.

The `ansi-104-template.json` file in this folder contains the `Space` and `Esc` changes common to all Keyboard images for Keybinds.
