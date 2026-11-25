OF ME — VERSION 0.2 · THE HANDMADE EDITION
A private, phone-first archive of the things that make me.

INSTALL ON YOUR IPHONE (GITHUB PAGES)
1. Unzip Of-Me-v0.2.zip on your Mac. Keep the files together.
2. In GitHub, create a repository called of-me. Free personal GitHub Pages generally requires a public repository. Only upload the app files in this ZIP, NEVER your own photos, backups, or media.
3. Upload the files inside the extracted folder to the repository root. index.html must be at the top level, not inside a second folder. Commit changes.
4. In the repository, open Settings > Pages. Under Build and deployment, select Deploy from a branch > main > /(root) > Save.
5. When GitHub provides your published URL, open it in Safari on your iPhone. Share > Add to Home Screen. Enable Open as Web App if offered, then Add.
6. Launch the new Home Screen icon. Enter test data only at first; Safari and the installed app may have separate local storage.

FIRST USE
• Threads: create a thread, customize its cover, colour and icon; open it to select, move, duplicate, remove, delete or rearrange keepsakes. A keepsake can belong to many threads. Add to Threads shares a single keepsake; Duplicate creates an independently editable record and may use extra storage. Delete sends the item to Recently Deleted across all threads. Deleting a thread retains its keepsakes.
• Keep: paste a link or attach an image/video/audio file. Pick multiple threads and reusable tags. Reflections and feelings are optional. Edit a keepsake later or add dated reflections. The original upload date remains unchanged.
• Mirror: add photos from the phone, text, motifs or keepsakes to a portrait; drag pieces, change width and rotation, change layering, save dated snapshots, export a JPG. Music/video keepsakes appear as a title or still image, not playing media. In view mode, linked pieces can open their keepsake.
• Settings: personalize the welcome, photo, paper colour, grain, feathering and icons. Enable online fonts if you want Cormorant Garamond and Inter; the default uses device fonts without external font requests.
• External media: link previews/titles are best-effort. YouTube, TikTok, Spotify and SoundCloud title retrieval is attempted via provider endpoints; CORS, private posts and provider restrictions can prevent it. YouTube thumbnails and its optional embedded player load only on request. Other sources can use a manually entered title and custom preview photo. External playback may have recommendations. Downloaded files can play offline when the device supports their format; links cannot guarantee preservation.

SHORTCUT (reliable capture via iCloud Drive)
1. In Files, create an iCloud Drive folder called Of Me Inbox.
2. In Shortcuts, create Save to Of Me. Enable Show in Share Sheet. Accept URLs and text.
3. Add Get URLs from Input (Shortcut Input).
4. Add Text containing the URLs magic variable.
5. Add Current Date, Format Date (custom yyyyMMdd-HHmmss-SSS), then Set Name (the Text result; use the formatted date followed by .txt).
6. Add Save File (the renamed Text result), choose Of Me Inbox, turn off Ask Where to Save. Avoid overwrite.
7. From a source app, Share > Save to Of Me. In Of Me, Settings > Import shared files, select the text files. Duplicate exact links are skipped. Imported links start with a generic title; open a keepsake and use Find title & preview if available.
8. For photos or permitted downloaded videos, attach in Keep or use a separate shortcut accepting images/media with Save File to the same folder. Retain the file extension.
The shortcut does not write directly into the Home Screen web app database. A direct Safari-only URL capture is possible via ?save=ENCODED_URL, but avoid mixing storage contexts. Action names may differ slightly by iOS version.

PRIVACY & BACKUPS
• Data is stored in IndexedDB on this device, not GitHub. No account, server database, analytics, automatic sync, or extra encryption/app lock. An unlocked device can access the archive. Source code and the provided wheel reference are public if published on a public repo. No personal reference photos are bundled.
• Optional external requests for metadata, online fonts, thumbnails and YouTube playback go to those providers. Reflections are not sent. Disable auto metadata in Settings if you prefer no automatic external requests.
• Export a complete JSON backup from Settings. Move the downloaded backup into a private iCloud Drive folder. Restore REPLACES the current archive after confirmation, so export first if needed. Backups include attached media and portrait photos; large backups may be memory intensive. Keep independent copies of irreplaceable media in Files.
• The app shell is cached after a successful online launch. Browser storage can be evicted, cleared, or lost if the app is removed. Keep copies and test restore before deleting originals. No automatic iCloud sync or backup scheduling is included.

RELIABILITY CHECK (before transferring your archive)
1. Create two threads and save a test photo to both. Try moving/duplicating it and changing the order.
2. Attach a permitted downloaded test video. Close and reopen the app, confirm it plays, then test in airplane mode. Do not delete your original until this succeeds AND you have a backup.
3. Export a backup to Files and verify that it exists. Restore it while you have only test data, then check media, tags, threads and portrait snapshots.
4. Test the shortcut using a single link. Import it from Files. Test title retrieval and preview separately.
5. If any test fails, retain your original files. Report what you saw before importing your collection.

Validation: JavaScript syntax checks and static rendering/logic checks completed. The test environment blocked browser navigation, so iPhone and end-to-end browser testing are not yet verified.
