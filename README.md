# iPod-Syncer-Bundle
A bundle that allows you to sync small pieces of information to older iPods. Apple no longer officially supports syncing Contacts, Notes, and Calendars. This bundle can sync those to older iPods on newer Macs.

Latest version: 1.0

Download here:
https://github.com/matthewyang204/iPod-Syncer-Bundle/releases/download/2.1/Install.iPod.Syncer.2.1.dmg

Requirements:
macOS 10.13 or later
iPod Classic/Nano/Mini (Touches are not supported)
iCloud account (iPod Notes Syncer needs your notes to be stored in iCloud)

To install or update:
1. Download the disk image.
2. Drag the folder (shows an iPod syncing) to the Applications folder alias. Your Mac may ask for your password, enter it if prompted. The app will now be in your Applications folder. You will be able to open this folder to access the apps inside.

To use iPod Contacts Syncer:
1. Make sure your iPod is connected and its main disk volume (formatted to MacOS Extended) is called iPod HD. If not, change it in Disk Utility.
2. Launch the app. If it asks for permissions, allow it. It may ask multiple times for different folders and contacts.
3. Empty the trash. (The app created some temp files in a folder and trashed the folder to clean up after itself)

To use the iPod Notes Syncer:
1. Make sure that your note doesn't contain any bullet points or dash points. The tool doesn't play well with these text formats. Remove them if there are any present. Also, the tool will remove the following formats: Bold, Italics, Underlines, and Slashes (crossouts). This is done when the file is re-compiled into UTF-8 encoded format so that the iPod can read them.
2. Launch the app from your Launchpad.
3. In the prompt, select one note you want to sync (you can only sync 1 note at one time)
4. In the second prompt, select your Downloads folder.
5. Wait 15-100 seconds for another prompt to appear. (The JavaScript takes a while to find your note and export it as a .txt file containing HTML formatting, depending on the speed of your Mac.) If 100 seconds have gone by and you still don't see the prompt, go to mission control and search for it.
6. In the third prompt, select the .txt file with the same name as the note we exported.
7. A TextEdit window will open; wait 5 seconds and it will disappear. (The tool copies to another text file that is completely re-compiled and writes it to your iPod's disk) After it disappears, look at the leftmost of your menu bar icons. If you see a rotating gear, wait until it disappears. Afterward, you can eject the iPod or go through this process to sync another note.

Note: Your Mac may ask you permission multiple times through this process. Always allow it, or else the tool won't get the proper data and won't be able to execute properly.

To use iPod Calendar Syncer:
1. Export your calendar as a .ics file. Mac Calendar: File > Export... After you click "Export...", select a location on your drive, such as the Downloads folder.
2. Launch the iPod Calendar Syncer and select the .ics file.
3. Click "Choose".

To use the iPod Txt Exporter:
1. Follow steps 6 and 7 in the iPod Notes Syncer instructions. Be sure to select the .txt file that you want to export to your iPod's notes folder.

Note: Your Mac may ask you permission multiple times through this process. Always allow it, or else the tool won't get the proper data and won't be able to execute properly.

To clear the Notes folder:
1. Launch iPod Notes Eraser.
2. Empty the trash.
