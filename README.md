# MacMD Viewer: a native Markdown viewer for Mac

MacMD Viewer opens `.md` files on macOS as formatted documents, with Mermaid diagrams, highlighted code, and a Finder Quick Look preview. It is read-only: it shows the file, your editor stays your editor. One-time purchase, $19.99.

**[Download the latest release →](https://github.com/macmdviewer/MacMDViewer/releases/latest)** · **[Website →](https://macmdviewer.com/?utm_source=github&utm_medium=readme&utm_campaign=macmdviewer_repo)**

> **About this repository.** MacMD Viewer is a commercial, closed-source app, so there is
> no source code here by design. This repository is its release channel: every version
> ships as a signed, notarized DMG attached to a [GitHub Release](https://github.com/macmdviewer/MacMDViewer/releases),
> which is also what the Homebrew cask and the app's Sparkle updater download. Bug reports
> and feature requests are welcome in [Issues](https://github.com/macmdviewer/MacMDViewer/issues).

## How to open a Markdown file on Mac

macOS has no built-in way to read a `.md` file as formatted text. Double-clicking one opens raw text in TextEdit or launches a full editor. With MacMD Viewer installed:

- **Double-click** a `.md` file: it opens rendered, with headings, tables, task lists, code, and diagrams.
- **Press Space** on a `.md` file in Finder: Quick Look shows the rendered document without opening any app.
- **Leave it open** while another app writes the file: the view reloads by itself when the file changes on disk.

## What it does

- **Renders GitHub-Flavored Markdown**: tables, task lists, fenced code, strikethrough
- **Mermaid diagrams**: flowcharts, sequence diagrams, and more, rendered offline
- **Syntax highlighting** for fenced code blocks
- **Quick Look extension** for Finder previews
- **Live reload** when an editor or an AI agent saves the file
- **Document outline** that follows the heading you are reading
- **12 document themes**, with code colours that follow the theme
- **PDF export** (⇧⌘P) that keeps Mermaid diagrams and highlighted code
- **Copy the Markdown source** (⌥⌘C) or **open the file in your editor** (⇧⌘E)
- **Word count and reading time**
- **Works offline**: nothing is uploaded to render a file

## Who it is for

- **Developers using AI coding agents.** Claude Code, Cursor, and Windsurf write plans, specs, and READMEs in Markdown. MacMD Viewer can open each file the agent writes, automatically, and reload it as the agent edits it ([setup](https://macmdviewer.com/docs/integrations?utm_source=github&utm_medium=readme&utm_campaign=macmdviewer_repo)).
- **People who read more Markdown than they write.** Documentation, notes, exported wikis, `README.md` files from cloned repositories.
- **Anyone who wants Finder previews of `.md` files** with diagrams and highlighted code.

## When you need something else

MacMD Viewer does not edit files and does not render math (LaTeX/KaTeX). If you want to write in the same window you read, use an editor: Typora, or MacDown 3000, the free, universal continuation of MacDown. MacMD Viewer pairs with any editor rather than replacing it. Detailed comparisons: [MacMD Viewer vs MacDown](https://macmdviewer.com/vs/macdown?utm_source=github&utm_medium=readme&utm_campaign=macmdviewer_repo), [vs Typora](https://macmdviewer.com/vs/typora?utm_source=github&utm_medium=readme&utm_campaign=macmdviewer_repo), [all comparisons](https://macmdviewer.com/vs?utm_source=github&utm_medium=readme&utm_campaign=macmdviewer_repo).

## Install

### Homebrew

```sh
brew install --cask macmd-viewer
```

### Direct download

Download the notarized DMG from [Releases](https://github.com/macmdviewer/MacMDViewer/releases) or from [macmdviewer.com](https://macmdviewer.com/?utm_source=github&utm_medium=readme&utm_campaign=macmdviewer_repo). Direct builds update themselves through Sparkle.

### Setapp

MacMD Viewer is available on [Setapp](https://setapp.com) as part of the subscription catalog.

## Requirements

- macOS 14 Sonoma or later
- Universal binary: Apple Silicon and Intel
- 5.4 MB download, 16 MB installed

## Pricing

$19.99, one-time purchase, one license for one Mac at a time. No subscription. Refunds within 14 days. Setapp members get it with their subscription.

## About

MacMD Viewer is built and maintained by Arthur Teboul, an independent developer.
