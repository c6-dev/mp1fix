# Max Payne launcher skip fix

When `-nodialog` launch option is used in MP1, several graphics settings don't get loaded correctly, namely AA, texture filtering and texture color depth. This patch fixes it.  

Before and after the patch, when `-nodialog` is used and AA set to 8:

![Untitled-1](https://github.com/c6-dev/mp1fix/assets/31777460/e16620ab-a6fd-4b89-9582-06dcd23168e5)


Supports latest Steam release only. To install, unpack `dsound.dll` into the game folder.

Same problem is present in Max Payne 2 - fix available [here](https://github.com/c6-dev/mp2fix/).
