A work in progress theme that aims to resemble the Nano text editor. It is intended to be minimalistic and exclusive to dark mode: for the gremlins and other basement dwellers.
# Current Visualisation
![Visualisation](https://github.com/DarkKooky/obsidian-styling/blob/main/Example.png)
# Graph
As I've only implemented colouring for edges, the `Graph view` is best used with the following parameters:
```json
{
  "collapse-filter": true,
  "search": "",
  "showTags": false,
  "showAttachments": true,
  "hideUnresolved": false,
  "showOrphans": false,
  "collapse-color-groups": true,
  "colorGroups": [],
  "collapse-display": false,
  "showArrow": false,
  "textFadeMultiplier": 3,
  "nodeSizeMultiplier": 0.1,
  "lineSizeMultiplier": 0.1,
  "collapse-forces": true,
  "centerStrength": 0.8,
  "repelStrength": 20,
  "linkStrength": 1,
  "linkDistance": 30,
  "scale": 0.055,
  "close": true
}
```
# How To Use
- In Obsidian, open the `Settings > Appearance > CSS snippets`
- Click 🗁 to open the vault's snippets directory `.obsidian/snippets/`
- Place the [theme.css](https://github.com/DarkKooky/obsidian-styling/blob/main/theme.CSS) into the opened directory
- Back in Obsidian, click ⭮ to reload snippets
- The theme should appear in the list and can be enabled
