SkinSettingsConverter:
Converts old skinsettings (<v16, helix, isengard or even older) to new settings (v16>, jarvis, krypton, ...)

Options:
-h: show help
-s <skin name>: Select skin name (Default: skin.xonfluence)
-g <folder>: Folder containing guisettings.xml (Default: kodi/userdata/)
-d <folder>: Folder containing settings.xml for Jarvis and up(Default: kodi/userdata/addon_data/skin.xonfluence)

In linux: just run SkinSettingsConverter
In Windows/ mac: run python SkinSettingsConverter

Of cource python needs to be installed.

Good practice:
* Copy guisettings.xml to a safe location (before upgrading to kodi Jarvis)
* Run this script (and write settings.xml to a safe location)
* Copy settings.xml to its desired folder when kodi Jarvis is installed (when kodi is not running)
* enjoy

Helly.
