# Umineko When They Cry Chiru - CG Restoration Mod
A patch for the 2017 Mangagamer release of Umineko Chiru, to restore the unused Pachinko CGs to the game.
----
## About
The Mangagamer release of **Umineko no Naku Koro ni Chiru** (available through both their website and via Steam) has, like their initial release of **Umineko no Naku Koro ni** itself, a number of unused CG images present in the game's files. However, _unlike_ their release of Umineko, none of the CGs are called or even defined in Chiru's script - due to time constraints (and the relatively small number of CGs available), they were not implemented.

This patch aims to restore these CGs to the game, in a manner that avoids any unwanted behaviour if the player switches between the original PC sprites and the new Pachinko sprites. A few typos and inconsistencies in the script are also fixed.
## Feedback
Other than bug reports, constructive feedback is welcome - for instance, on things such as:
- CG locations
- script errors that could use correcting (e.g. sprites not clearing properly) 
- script changes that are unnecessary (e.g. minor syntax fixes, capitalization changes to some dialogue)

Please read the [Feedback Notes](https://github.com/KyuuGryphon/umineko-chiru-cgs/issues/1) thread before creating a new issue.
## Installation
The latest release of the patch can be downloaded from the [Releases](https://github.com/KyuuGryphon/umineko-chiru-cgs/releases) section. Simply download the .zip file, and extract the folders and 0.utf file to your Umineko Chiru directory. For the Steam release, it should be something like this:

`C:/Program Files (x86)/Steam/steamapps/common/Umineko Chiru`

**I strongly recommend backing up the original 0.utf file before installing!** In case something goes wrong, you can simply delete the patch's version of 0.utf and restore the original version. 
## Future Plans
# For this patch
Ideally, I'd like to find a way to clean up the two CGs that I had to scan in from [the Pachislot version of the game's art book](https://www.ninoma.com/index.php/character-of-the-slot-golden-witch-umineko-no-naku-koro-ni-artbooks) (specifically, two of the ending CGs for Episode 8). Hopefully, I can get clean enough scans that they can just be touched up and colour corrected directly, but that remains to be seen.
# Other plans
Once this Chiru patch is complete, I plan on making a version of it that is compatible with 07th Modding's [Chiru voice patch](https://github.com/07th-mod/umineko-answer/tree/master/voices-only). After that, I may look at making a similar patch for the Umineko Question Arcs (while its CGs are defined, the calls are somewhat buggy and some of them are still unimplemented).
## Patch status
- [x] Episode 5 CGs
- [x] Episode 5 bugfixing
- [x] Episode 6 CGs
- [x] Episode 6 bugfixing
- [x] Episode 7 CGs
- [ ] Episode 7 bugfixing
- [ ] Episode 8 CGs
- [ ] Episode 8 bugfixing
