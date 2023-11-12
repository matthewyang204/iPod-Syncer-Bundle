# iPod-Syncer-Bundle
A bundle that allows you to sync small pieces of information to older iPods. Apple no longer officially supports syncing Contacts, Notes, and Calendars. This bundle so far contains an app that syncs contacts and an app that syncs notes. I am working on calendars.

Latest version: 1.0

Download here:
https://github.com/matthewyang204/iPod-Syncer-Bundle/releases/download/1.1/Install.iPod.Syncer.1.1.dmg

Requirements:
macOS 10.13 or later
iPod Classic/Nano/Mini (Touches are not supported)
iCloud account (iPod Notes Syncer needs your notes to be stored in iCloud)

To install:
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
7. A TextEdit window will open; wait 5 seconds and it will disappear. (The tool copies to another text file that is completely re-compiled and writes it to your iPod's disk) After it disappears, wait 3 seconds, depending on the speed of your iPod because it needs to write a new file to your iPod. Afterward, you can eject the iPod or go through this process to sync another note.

To clear the Notes folder:
1. Open Folder Eraser. It comes in the bundle. However, you can use the separate app if you installed it from my Github repository.
2. Select the "Notes" folder on your iPod's disk. Use step 3 in the guide on iPod Notes Syncer, but use the prompt given by Folder Eraser.
3. Click "Choose".
4. Empty the trash.
