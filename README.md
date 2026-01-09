# RemoveShortcutArrow

Removes the shortcut arrow overlay icon from Windows shortcuts using Windows Registry entries.  
Includes an undo script to restore the default shortcut arrow.

## Usage

### Goto Release
1. Find latest release version
2. Goto Assets and find "RemoveShortcutArrow.zip"
3. Click "RemoveShortcutArrow.zip"

### Remove shortcut arrow
1. Goto Downloads Folder
2. Find "RemoveShortcutArrow.zip"
3. Extract the folder to: "C:\RemoveShortcutArrow"
4. Open the folder  
5. Right-click `RemoveShortcutArrow.reg`  
6. Select **Run as administrator**  
7. Accept the registry prompt  
8. Restart File Explorer or sign out/in if required

### Restore shortcut arrow
1. Open: "C:\RemoveShortcutArrow"
2. Right-click `UndoRemoveShortcutArrow.reg`  
3. Select **Run as administrator**  
4. Accept the registry prompt  
5. Restart File Explorer or sign out/in if required

## Files

| File | Description |
|------|------------|
| `RemoveShortcutArrow.reg` | Removes shortcut arrow overlay icon |
| `UndoRemoveShortcutArrow.reg` | Restores default shortcut arrow icon |

## Notes
- Uses Windows Registry
- Administrator access required
- Fully reversible
- RemoveShortcutArrow Folder should not be deleted from C drive.
