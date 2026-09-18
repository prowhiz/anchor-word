# Changelog

What changed in each release of Anchor Word, newest first. The heading is the
version and build number exactly as **Settings → About** shows them, which is
what to quote when something is wrong.

## 0.5.0 (build 10) — 18 September 2026

Settings has been rebuilt: a short page of contents, with a page for each
thing it covers. The gear at the top of the reader, the Library and Search
opens it.

- **Reading & display** holds every reading setting, with a passage above them
  that changes as you do, and one reset. The reset no longer changes the
  translation you are reading.
- **Resources** replaces Storage. Every translation and study tool opens onto
  a page of its own, which says what it is, what it works with and whose it
  is. That page is where you remove it, with Undo straight after.
- **Put your translations in your own order**, by dragging, under Resources →
  Translation order. The translation menu, Compare and Search list them that
  way. The order stays on this phone.
- **Rename an imported translation** from its page: its name, abbreviation,
  language and licence. Quotes already in your notes keep the old
  abbreviation.
- **Sync is set up a step at a time**, one choice to a page, and back undoes
  the last one. Moving your library by hand is now "Send a file", offered
  while sync is off.
- **Backup & export share a page.** A backup is always everything. Export makes
  one file of your notes, highlights and bookmarks: whichever you tick.
- **Sources & licences** credits every text and tool on the phone.
- **Back goes one step**, to the page you came from and to the same place on
  it, whether you use the arrow or your phone's back.

From a note:

- **Read a note's passage in context.** Tap the passage the note is anchored
  to, or a reference in its text, and choose Read in context. Back to note
  brings you home.
- **Two ways into scripture.** In the formatting row, the open book now goes to
  the reader, at the chapter you last read, and a new search button goes to
  Search, taking the words you had selected with it. Link puts the reference
  in place of the words you searched for; Quote puts the passage after them.

And smaller things:

- **The translation menu shows when there is more below**, with a fade and a
  scroll bar, and only when there is. Its last row, Manage translations, opens
  Resources.
- **An import that marks no words of Christ says so** before it is built, so
  you know it is the file and not the app.
- **Messages say how it went**: a green check when a backup, export, import or
  update finishes, and a red mark when something you asked for fails.
- **The status bar follows the app's theme**, not the phone's, so the clock
  stays readable in the dark theme on a light phone.

Nothing in your library changes when you update, and this build still syncs
with a device on 0.4.0.

## 0.4.0 (build 9) — 17 September 2026

Your phone and your tablet can hold the same library now. Everything is under
Settings → Sync with another device.

- **Sync through a folder.** Choose a folder, and point a sync app —
  Syncthing, or FolderSync — at the same folder on each device. Anchor Word
  leaves its library there and brings in the others' whenever it opens, comes
  back, or has something new.
- **Or sync with your own server**: sign in to Nextcloud in your browser, or
  give the address and account of another WebDAV server. The server needs an
  https address. Anchor Word gets an app password from Nextcloud, which it
  takes back when you stop syncing.
- **A sync phrase keeps the copies private.** The first device makes one and
  shows it once: write it down, and type it on each other device when you set
  it up. Without it nobody can open what is in the folder or on the server.
- **Notes, highlights, bookmarks, folders and your reading settings travel.**
  Downloaded translations and imported texts stay on the device that has them,
  and so do the text size, true black and the translation you are reading.
- **A note written in on both devices is kept twice**, the other copy named
  "(from …)" after the device it came from, and the app says so.
- **Name each device** on the same screen, so the others know what to call it.
- **Or send your library by hand**, as one file, and bring it in on the other
  device.
- **"Licences · text sources" is now "Where the texts come from"**, and no
  longer lists as planned a source that is already in the app.

The first time this build opens, your library is updated so that devices can
tell who changed what. A backup made before updating can be restored into
this build if you ever need to.

## 0.3.1 (build 8) — 16 September 2026

- **The translation menu shows five translations and scrolls the rest.** With
  several texts on the phone it filled the screen; now it is a short list under
  the chip, with "More translations" below it as before.

## 0.3.0 (build 7) — 16 September 2026

The app looks like itself now, and the translation menu works with a long
list.

- **Its own icon**, an anchor, on the home screen and in the app switcher. On
  Android 13 and later it takes the tint of your wallpaper along with your
  other icons, if you use themed icons.
- **A launch screen** with the same anchor and the app's name, in the app's own
  background — the light one or the dark one, following your phone.
- **The translation menu scrolls.** With several texts imported, the list ran
  past the bottom of the screen and the rows down there couldn't be reached,
  "More translations" among them. The list now scrolls, and that row stays
  below it.

## 0.2.0 (build 6) — 16 September 2026

Bring your own Bible: this build reads translation files you already have.

- **Settings → Manage downloads → Import a translation.** Pick a Zefania XML,
  OSIS or USFX file, zipped or not, in any language. The app reads it on the
  phone, with nothing sent anywhere.
- **It shows you what is in the file before it keeps anything**: how many books
  and verses, anything left out and why, where its numbering differs from the
  app's, and what script it is written in. You give it a name and an
  abbreviation, and those are what the menu and every citation show.
- **An imported text then reads like any other.** It is in the translation
  menu, in Compare and in search, and its verses copy, share and quote into
  notes.
- **Remove takes one away**, with eight seconds to undo. Your notes,
  highlights and bookmarks are kept separately and outlive any text you remove.
- Encrypted files are refused, and only import a text you have the right to
  use. An imported text stays on this phone: it is never uploaded, exported or
  included in a backup.

Also:

- **The app has its own icon**, and a launch screen to match.
- **The translation menu lists what is on the phone**, with one row leading to
  the rest, instead of a list of everything with most of it dimmed.
- **Settings → Feedback** sends a report, with the build details filled in, and
  offers to send them after a crash.

## 0.1.0 (build 5) — 15 September 2026

The first build for testers.

- Read the King James Version, which comes with the app and works offline.
  More translations download from Settings → Manage downloads.
- Highlight verses in five colours, keep a bookmark in each book, and write
  notes attached to a verse or passage, filed in folders if you like.
- Find it again: the Library lists your notes, highlights and bookmarks, and
  Search looks through the Bible and your notes.
- Cross-references, a verse compared across translations, and the Hebrew and
  Greek behind a word, each from a download.
- Settings → Backup saves your whole library to one file and restores it on
  another phone or a fresh install. Back up before you ever uninstall.
