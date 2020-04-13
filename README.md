# tts-games
Group tabletop simulator games.

# Set up
Copy save files desired into save file folder (for Windows this is likely "\Documents\My Games\Tabletop Simulator\Saves\"). 

Symlink from git folder to saves folder is useful:

```powershell
 New-Item -ItemType SymbolicLink -Path "C:\Users\blech\Documents\My Games\Tabletop Simulator\Saves\1362916856.json" -Target "C:\Users\blech\Documents\GitHub\tts-games\hero-realms\1362916856.json"
```