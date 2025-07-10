# MuseScore plugin: add scale-degree numbers

![screenshot](https://github.com/meganlavengood/MS-SD-plugin/blob/main/demo.png?raw=true)

[View example score on MuseScore.com](https://musescore.com/user/32728834/scores/26193772)

## Purpose

Adds lyrics below notes that correspond to scale-degree numbers in major or minor. Uses SMuFL glyphs to properly display scale degrees as Arabic numerals with carats/circumflex.

By default, raised/lowered scale degrees are shown with arrows. To change to sharp and flat signs, in the .qml file, set `var arrows` to `false`.

**Requires that you use Bravura font for Lyrics text style in order to display properly.**

## Installation instructions

1. Move the **scale-degree-numbers** folder to MuseScore’s plugins folder. This is configurable at **Preferences > General > Folders**. The default directories are:
    - Windows: C:\Users\%USERNAME%\Documents\MuseScore4\Plugins
    - nmacOS: ~/Documents/MuseScore4/Plugins
    - Linux: ~/Documents/MuseScore4/Plugins
2. In MuseScore, click **Plugins > Manage plugins** and enable both plugins (major and minor).

To update to a new version, simply replace the **scale-degree-numbers** folder with the new one (you may need to restart Musescore).

## Use

1. **Ensure that your Lyrics text type has its font set to Bravura.** Other fonts may not properly display the scale-degree glyphs.
2. Click **Plugins > Scale degree numbers ([major or minor])**

By default, raised/lowered scale degrees are shown with arrows. To change to sharp and flat signs, in the .qml file, set `var arrows` to `false`.

## Notes

Developed for use with [Open Music Theory](https://viva.pressbooks.pub/openmusictheory).

Based on [Add Jianpu numbers as text (lyrics): 五线谱->简谱](https://musescore.org/en/project/add-jianpu-numbers-text-lyrics-wuxianpu-jianpu)
