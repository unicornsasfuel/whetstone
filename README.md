# Whetstone Transient Shaper
A free, open source transient shaping audio plugin that operates on a specified frequency band

Whetstone will extract a certain frequency band based on a low cutoff and high cutoff that you choose, apply transient shaping to it, and then reintegrate the shaped band back into the original signal. This plugin is meant to be comparable to the excellent Spiff plugin in its core functionality, but lacks many of the nice features and polished UI.

# Building
This project is coded in Faust, so it can be built into any of the outputs Faust is capable of. A JUCE project is also provided, for building with Projucer.
