# Novation-Launchpad-Mini-MK3-for-Reaper
A set of config and helper files to make Novation Launchpad Mini MK3 useful with [Cockos Reaper](https://www.reaper.fm/index.php) and [Helgoboss Playtime](https://www.helgoboss.org/projects/playtime/).

## Using Launchpad Mini MK3 in Legacy mode with Playtime:
Why Legacy Mode? Because in Legacy Mode Launchpad Mini MK3 releases all the side buttons to be usable via MIDI. Otherwise, when not in Legacy Mode, those side buttons have special meaning and can not be used for muting groups and triggering scenes.

Put your Launchpad Mini MK3 into Legacy mode by holding the [Session] button for 2 seconds and then, when the pad "screen" changes, press the pink [>] button. Then press [Session] again to exit the setup. Your Launchpad Mini MK3 is now in Legacy mode.

Download the file [launchpad-mini-mk3-legacy.json](https://raw.github.com/AtmanActive/Novation-Launchpad-Mini-MK3-for-Reaper/main/Reaper/Playtime/controllers/launchpad-mini-mk3-legacy.json) and save it to your Reaper/Playtime/controllers/ folder. Then (re)start Reaper and in the Playtime plug-in choose "Launchpad Mini MK3 in Legacy Mode" as your controller.

If you would like to change the colours, edit the file launchpad-mini-mk3-legacy.json and change the numbers under the "lights" section. Pads can not have the Reaper item colours as that functionality is not supported by Playtime (yet). The only colour-coded-states supported are: "almostPlaying", "almostStopping", "empty", "playing", "recording" and "stopped".

