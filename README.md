# MacMD Viewer

A native macOS app that renders Markdown files into clean, formatted documents. It is a read-only viewer, not an editor: you open a `.md` file and see it rendered the way it is meant to look, and it updates automatically when the file changes on disk.

**[Download the latest release →](https://github.com/macmdviewer/MacMDViewer/releases/latest)** · **[Website →](https://macmdviewer.com)**

> **About this repository.** MacMD Viewer is a commercial, closed-source app, so there is
> no source code here by design. This repository is its release channel: every version
> ships as a signed, notarized DMG attached to a [GitHub Release](https://github.com/macmdviewer/MacMDViewer/releases),
> which is also what the Homebrew cask and the app's Sparkle updater download. Issues and
> feature requests are welcome — support runs through
> [macmdviewer.com](https://macmdviewer.com).

## The problem it solves

AI coding tools (Claude Code, Cursor) and AI assistants (ChatGPT, Claude) produce a lot of Markdown: READMEs, specs, plans, notes, generated documentation. macOS has no built-in way to read a `.md` file as formatted output, so double-clicking one either opens raw text in TextEdit or launches a full editor. MacMD Viewer fills that gap: it shows the rendered document, and because it live-reloads, you can watch an AI agent's output update in place as it writes.

## Features

- Renders GitHub-Flavored Markdown (tables, task lists, fenced code, strikethrough)
- Syntax highlighting for fenced code blocks
- Mermaid diagram rendering (flowcharts, sequence diagrams, and more)
- Live reload: the view refreshes automatically when the file changes on disk
- Finder QuickLook extension: press Space on a `.md` file to preview it rendered
- 12 document themes
- Scroll-spy outline that highlights the active heading as you scroll
- Native Swift 6 + SwiftUI app, a 5.4 MB download, universal binary (Apple Silicon and Intel)
- Requires macOS 14 or later

## Install

### Homebrew (Cask)

```sh
brew install --cask macmd-viewer
```

### Direct download

Download the notarized DMG from the [Releases](https://github.com/macmdviewer/MacMDViewer/releases) page, or from [macmdviewer.com](https://macmdviewer.com). Direct builds receive automatic updates via Sparkle.

### Setapp

MacMD Viewer is available on [Setapp](https://setapp.com) as part of the subscription catalog.

## Pricing

19.99 USD, one-time purchase. No subscription and no trial. (Setapp distribution is covered by the Setapp subscription.)

## Links

- Website: https://macmdviewer.com
- Releases: https://github.com/macmdviewer/MacMDViewer/releases
- Homebrew Cask: `brew install --cask macmd-viewer`
- Setapp: https://setapp.com

## About

MacMD Viewer is built and maintained by Arthur Teboul, an independent developer.
