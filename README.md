# Tekken 7 Save Manager
**I do not condone save scumming, this app is only made for honest save backup**

This is a minimal Electron application based on the  `fs-extra` package.

Since the savefile oftenly gets corrupted on PC, and since there is no way to repair them since it appears that the .sav files are encoded,
I went the easy way around and created this tool to store the savefiles, and a way to import them back.

If you want to build a standalone `.exe` file :

`npx electron-builder build --win portable`.
