# Swiftpoint Multiboxing
My Swiftpoint Z multiboxing configuration

This configuration contains the default global profile and 2 additional profiles specifically for World of Warcraft Multiboxing:
1. **ISBoxer** - Uses default ISBoxer keys for keymaps toggles, broadcast toggles and switching slots.  Additional buttons are defined to support an action bar based DPS rotation if you're moving between hardware and software like I am.
2. **AIMOS** - An updated version of the configuration I've been working on since December of 2020.  Set team focus hot keys have been redefined to match the ISBoxer slot swapping hot keys (CTRL+ALT+1, CTRL+ALT+2 ... CTRL+ALT+5).
3. **Default** - This is just an empty profile to give you a way to set your mouse to the global profile with none of the multiboxing buttons active.

# Action bar DPS
All action bar DPS macros assume you are using `NUM1` through `NUM9` as well as `NUM /`, `NUM 0` and `NUM .`.  Macros break an action bar up into a top and bottom, consisting of six buttons each.  `NUM1` is assumed to be an in game macro that does the following:
```
/assist focus
/script SetView(4); SetView(4)
```
# Game movement and interact key bindings
My game keys are as follows, update the profile to suit your preferences:
`E`, `ALT+E`: Move forward, others move forward

`S`, `ALT+S`: Move left, others move left

`F`, `ALT+F`: Move right, others move right

`D`, `ALT+D`: Move back, others move back

`H`: Interact with Target (All characters)

`I`: Interact with Target (Melee only)


# Additional key binds and macros  that may be referenced in either configuration:
`0`: Follow `/follow focus`

`ALT+-`: Click to move On `/run  ConsoleExec("Autointeract 1")`

`ALT+0`: Click to move Off `/run ConsoleExec("Autointeract 0")`

# Swiftpoint Profiles
This configuration uses the default settings for switching profiles, changing mouse DPI and updating the OLED display.  Tilt the mouse to the right 25 degrees and use the following buttons:
* Left trigger pull - Alternate between OLED displays
* Scroll wheel push/pull - Add and remove 100 DPI from current setting
* Rear edge press - Next profile
* Front edge press - Previous profile

# How do I use this?
First you need [a Swiftpoint Z mouse](https://www.swiftpoint.com/store/swiftpoint-z-mouse/)!  I am not sponsored by them and I receive no compensation for linking to them.  I own two of these and it really is the best gaming mouse I've ever used.

* Backup your own settings*

Next you would download the .SPCF file from this GitHub repository.  If you already have your own Swiftpoint configuration, you should back it up with the following commands (these are for use while in Expert Mode):
* Click on the hamburger menu (the three line icon top left)
* Click Export Mappings to a file
* Save your file somewhere you won't lose it.  I like to put mine in OneDrive but Google Drive and Dropbox work just as well.  If you make a habit of storing your configuration in the cloud you should be able to restore a previous version if you ever make a mistake

* Import my settings *

With your config backed up, you can choose to import some or all of my configuration file.  The ISBoxer and AIMOS profiles are distinct so you can select either one or both.
* Click the hamburger menu again
* Import Mappings from a file
* Click the checkbox(es) of the profile(s) you want to import
* Click OK

* Save to on board memory *

If you like what you see remember to save the profile and store everything back on the mouse.
* Hamburger menu
* Save mapping to permenant memory in mouse
