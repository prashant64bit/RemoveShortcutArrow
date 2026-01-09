# RemoveShortcutArrow

![Windows](https://img.shields.io/badge/OS-Windows-blue?logo=windows)  
![License](https://img.shields.io/badge/license-MIT-green)  
![Version](https://img.shields.io/badge/version-1.0.0-orange)  

**RemoveShortcutArrow** Removes the shortcut arrow overlay icon from Windows shortcuts using Windows Registry entries.  
Includes an undo script to restore the default shortcut arrow.

## Usage

### Goto Release
1. Find latest **[Latest Release](https://github.com/Prashant64bit/RemoveShortcutArrow/releases/latest)**
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
| `blank.ico` | Transparent icon used to override the shortcut arrow |

## Notes
- Uses Windows Registry
- Administrator access required
- Fully reversible
- RemoveShortcutArrow Folder should not be deleted from C drive.

## LICENSE
This project is licensed under the [MIT License](LICENSE).  

