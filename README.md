# CrysisFix
Fixes the refresh rate being forced to the lowest available in the DX10 version of Crysis and Crysis Wars.

Use CrysisLaunch.exe or CrysisWarsLaunch.exe to start the game. Any arguments will be passed through to the game itself.

Running the game in compatability mode may prevent this fix from working. I do not know why.

Depends on the Detours library (v4.0):
https://github.com/microsoft/detours

This will need to be added to the include path before you can build from source.