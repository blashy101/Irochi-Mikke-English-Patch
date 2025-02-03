# Irochi-Mikke-English-Patch

Official English Version Released: https://www.nintendo.com/us/store/products/odd-hue-out-switch/

Hello! This is an English translation patch for いろちみっけ! aka Irochi Mikke. 
The patch is in xdelta format and you'll need a couple of things to get started.

First, you need xDelta: https://www.romhacking.net/utilities/598/
and NxDumpTool: https://github.com/DarkMatterCore/nxdumptool

Use NxDumpTool to create a romFS dump of your copy of the game, then get 1 file from your dump.
"sharedassets0.assets"

Copy it into wherever you put your xDelta patch from the download, and patch the file from your romFS dump with the corresponding patch.

Then, we'll make a LayeredFS folder structure to have these newly patched files loaded instead of the original game files.

Folder structure should look like this:

SDROOT\atmosphere\contents\0100F6901D32E000\romfs\Data\ *patched file here*

Start up the game and enjoy!
