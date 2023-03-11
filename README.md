-------------------------------------------------------------------------------------------------------------------------------------------

# notificationsBeGONE for macOS
#### Read this text in: [Polish :poland: ](https://github.com/karolpszo/notificationsbegone/blob/main/README-pl.md) | [German/Deutsch :de:](https://github.com/karolpszo/notificationsbegone/blob/main/README-de.md)
+ **notificationsBeGONE is a very lightweight :feather: AppleScript program that eliminates all of the notification popups on macOS in a single click.**
+ **This software is intended for those who experience the LoginItems popup bug or who have too many notifications on their Macs.**
+ **You can launch this program from Programs using a folder or Spotlight, or you can add it to macOS' Login Items to make it work after login.**
### Please leave a star :star: on this software if it meets all of your needs.
![applogo](https://i.imgur.com/mnm2GrD.png)

-------------------------------------------------------------------------------------------------------------------------------------------
## Main problems, issues and to-do tasks:
- [x] :green_square: :hammer: Software won't close notifications on macOS with Polish language set (Issue #1)
- [x] :green_square: :hammer: Change word "Schlie§en" to "Schließen" in notificationsbegone.scpt and notificationsBeGONE.app (Issue #2)
- [ ] :pen: Add more languages 
-------------------------------------------------------------------------------------------------------------------------------------------

## Important news :newspaper: :warning:
> When you'll look :eyes: into notificationsbegone.scpt file, in line 8:
```
if description of _action is in {"Schlie§en", "Alle entfernen", "Zamknij", "Close", "Clear All"} then 
```
> You'll see, that this software works only in 3 macOS System languages: **German, Polish and English.** I want to make this software available for all of the GitHub and Macs community, so if you want to help with software translation, open an Issue with your fix.
### What do I need?! The only thing I need is translation of a word, that closes notifications.
![a](https://user-images.githubusercontent.com/111112623/224505336-015febd8-0c16-4b8d-810a-3369b2ed8e2b.png) 
#### In English :gb:, it is **close**,   in Polish :poland: - **Zamknij**,    and in German :de: - **Schließen**.
-------------------------------------------------------------------------------------------------------------------------------------------
