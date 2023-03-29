## Version 0.8.9
- Among many smaller improovements, project groups have been added:
![image](https://user-images.githubusercontent.com/62482747/228671786-5ecab1a8-9279-41f1-874c-5fefa376a55f.png)<br>
![image](https://user-images.githubusercontent.com/62482747/228671802-bcf446a6-8b77-4df5-9144-f653894a1530.png)<br>
- You can also now drag-n-drop projects in the main screen to reorder them and move them between groups.

## Version 0.8.8
- Added an interface to edit envinronment variables<br>
![image](https://user-images.githubusercontent.com/62482747/228053223-275901f4-bb29-48a3-b8c0-28549b37b620.png)
- Misc tools like database benchmark added
- Migrated to a different DB system, only to add automatic saving instead of intervals, but the performance and disk space waste may have worsened. There may be a way to switch later.
- Polished treeview - now sadly due to the changes the connector lines have been temporarily removed, but more features have been added and more like virtual scrolling optimisation are awaiting.


## Version 0.8 (New)
Changelog for newer versions is comming soon.<br>
![image](https://user-images.githubusercontent.com/62482747/226109061-c1180ab0-f3d9-4f8c-a9b3-f86b2262a9cb.png)

<hr>

### (From now onwards, there will be the old legacy releases.)<br>

<hr>

## Version 0.4 B235 (Legacy)
0.4 B235 is the last version from the legacy releases.<br>
There doesn't appear to be an official changelog for 0.4, but it was a fairly big update, introducing upgrades around the treeview (and overall file manager), builder, font manager, and overall features.<br>
It also handeled previews for many kinds of formats.<br>
It also is the last version to be able to run standalone on the web.<br><br>
![image](https://user-images.githubusercontent.com/62482747/226108947-383010b9-e5e2-40e3-b6a4-83eecd5ff70b.png)

## Version 0.3 B0
- Download for save/export screen
- You can now open the save file directly
- Added more /l# tags to fix issues with special characters
- Fixed html encoding issue while copying
- Windows got better look and few small improovements
- Multi file and site support
- Quick addons support, for example in HTML @clr(red)...clr/ makes red text. More in QA doc.
- Anchors @anch(name)anch/ - makes an anchor in that place. Use href="#name" to scroll onto it
- Small GUI updates
- Completly remade the WDSP to now support multiple files at once
- Editor now has its toolbar
- Editor has now fulscreen mode and multi instances support
- Added side editor instance for documents
- Added tags. Useful.
- We fixed a lot 🕷

## Version V0.2 B09
- Reduced loadtime by 50%
- "About" now shows actual running verzion
- Added more font presets + added "family=" alias (f=)
- Some changes to plugin manager
- For addon devs: Custom addons can now create multiple windows and can change their size.<br>
![image](https://user-images.githubusercontent.com/62482747/226108599-a5102e15-389e-44dc-95f2-764fa5b8b305.png)

## Version V0.2 B08
- Some changes and fixed to loader
- Loader now checks for what verzion was the project made.
- UI changes: Added custom scrollbar, added icons
- Experimenting with themes

## Version V0.2 B07
- Added toolbar to top of the screen
- Added 8 more font presets
- Bugfixes
- Fixed random console errors
- Fixed saving copy

## Version V0.2 B06
- Fixed errors when using backslahes \ in code
- Fixed project corruptions when adding " or \ to title/name/any user-input value
- The entire app will now disapear completly until it loads. If JS is not enabeled, app wont show up at all.
- Support for global CSS/JS
- Editor now supports multiple languages
- Monaco editor is now automaically resied when window size changes

## Version V0.2 B05
- Major CDN fixes and improovements from our side
- Plugin presets from dropdown are now gone: say hello to pluin manager
- Added undo/redo
- Added extra settings

## Version V0.2 B04
- Major bugfixes
- Added 3 font presets
- Fixed title and favicon in build output
- Now automatically detets wich format is favicon in and sets the output automatically.
- Monaco implementation fixes and upgrades<br>
![image](https://user-images.githubusercontent.com/62482747/226108641-6d0ca468-49f4-42fd-95fe-b5f468635fdc.png)

## Version V0.2 B03
- Few UI improovements
- Say goodbye to NJSSH editor that caused alot of trouble. Introducing Monaco.

## Version V0.2 B02
- Say goodbye to textarea - we are implementing NJSSH (Our editor made in pure JS).
  (This editor is not meant to be implemented this way and is in active development, so if you see
  any bugs or have any issues please report in our ticket channel)
- You can now setup favicon

## Version V0.2 B01
- Fixes

## Version V0.2 B0
- Added "about"
- Added default "introduction" doc
- Warning when exiting the app
- App will now remain working afrer going offline (Not yet working fully offline tho)
- Source code for 0.2 released

## Version V0.1 B0298 [>B0132]
- Added plugins
- Added better font manager
- Added title setup
- Window bugfixes
- Fixes

## Version V0.1 B0131 [>B0011]
- Fixes (a ton)
- Load/Save/build functions introduced
- WDSP format now supports subcategories
- GUI changes
- Introduces windows
- Introduced toasts (little quick messages appearing in the bottom of the screen)

### -- 0.1 B0 and older weren't recorded and are lost to time --
