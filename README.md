How apply a patch?

by commands:
  "svn patch svnpatch.diff" from main svn directory which contain subdirectories "source", "build", etc.
and additionally (because svn diff doesn't show it)
  "patch -u -p0 < gnupatch.diff" from directory which contain subdirectory "tutorials" > ".../data/glest_game/ X /tutorials"



What this patch doing?
Improve in one or other way pretty much "little things".


  > from the forum

fixes bugs:
r4462: "IRC People Online" list isn't properly refreshed
https://forum.megaglest.org/index.php?topic=9113.0

r4323: Two strings associated with more than one meaning...
https://forum.megaglest.org/index.php?topic=9030.0

r4378: Warnings during the compilation related with compression
https://forum.megaglest.org/index.php?topic=9075.0


introduces new features:
More lines or scroll bar for tutorial instructions
https://forum.megaglest.org/index.php?topic=8331.0

Replace question marks in localization keys
https://forum.megaglest.org/index.php?topic=9138.0

Split "ExitGame?" string 
https://forum.megaglest.org/index.php?topic=9102.0

Replace the "?" with a flag for servers that dont reveal their nationality 
https://forum.megaglest.org/index.php?topic=9162.0

Information about "my own" nickname in game lobby. 
https://forum.megaglest.org/index.php?topic=9009.0

Remove the stupid linux hint 
https://forum.megaglest.org/index.php?topic=8909.0


  > principal others

Improve the functionality and appearance of menus, texts, buttons for languages ​​other than default,
for English very often too but mostly "as a side effect" ;). [This is a v. large part of patch]

Corrects meaning of certain oryginal texts to make them more understandable.

Improves slightly tutorials.

Allows to version info be translatable.

Introduces new standard of informations recognition about Linux distribution (not every distribution already supports it).

Introduces support for LinuxMintDebianEdition and PCLinuxOS and updates support for previous distributions.

Improves some messages during linux compilation and reduces the number of unnecessary messages in console during a game.


  > and others smaller

