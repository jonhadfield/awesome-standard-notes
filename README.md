# Awesome Standard Notes [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of tools and information relating to [Standard Notes](https://standardnotes.com/).

[Contribution guidelines](CONTRIBUTING.md) · [Official plugins](https://github.com/standardnotes/plugins) · [Discord](https://discord.gg/9VNW3kK554)

## Contents

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
- [Status Labels](#status-labels)

## Guides

- [Standard Notes Help](https://standardnotes.com/help) - Official help center.
- [Self-Hosting Standard Notes](https://standardnotes.com/help/47/can-i-self-host-standard-notes) - Official self-hosting guide.
- [Introduction to Plugins](https://standardnotes.com/help/plugins/intro) - Official plugin development overview.
- [Building a Theme Plugin](https://standardnotes.com/help/plugins/themes) - Official guide to creating themes.
- [Self-Hosting on ARM / Raspberry Pi](https://github.com/antonheitz/standard-notes-arm) - Run Standard Notes on ARM hardware.
- [Self-Hosting Extensions with Docker Compose](https://return2.net/dockerize-standard-notes-extensions/) - Host community extensions with Docker.
- [Install Standard Notes (AppImage) on Linux](https://www.tekbyte.net/integrating-standard-notes-into-linux/) - Integrate the AppImage desktop client on Linux.
- [How to Host Standard Notes Themes](https://blog.gunderson.tech/29891/how-to-host-standard-notes-themes) - Host and install custom themes.
- [Creating Editor Extensions](https://randombits.dev/standard-notes/creating-extensions) - Walkthrough for building editor extensions.
- [Installing Extensions](https://randombits.dev/standard-notes/installing-extensions) - How to install third-party extensions.
- [Editor Extension Template](https://github.com/nienow/sn-extension-template) - Starter template for building editor extensions.

## Extensions

> Install custom extensions via Preferences → General → Advanced Options. Many project READMEs still show outdated install steps.

### Themes

- [Dracula](https://github.com/dracula/standard-notes) - Dark theme based on the Dracula color scheme.
- [Serendipity Dark](https://github.com/luisstd/sn-theme-serendipity-dark) - Dark theme based on Serendipity.
- [Horizon Dark](https://github.com/luisstd/sn-theme-horizon-dark) - Based on the Horizon VS Code theme.
- [Horizon Light](https://github.com/luisstd/sn-theme-horizon-light) - Light variant of the Horizon VS Code theme.
- [Gruvbox Dark](https://github.com/christianhans/sn-gruvbox-dark-theme) - Based on the gruvbox Vim theme.
- [Monochrome Dark](https://github.com/Parkertg/sn-theme-monochrome-dark) - Near-monochrome dark theme.
- [Muted Dark](https://github.com/ntran/sn-theme-muteddark) - Dark theme with muted, non-vivid colors.
- [Pure Black](https://github.com/christianhans/sn-pure-black-theme) **[Unmaintained]** - OLED-friendly pure black theme.
- [Slate](https://github.com/yithian/slate-theme/) - Shady grey with mossy green highlights.
- [VS Code Dark](https://github.com/marcolaux/sn-theme-vscode) - Inspired by the VS Code Dark theme.
- [Subtle Dark](https://github.com/Parkertg/sn-theme-subtle-dark) - Low-contrast dark theme.
- [Subtle Light](https://github.com/Parkertg/sn-theme-subtle-light) - Low-contrast light theme.
- [One Dark Darker](https://github.com/eenpadvinder/standardnotes-theme-one-darker) - Based on One Dark Darker for VS Code, with colored headings.
- [Tangerine](https://github.com/shompoe/sn-orange) - Orange-accented theme (updated for SN 3.9.15+).
- [One Light Lighter](https://github.com/arturolinares/standardnotes-theme-one-lighter) - Light counterpart to One Dark Darker.
- [Writer](https://github.com/eenpadvinder/standardnotes-writer) - Distraction-free writing look with word count styling.
- [Markdown Monospace](https://github.com/DanielNetoP/markdown-monospace) **[Archived]** - Monospace font overlay for markdown editors.
- [Overcast](https://github.com/nienow/sn-theme-overcast) - Simple grayscale theme.
- [Dark Sense](https://github.com/xzrelay/sn-theme-dark-sense) - Dark theme tuned for low-light writing.
- [Moss](https://github.com/TheMany172/SN-Moss-Theme) - Mossy green with orange accents.
- [Callisto](https://github.com/lissy93/callisto-theme-standard-notes) - Dusty navy and teal palette.
- [Cobalt](https://github.com/PASSK3YS/cobalt) - Blue-inspired theme.
- [Catppuccin](https://github.com/JoeC-Dev/SN-catppuccin-mocha) - Catppuccin flavors: [Mocha](https://github.com/JoeC-Dev/SN-catppuccin-mocha), [Latte](https://github.com/JoeC-Dev/SN-catppuccin-latte), [Frappe](https://github.com/JoeC-Dev/SN-catppuccin-frappe), [Macchiato](https://github.com/JoeC-Dev/SN-catppuccin-macchiato).

### Editors

Compare selected editors in the [editor comparison](https://github.com/dataprolet/standard-notes-editor-comparison).

#### General

- [Official Plugins](https://github.com/standardnotes/plugins) - Official and community plugins directory.
- [Indent Editor](https://github.com/MaxLap/standard-notes-indent-editor) - Outliner-style indenting editor.
- [Org Mode](https://github.com/ryanpcmcquen/standardnotes_org_mode_editor) - Org mode editor for Standard Notes.
- [Nimble Editor](https://hub.darcs.net/jandrew/sn-nimble-editor) **[May be unavailable]** - Lightweight text editor.
- [Append Editor](https://github.com/theodorechu/append-editor) - Append-focused Markdown editor with Textarea, CodeMirror, Outline RME, and Monaco modes.
- [Rich Markdown Editor](https://github.com/arturolinares/sn-rme) - Outline-based editor with tables, embeds, and highlights.
- [TUI Markdown Editor](https://github.com/MortalHappiness/sn-tui.editor) **[Archived]** - Markdown editor built on Toast UI Editor.
- [Scratch](https://dylanonelson.github.io/sn-scratch-editor/) **[May be unavailable]** - Rich text notes with lists, checkboxes, and hotkeys.
- [Quill](https://github.com/nienow/sn-quill) - Rich text editor based on Quill.
- [Cosmos](https://github.com/nienow/cosmos) - Split a note into multiple areas, each with its own editor.

#### Boards and diagrams

- [Kanban Board](https://github.com/tryonlinux/kanban-board-sn) **[Archived]** - Simple Kanban board editor.
- [Kanban Editor](https://github.com/corvec/sn-kanban-editor) - Kanban board that stores notes as Markdown.
- [Whiteboard](https://github.com/antonheitz/sn-whiteboard) - Freeform drawing and sticky notes via TLDraw.
- [Excalidraw](https://github.com/nienow/sn-excalidraw) - Sketching editor based on Excalidraw.
- [Mermaid](https://github.com/nienow/sn-mermaid) - Diagram editor for flow, sequence, Gantt, and more.
- [Marp Editor](https://github.com/TheodoreChu/marp-editor) **[Archived]** - Presentation slides with Marp / Marpit Markdown.

#### Specialty

- [Music Editor](https://github.com/TheodoreChu/music-editor) **[Archived]** - Write music with VexTab and VexFlow.
- [IronCalc](https://github.com/iamanaws/sn-ironcalc) - Spreadsheet editor powered by IronCalc.
- [Home Inventory](https://github.com/tryonlinux/Home-Inventory-sn) - Catalog home inventory securely.
- [Coin Inventory](https://github.com/tryonlinux/Coin-Inventory-sn) - Catalog coin collections.
- [Precious Metals](https://github.com/tryonlinux/Precious-Metals-Inventory-sn) - Track precious metal holdings and values.
- [Savings Goal Tracker](https://github.com/tryonlinux/savings-goals-editor-sn) - Prioritize and track savings goals.

### Components

- [Pomodoro Timer](https://github.com/tryonlinux/pomodoro-sn/) - Pomodoro timer in the editor bottom bar.

### Fonts

- [SF Pro Text](https://github.com/christianhans/sn-sf-pro-text-font) - Apple SF Pro Text font package.
- [JetBrains Mono](https://github.com/aiFdn/SN-JetBrains-Mono) - JetBrains Mono font package.

## Tools

### Browser

- [Page Link & Title → Note](https://github.com/mllocs/standard-notes-chrome-extension) **[Unmaintained]** - Create a note from the current page title and URL.

### Command Line

- [sn-cli](https://github.com/jonhadfield/sn-cli) - Manage notes, tags, and account operations from the terminal.
- [sn-dotfiles](https://github.com/jonhadfield/sn-dotfiles) - Sync and manage dotfiles with Standard Notes.
- [Open Extended](https://github.com/kylejbrk/standard-notes-open-extended) - Community-hosted catalog of installable extensions.
- [Extensions Server](https://github.com/sentriz/standardnotes-extensions) - Auto-updating Docker/Go host for extensions.
- [MCP Standard Notes](https://github.com/lozit/mcp-standardnotes) - MCP server with end-to-end encryption.

### Importers, Exporters, and Converters

- [Day One Importer](https://github.com/ArneTR/standardnotes_day_one_importer) - Import Day One JSON exports.
- [Google Keep Converter](https://github.com/vantezzen/Google-Keep-to-Standardnotes-Converter) **[Archived]** - Convert Google Keep Takeout archives.
- [Official Google Keep Import](https://standardnotes.com/help/35/how-can-i-import-my-notes-from-google-keep) - Official Keep → Standard Notes conversion help.
- [simplenote2standardnote](https://github.com/edas/simplenote2standardnote) **[Archived]** - Port Simplenote backups with dates and tags.
- [onestandard](https://github.com/oxhacks/onestandard) - Convert OneNote notebooks to Standard Notes format.
- [notexfr](https://github.com/rafaelespinoza/notexfr) - Convert and adapt data between note-taking services.
- [Jimmy](https://github.com/marph91/jimmy) - Convert notes from many apps (including Standard Notes) to Markdown.
- [evernote2md](https://github.com/wormi4ok/evernote2md) - Convert Evernote `.enex` exports to Markdown files.
- [Yarle](https://github.com/akosbalasko/yarle) - Configurable Evernote → Markdown desktop converter.
- [Aegis to TokenVault](https://gist.github.com/kahnwong/e94933bb80888e4b7f75df4d90645cbe) - Format Aegis exports for the TokenVault editor.
- [Folder Export CLI](https://github.com/BrunoBernardino/standardnotes-folder-export-cli#standard-notes-folder-export-cli---deno) **[Archived]** - Turn a decrypted backup into `<tag>/<note>.<ext>` folders.
- [Export to Folder](https://github.com/danielnetop/sn-export-to-folder) - Extract a decrypted export into tag folders and note files.
- [BB10 Remember Converter](https://github.com/jayb-g/bbrem2sn) - Convert BlackBerry 10 Remember backups to Standard Notes import format.

## Libraries

- [gosn-v2](https://github.com/jonhadfield/gosn-v2) - Go client library for Standard Notes.
- [Standard File Client Library](https://pkg.go.dev/github.com/mdouchement/standardfile/pkg/libsf) - Go client library for the Standard File protocol.

## Servers

- [Official Sync Server](https://github.com/standardnotes/server) - Official self-hostable sync server.
- [Yet Another Standardfile](https://github.com/mdouchement/standardfile) - Standard Notes–compatible server written in Go.

## Clients

- [Official App](https://github.com/standardnotes/app) - Official web, desktop, and mobile clients.
- [Iridium](https://codeberg.org/baarkerlounger/Iridium) - Local-first Rust/GTK client (Codeberg fork; original GitHub repo is archived).
- [Flatpak](https://flathub.org/en/apps/org.standardnotes.standardnotes) - Unofficial Flatpak package.

## Status Labels

Projects may include a maintenance label:

- **[Archived]** — Read-only; no longer maintained by the original author.
- **[Unmaintained]** — Dormant but still accessible; may work, receives no updates.
- **[v003 only]** — Only compatible with the legacy protocol (pre-November 2020). See [VERSIONS.md](VERSIONS.md).
- **[May be unavailable]** — Link may be intermittently unavailable or moved.

## Related

- [standardnotes.com](https://standardnotes.com/) — Product site and apps.
- [Protocol versions](VERSIONS.md) — Client/protocol compatibility notes.
- [Discord](https://discord.gg/9VNW3kK554) — Community chat.
