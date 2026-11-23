# Editor Button Shortcuts

Adds keyboard shortcuts to the editor buttons and shows the key on each button.

## Default shortcuts

| Button | Key |
|---|---|
| Edit Object | E |
| Edit Group | G |
| Deselect | Q |
| Edit Extras | X |
| Edit HSV | H |
| Copy + Paste | B |
| Copy / Paste | C / V |
| Copy Values / Paste State | Shift+C / Shift+V |
| Paste Color | Alt+V |
| Go To Layer | L |
| Link / Unlink | K / Shift+K |
| Swipe / Rotate / Free Move / Snap | T / R / F / N |
| Playtest / Stop Playtest | P / Shift+P |
| Play Music | M |
| Zoom In / Zoom Out | Z / Shift+Z |
| Next / Previous Layer | ] / [ |
| All Layers | \ |

Undo, Redo, Delete Selected and the Build/Edit/Delete tabs can also be bound, but start unbound because vanilla already has keys for them.

Every key can be changed in the mod settings, and you can bind more than one key to the same button. The labels can be moved, resized, recolored or hidden.

## Building

**GitHub (easiest):** push this folder to a GitHub repo. The workflow in `.github/workflows/build.yml` builds Windows, macOS, iOS and Android automatically. Download the `.geode` file from the **Build Output** artifact on the Actions tab.

**Locally:** install the [Geode CLI and SDK](https://docs.geode-sdk.org/getting-started/geode-cli), then run:

```
geode build
```

Put the resulting `.geode` file in your `geode/mods` folder.
