# Whetstone Transient Shaper
A free, open source transient shaping audio plugin that operates on a specified frequency band.

Whetstone will extract a certain frequency band based on a low cutoff and high cutoff that you choose, apply transient shaping to it, and then reintegrate the shaped band back into the original signal. This plugin is meant to be comparable to the excellent Spiff plugin in its core functionality, but lacks many of the nice features and polished UI.

# Installation
Grab the latest release from https://github.com/unicornsasfuel/whetstone/releases that corresponds to your operating system and supported plugin type, unzip it if it is zipped, and drop the file into the appropriate plugin directory.

Help finding VST3 locations can be found here: https://helpcenter.steinberg.de/hc/en-us/articles/115000177084-VST-plug-in-locations-on-Windows

Help finding AU locations can be found here: https://support.apple.com/en-us/HT201532

Since making macOS plugins that do not trigger Gatekeeper requires paying Apple for a developer license and I am not profiting from this software, this plugin will trigger Gatekeeper. Right click the plugin after placing it in the correct directory, and select "Open With". Choose any application you like, even one that won't open it properly, and open it. This creates an exception for the plugin and allows you to use it.

# Building
This project is coded in Faust, so it can be built into any of the outputs Faust is capable of. A JUCE project is also provided, for building with Projucer.
