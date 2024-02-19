# ScreenShooter

This app is used to **quickly take screenshot** of an area that may be **all or only one monitors or the active window only**.

## Take Screenshoot
Which area you will take is set from the **main app menu, invoked by the right click on the app icon** in the system tray.
From the same menu you may set and open a folder with screenshots, and make some actions on the last taken screenshot. 
If during selecting **'Set Saving Folder'** menu item the **Ctrl key** was pressed - the last used folder wil be replaced with
the actual date in format **yyyy-mm-dd**. If, additionaly, the **Shift key** will be pressed, format will be **yyyy-mm-dd_hh.mm**.
 
A new screenshot can be taken by **double click on the app icon** in the system tray. 
**Alt+Dblclick will re-take the screenshot - at first, the **previous will be deleted, and a new one will replace it**.

Also screeshot may be taken by pressing the **hotkeys** that may be set by selecting **Configuration** item from the main menu.
Hotkeys must match the Autohotkey (v1) hotkey string as discribed here - https://www.autohotkey.com/docs/v1/Hotkeys.htm 

## Comment Screenshot

After taking screenshot, the small **preview will be show** for the time, defined in the Configuration.

If **during this time the Ctrl key will be pressed**, the preview would not be hiden automatically, and you will be able to
**add a 'comment' to the file name** that will appended to the screenshot file number. Such a comment may be also added to 
the last taken screenshot by pressing the Preview hotkey or selecting this item from the main menu in the system tray.

## Installation and Execution

Application **does not require any special installation** and may be run directly from any location.
It's holding its configuration parameters in the system registry in the key **HKEY_CURRENT_USER\Software\ScreenShooter**
