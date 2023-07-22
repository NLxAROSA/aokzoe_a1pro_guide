** AOKZOE Player Center not opening or not showing content, quick fix **

1. Microsoft Defender:
- Turn off *Memory Integrity*
- Memory integrity will block the app from opening
2. Regional formatting:
- The app is sensitive to regional formatting. Change the `Regional Format` in Windows to `Default`
- You can find the setting by searching for it via the Search function or by going into `Options` > `Time & language` > `Language & region` > `Regional format` and set it to `Recommended` or `English US`
3. Gamerzone folder corruption or errors
- Show hidden files (in Explorer: `View` > `show` > ensure `hidden files` is checked)
- Delete the Gamerzone folder, which is located at `C:/Users/<yourname>/AppData/Roaming/Gamerzone`

** If this is not sufficient, then follow the following steps as well **

1. Uninstall the Player Center app.
2. Delete the following folder: `C:/Users/<yourname>/AppData/Roaming/Gamerzone`
3. Delete the `C:/users/<yourname>/AppData/Local/aokzoe(or oxp) folder if it exists
4. Delete the `C:/Program Files/aokzoe(or oxp) folder if it exists
5. Restart Windows
6. Reinstall the Player Center app