# NoteS

A desktop app for whiteboards, notes and documents, novels included. Everything lives in **Spaces**: ordinary folders on your computer, so your files stay yours and work with any backup or sync you already use.

This repository holds NoteS's releases: its installers, and the updates installed copies download.

## Install

Download **NoteS-Setup-x.x.x.exe** from the [latest release](https://github.com/lucasboschiroli/NoteS_public/releases/latest) (under **Assets**) and run it. NoteS updates itself when a new version is released: it downloads in the background and installs when you restart (or the next time you close it).

> Windows may show "Windows protected your PC" because the installer isn't code-signed. Click **More info → Run anyway**.

## What it does

**Whiteboards** (`.wboard`): an infinite canvas with shapes, arrows, text, pictures and drawing.

**Notes** (`.snote`): quick notes with headings that fold, checklists, tables, pictures, drawings, fonts and colours.

**Documents** (`.sdoc`): real pages, like Word or Google Docs.
- Page size, margins, page numbers, headers and footers
- Footnotes, tables, pictures, links, special characters
- A Contents panel that follows your headings
- Export to PDF (exactly as on screen) and Word

**Novels**, a kind of document made for books:
- A binder with front matter, parts, chapters (prologue, interlude, epilogue too) and back matter
- Manuscript pages (the format agents and publishers ask for) or book pages, switchable any time
- Scenes inside chapters, with status, point of view and a summary
- Snapshots: keep a chapter as it is, compare later versions with it, or go back to it
- Word goals for the book and for each day, smart quotes and dashes
- Title page, cover, series, and the details stores ask for (ISBN, description, keywords)
- Exports: EPUB, a print-ready PDF (KDP, IngramSpark) with trim sizes, mirrored margins and running heads, the print cover (back, spine and front), PDF and Word

**Writing help**
- Spelling in the languages you choose, from Windows' own checker
- English grammar checking that runs on your computer (nothing is sent anywhere)

**Spaces**
- Any folder can be a Space; sub-folders show up in the sidebar
- Home lists everything, with filters, stars and search
- Back up a Space as a .zip whenever you want

## Your data

Your boards, notes and documents are files in your Spaces' folders. NoteS keeps its own list of Spaces and its settings in `%APPDATA%\s`.

## Built with

[Electron](https://www.electronjs.org/), TypeScript, [docx](https://github.com/dolanmiu/docx) (Word export), [Harper](https://github.com/Automattic/harper) (grammar), [electron-builder](https://www.electron.build/) and electron-updater.

## License

[MIT](LICENSE) © 2026 Lucas Salomão Boschiroli
