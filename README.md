# jetsoundbath
Jet Sound Bath is a Max MSP patch for analyzing low frequency noise sources and converting the dominant frequency of a source into a harmonic immersive experience. This installation first appeared at the Georgetown Steam Plant Science Fair, September 20-22, 2024. Hundreds of visitors came through and experienced the sound bath. Each time a jet flew overhead (on its way to Seatac airport or taking off/landing at the adjacent Boeing Field), this patch analyzed the jet sound being picked up live from a shotgun microphone outside the building and "re-tuned" the room with the dominant frequency of that jet fly-over.

How to Install:
Max MSP is required to load the patch. Visit www.cycling74.com for a demo of Max. Download both .maxpat files into the same directory and double-click jsb.maxpat to open.

Ideas for further development:
1. Improve the band filtering method which is currently dependent on some arbitrary values for Q (resonance) and threshold amplitudes. During the jet sound installation I manually tweaked these variables to find the approriate levels given the particular environment I was recording in. However, if the environment is likely to change, there should be a callibration button that takes sample noise values and automatically applies these filter variables.


