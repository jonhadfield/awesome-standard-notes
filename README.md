# Awesome Standard Notes
A curated list of tools and information relating to [Standard Notes](https://standardnotes.com/).

Please take a look at the [contribution guidelines](CONTRIBUTING.md) before suggesting any changes. You can also have your extension hosted by the [official plugins directory](https://github.com/standardnotes/plugins).

## Status Labels

This list includes projects in various maintenance states. Labels help you understand project availability:

- **[Archived]** - Read-only repository, no longer maintained by the original author
- **[Unmaintained]** - Repository is dormant but still accessible; may work but receives no updates
- **[v003 only]** - Only compatible with legacy Standard Notes protocol (pre-November 2020)
- **[May be unavailable]** - Link may be intermittently unavailable or moved

### Contents
- [Awesome Standard Notes](#awesome-standard-notes)
    - [Contents](#contents)
  - [Guides](#guides)
  - [Extensions](#extensions)
    - [Themes](#themes)
    - [Editors](#editors)
    - [Components](#components)
    - [Fonts](#fonts)
  - [Tools](#tools)
    - [Browser](#browser)
    - [Command Line](#command-line)
    - [Importers, Exporters, and Converters](#importers-exporters-and-converters)
  - [Libraries](#libraries)
  - [Servers](#servers)
  - [Clients](#clients)

## Guides
* [Standard Notes Help](https://standardnotes.com/help)
* [Self-Hosting Standard Notes](https://standardnotes.com/help/47/can-i-self-host-standard-notes)
* [Introduction to Plugins](https://standardnotes.com/help/plugins/intro)
* [Building a Theme Plugin](https://standardnotes.com/help/plugins/themes)
* [Self-Hosting Standard Notes on your own ARM Server like the Raspberry Pi](https://github.com/antonheitz/standard-notes-arm)
* [Self-Hosting Standard Notes Extensions with Docker-Compose](https://return2.net/dockerize-standard-notes-extensions/)
* [Install Standard Notes (AppImage) on Linux](https://www.tekbyte.net/integrating-standard-notes-into-linux/)
* [How to Host Standard Notes Themes](https://blog.gunderson.tech/29891/how-to-host-standard-notes-themes)
* [Creating Editor Extensions](https://randombits.dev/standard-notes/creating-extensions)
* [Installing Extensions](https://randombits.dev/standard-notes/installing-extensions)
* [Editor Extension Template](https://github.com/nienow/sn-extension-template) - Starter template for building Standard Notes editor extensions.

## Extensions

> Many of the extensions have outdated instructions in their README for where to install extensions. Go to Preferences -> General -> Advanced Options to install extensions.

### Themes
* [Dracula theme](https://github.com/dracula/standard-notes) - A dark theme for Standard Notes.
* [Serendipity Dark Theme](https://github.com/luisstd/sn-theme-serendipity-dark) - Dark theme based on the Serendipity theme.
* [Horizon Dark Theme](https://github.com/luisstd/sn-theme-horizon-dark) - Based on colors from the Horizon theme for VSCode.
* [Horizon Light Theme](https://github.com/luisstd/sn-theme-horizon-light) - Based on colors from the Horizon Theme for VSCode.
* [Gruvbox Dark Theme](https://github.com/christianhans/sn-gruvbox-dark-theme) - Based on colors from the gruvbox theme for Vim.
* [Monochrome Dark Theme](https://github.com/Parkertg/sn-theme-monochrome-dark)
* [Muted Dark Theme](https://github.com/ntran/sn-theme-muteddark) - Standard Notes dark theme with non-vivid, muted colors
* [Pure Black Theme](https://github.com/christianhans/sn-pure-black-theme) **[Unmaintained]** - Theme for Standard Notes. Optimized for OLED devices such as iPhone X.
* [Slate Theme](https://github.com/yithian/slate-theme/) - A Standard Notes theme with shady grey and mossy green highlights.
* [vscode-theme](https://github.com/marcolaux/sn-theme-vscode) - A theme for Standard Notes inspired by the VS Code Dark theme that is easy on the eyes.
* [vscode-theme](https://github.com/hyphone/sn-theme-vscode) **[Unmaintained]** - A theme for Standard Notes inspired by the VS Code Dark theme that is easy on the eyes.
* [Subtle Dark Theme](https://github.com/Parkertg/sn-theme-subtle-dark)
* [Subtle Light Theme](https://github.com/Parkertg/sn-theme-subtle-light)
* [One Dark Darker](https://github.com/eenpadvinder/standardnotes-theme-one-darker) - Based on the One Dark Darker theme for VS Code, with colored headings and some UI tweaks.
* [Tangerine Theme](https://github.com/shompoe/sn-orange) - Newly updated for SN 3.9.15 onward. New installation link. Please re-install
* [One Light Lighter](https://github.com/arturolinares/standardnotes-theme-one-lighter) - Based on One Dark Darker (listed above), but with a light background.
* [Standard Notes Writer](https://github.com/eenpadvinder/standardnotes-writer) - Distraction free writing with word count
* [Monospace for Markdown Editors](https://github.com/DanielNetoP/markdown-monospace) - Monospace font for Standard Notes markdown editors (Toggle on top of other themes)
* [Overcast Theme](https://github.com/nienow/sn-theme-overcast) - A simple grayscale theme.
* [Dark Sense Theme](https://github.com/xzrelay/sn-theme-dark-sense) - Perfect for writing in the dark.
* [Moss Theme](https://github.com/TheMany172/SN-Moss-Theme) - Mossy green with orange accents - dark theme.
* [Callisto Theme](https://github.com/lissy93/callisto-theme-standard-notes) - A dusty navy and teal color theme for Standard Notes.
* [Cobalt Theme](https://github.com/PASSK3YS/cobalt) - A blue inspired theme for Standard Notes.
* [Catppuccin Mocha](https://github.com/JoeC-Dev/SN-catppuccin-mocha) - Catppuccin Mocha theme for Standard Notes (also [Latte](https://github.com/JoeC-Dev/SN-catppuccin-latte), [Frappe](https://github.com/JoeC-Dev/SN-catppuccin-frappe), [Macchiato](https://github.com/JoeC-Dev/SN-catppuccin-macchiato)).

### Editors
> A comparison of selected text editors can be found [here](https://github.com/dataprolet/standard-notes-editor-comparison).
* [Official Extensions](https://github.com/standardnotes/plugins)
* [Org mode for Standard Notes](https://github.com/ryanpcmcquen/standardnotes_org_mode_editor)
* [Standard Notes Indent Editor](https://github.com/MaxLap/standard-notes-indent-editor)
* [Standard Notes Nimble Editor](https://hub.darcs.net/jandrew/sn-nimble-editor)
* [Append Editor](https://github.com/theodorechu/append-editor) - Append to your notes. Write GitHub Flavored Markdown via four different editing modes: Plain Textarea with spell check, in-line formatting provided by [CodeMirror](https://github.com/codemirror/codemirror5), what-you-see-is-what-you-get live formatting provided by the [Rich Markdown Editor](https://github.com/outline/rich-markdown-editor) developed by [Outline](https://www.getoutline.com/), and in-line syntax highlighting provided by the [Monaco Editor](https://github.com/microsoft/monaco-editor). In addition to GFM, the Plain Textarea, CodeMirror, and Monaco modes support KaTeX, table of contents, footnotes, in-line HTML, and emoji codes. The Monaco mode also supports autocompletion, search and replace, and syntax highlighting for over 60 programming languages. The Append Editor has built-in support for printing notes and per-note font sizes, font families, and custom CSS.
* [Standard Notes Nimble Editor](https://hub.darcs.net/jandrew/sn-nimble-editor) **[May be unavailable]**
* [Append Editor](https://github.com/theodorechu/append-editor) - Append to your notes. Write GitHub Flavored Markdown via four different editing modes: Plain Textarea with spell check, in-line formatting provided by [CodeMirror](https://github.com/codemirror/codemirror), what-you-see-is-what-you-get live formatting provided by the [Rich Markdown Editor](https://github.com/outline/rich-markdown-editor) developed by [Outline](https://www.getoutline.com/), and in-line syntax highlighting provided by the [Monaco Editor](https://github.com/microsoft/monaco-editor). In addition to GFM, the Plain Textarea, CodeMirror, and Monaco modes support KaTeX, table of contents, footnotes, in-line HTML, and emoji codes. The Monaco mode also supports autocompletion, search and replace, and syntax highlighting for over 60 programming languages. The Append Editor has built-in support for printing notes and per-note font sizes, font families, and custom CSS.
* [Flashcard Editor](https://github.com/TheodoreChu/flashcard-editor)
* [Marp Editor](https://github.com/TheodoreChu/marp-editor) - Create presentation slides with [Marp](https://marp.app) and [Marpit Markdown](https://marpit.marp.app/markdown).
* [Music Editor](https://github.com/TheodoreChu/music-editor) - Write music with [VexTab](https://github.com/0xfe/vextab) and [VexFlow](https://github.com/0xfe/vexflow).
* [Rich Markdown Editor](https://github.com/arturolinares/sn-rme) - The awesome editor developed by [Outline](https://www.getoutline.com/). Supports tables, YouTube embeds and text highlights.
* [Tui Markdown Editor](https://github.com/MortalHappiness/sn-tui.editor) - A markdown editor using [Toast UI Markdown Editor](https://github.com/nhn/tui.editor).
* [Scratch](https://dylanonelson.github.io/sn-scratch-editor/) - Scratch includes most of the text editing features you would expect for taking notes, like lists, checkboxes, basic text formatting, smart copy/paste, and hotkeys.
* [Kanban Board](https://github.com/tryonlinux/kanban-board-sn) - A simple Kanban style board editor for Standard Notes.
* [Kanban Editor](https://github.com/corvec/sn-kanban-editor) - Kanban Editor for Standard Notes. It integrates rcdexta/react-trello, a Kanban board editor, and saves your notes in Markdown so that you can easily read them, export them, etc.
* [Scratch](https://dylanonelson.github.io/sn-scratch-editor/) **[May be unavailable]** - Scratch includes most of the text editing features you would expect for taking notes, like lists, checkboxes, basic text formatting, smart copy/paste, and hotkeys.
* [Kanban Board](https://github.com/tryonlinux/kanban-board-sn) **[Archived]** - A simple Kanban style board editor for Standard Notes.
* [Kanban Editor](https://github.com/corvec/sn-kanban-editor) - Kanban Editor for Standard Notes. It integrates rcdexta/react-trello, a Kanban board editor, and saves your notes in Markdown so that you can easily read them, export them to Listed, etc.
* [Home Inventory](https://github.com/tryonlinux/Home-Inventory-sn) - An extension editor for Standard Notes to catalog home inventory (great for insurance purposes) in a solid and secure way.
* [Coin Inventory](https://github.com/tryonlinux/Coin-Inventory-sn) - An extension editor for Standard Notes to catalog coin inventory in a solid and secure way. Numismatists rejoice!
* [Precious Metals](https://github.com/tryonlinux/Precious-Metals-Inventory-sn) - An extension editor for Standard Notes to keep track of what precious metals you have and their values.
* [Savings Goal Tracker](https://github.com/tryonlinux/savings-goals-editor-sn) - This is an editor for Standard Notes that allows you to track your savings goals within the app. You can add your goals and prioritize them by dragging and dropping them in the order you wish.
* [Whiteboard](https://github.com/antonheitz/sn-whiteboard) - This editor utilizes TLDraw to enable you to freely draw and write, add sticky notes and shapes. Works on Desktop and Mobile.
* [Excalidraw](https://github.com/nienow/sn-excalidraw) - A drawing/sketching editor that uses the Excalidraw library.
* [Quill](https://github.com/nienow/sn-quill) - A rich text editor that uses the Quill library.
* [Cosmos](https://github.com/nienow/cosmos) - Split a note into multiple areas. Each area can use a different editor. Install new editors more easily.
* [Mermaid](https://github.com/nienow/sn-mermaid) - A diagram editor. Create Flow, Sequence, Class, State, Gantt, Pie, ER, User Journey, Git, Mindmap, or Quadrant diagrams.
* [IronCalc](https://github.com/iamanaws/sn-ironcalc) - Spreadsheet editor plugin for Standard Notes, powered by IronCalc.

### Components
* [Pomodoro Timer](https://github.com/tryonlinux/pomodoro-sn/) - Pomodoro timer for Standard Notes in the Editor Bottom Bar


### Fonts
* [SF Pro Text](https://github.com/christianhans/sn-sf-pro-text-font)
* [JetBrains Mono](https://github.com/aiFdn/SN-JetBrains-Mono)

## Tools
### Browser
* [Page Link & Title → Note](https://github.com/mllocs/standard-notes-chrome-extension) - Takes the title and link of a web page and creates a note using the same title and inserts the link into the body.
* [Standard Notes Clipper](https://github.com/johnjones4/Standard-Notes-Clipper) **[Archived]** - A browser add-on (Firefox and Chrome) that allows you to clip web pages to your Standard Notes account. 🔻Please note this reported [issue](https://github.com/johnjones4/Standard-Notes-Clipper/issues/34)
* [Page Link & Title → Note](https://github.com/mllocs/standard-notes-chrome-extension) **[Unmaintained]** - Takes the title and link of a web page and creates a note using the same title and inserts the link into the body.

### Command Line
* [standardnotes-fs](https://github.com/tannercollin/standardnotes-fs) **[Archived]** - Mount your Standard Notes account as a filesystem and edit your notes as plain text files. **Note: No longer functional.** <sub><sup>([SN version 003 only](VERSIONS.md "Not compatible with version 004 accounts: those created or upgraded after Nov 2020"))</sub></sup>
* [sn-cli](https://github.com/jonhadfield/sn-cli) - Manage notes, tags, and other account operations
* [sn-dotfiles](https://github.com/jonhadfield/sn-dotfiles) - Sync and manage dotfiles using Standard Notes
* [Open Extended](https://github.com/kylejbrk/standard-notes-open-extended) - Community-hosted catalog of Standard Notes extensions (install via external package URL).
* [Extensions Server](https://github.com/sentriz/standardnotes-extensions) - Auto-updating Docker/Go server for hosting Standard Notes extensions.
* [MCP Standard Notes](https://github.com/lozit/mcp-standardnotes) - MCP server for Standard Notes with end-to-end encryption.
* [Extensions Repository Builder](https://github.com/iganeshk/standardnotes-extensions) **[Archived]** - Host Standard Notes extensions on your own server.

### Importers, Exporters, and Converters
* [Day One => Standard Notes Importer](https://github.com/ArneTR/standardnotes_day_one_importer) - Day One JSON Export Importer for Standard Notes
* [Google Keep™ to StandardNotes Converter](https://github.com/vantezzen/Google-Keep-to-Standardnotes-Converter) **[Archived]** - Convert Google Keep Takeout archive into Standardnotes archive
* [simplenote2standardnote](https://github.com/edas/simplenote2standardnote) **[Archived]** - Port a SimpleNote backup to a StandardNote one, keeping dates and tags
* [onestandard](https://github.com/oxhacks/onestandard) - Convert notebooks from OneNote into Standard Notes format.
* [notexfr](https://github.com/rafaelespinoza/notexfr) - notexfr is a tool to convert and adapt data for transfer between note-taking services
* [Google Keep to Standard Notes nodeJS converter](https://standardnotes.com/help/35/how-can-i-import-my-notes-from-google-keep) - Simple NodeJS script to convert a Google Keep Takeout export into a decrypted Standard Notes backup (Now part of StandardNotes).
* [Jimmy](https://github.com/marph91/jimmy) - Convert notes from many apps (including Standard Notes) to Markdown.
* [evernote2md](https://github.com/wormi4ok/evernote2md) - Evernote2md is a CLI tool to convert Evernote notes exported in *.enex format to a directory with markdown files.
* [Aegis to TokenVault](https://gist.github.com/kahnwong/e94933bb80888e4b7f75df4d90645cbe) - Export secret keys and account info from Aegis, then use this python script to format it into something the TokenVault Editor can use.
* [Yarle - The ultimate converter of Evernote notes to Markdown](https://github.com/akosbalasko/yarle) - A fully configurable cross-platform desktop application to convert your Evernote notebooks (enex files) to Markdown format.
* [Standard Notes Folder Export CLI](https://github.com/BrunoBernardino/standardnotes-folder-export-cli#standard-notes-folder-export-cli---deno) **[Archived]** - Simple CLI script to convert a decrypted Standard Notes Backup/Export into a structure of `<tag>/<note-title>.<file-extension>`.
* [Standard Notes export to folder](https://github.com/danielnetop/sn-export-to-folder) - CLI tool to extract info from the Standard Notes decrypted export and transform it into folder based tags and notes. After the tool runs the tags will be folders and each note will be inside the respective folder.
* [BB10 Remember → Standard Notes plaintext(/super note) import format Converter](https://github.com/jayb-g/bbrem2sn) - A simple python program to convert BlackBerry10 Remember Notes backup(backed-up using Runisoft Ultimate Backup on BB10) to Standard Notes importable format with preserved formatting, attachments and timestamps.

## Libraries
* [gosn-v2](https://github.com/jonhadfield/gosn-v2) - A library written in Go
* [Standard File Client Library](https://pkg.go.dev/github.com/mdouchement/standardfile/pkg/libsf) - A library written in Go

## Servers
* [Official Sync Server](https://github.com/standardnotes/server) - The official Standard Notes sync server (self-hostable).
* [Yet Another Standardfile](https://github.com/mdouchement/standardfile) - A Standard Notes Server implementation written in Go

## Clients
* [Official App](https://github.com/standardnotes/app) - Official Standard Notes clients (web, desktop, and mobile).
* [Iridium](https://codeberg.org/baarkerlounger/Iridium) - A local-first client written in Rust and GTK, with support for any server and offline editing (Codeberg fork; original GitHub repo is archived).
* [Flatpak](https://flathub.org/en/apps/org.standardnotes.standardnotes) - An unofficial Flatpak build.
