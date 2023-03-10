<div align="center">

# Hacker Newsfeed

App for reading [Hacker News](https://news.ycombinator.com/).

[![Build status](https://github.com/rhzx86/hacker-newsfeed/actions/workflows/release.yml/badge.svg)](https://github.com/rhzx86/hacker-newsfeed/actions)
[![GitHub Release](https://img.shields.io/github/v/release/rhzx86/hacker-newsfeed)](https://github.com/rhzx86/hacker-newsfeed/releases/latest)

<img alt="App screenshot" src="screenshot.png">

</div>

## Installation

Download the latest release [here](https://github.com/rhzx86/hacker-newsfeed/releases/latest).

Or install it from sources with `cargo install hacker-newsfeed`.

## Features

- Tabs to browse Top, New, Show HN, Ask HN and Jobs stories
- Open external links in browser
- Show comments for stories in app
- Expand and collapse story comments in tree-like structure
- Refresh to load new stories
- Navigation with keyboard shortcuts
- Accessibility and screenreader support
- Made with [egui](https://github.com/emilk/egui)

### Keyboard shortcuts

- `F5` - Refresh
- `Backspace` - Go back to story view from comment section
- `Alt + Left Arrow` - Go back a page
- `Alt + Right Arrow` - Go to next page (load more)
- `Alt + 1` - Switch to Top tab
- `Alt + 2` - Switch to New tab
- `Alt + 3` - Switch to Show HN tab
- `Alt + 4` - Switch to Ask HN tab
- `Alt + 5` - Switch to Jobs tab
- `F12` - Debug menu

### Accessibility keyboard shortcuts
- `Tab` - Focus next ui item
- `Shift + Tab` - Focus previous ui item
- `Space` or `Enter` - interact with ui item (click link/button)

#### License

<sup>
<a href="LICENSE-APACHE">Apache License, Version 2.0</a> or <a href="LICENSE-MIT">MIT license</a>
</sup>
