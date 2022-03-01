# Taiko no Tatsujin - Fumen Timing Window Replace Script

Simple Python 3 script to replace that can replace the timing windows in a Taiko Gen 3 fumen

Usage: replace_timing.py inFile outFile timingWindow

Timing Options: Standard, Hitnarrow, Hitwide, Custom


Detects what difficulty timing window to use based on the Input's filename.  
Easy(\_e) and Normal(\_n) will use the easy timing
Hard(\_h), Extreme(\_e) and Ura(\_x) will use hard timing

If it fails to detect difficulty, it'll use the hard timing values instead.

Edit the Custom section of timing.ini to use Custom timing windows
