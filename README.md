# alfred-terminalfinder (Fork)

> **Note**: This is a fork of the original [alfred-terminalfinder](https://github.com/LeEnno/alfred-terminalfinder) by [LeEnno](https://github.com/LeEnno), maintained by [bpetrynski](https://github.com/bpetrynski).
> It adds support for **WezTerm**, **Alacritty**, **Ghostty**, and **Kitty**.

Alfred workflow to open current Finder window in Terminal/iTerm (and many others) and vice versa.

<img src="https://raw.github.com/LeEnno/alfred-terminalfinder/master/tf_icon_sm.png" width="128" height="128">

## Usage

Install the workflow and use the following keywords:

| App | Finder → App | App → Finder |
| :--- | :--- | :--- |
| **Terminal** | `ft` | `tf` |
| **iTerm** | `fi` | `if` |
| **Path Finder** | `pt` | `tp` |
| **Warp** | `fw` | - |
| **WezTerm** | `fz` | `zf` |
| **Alacritty** | `fa` | `af` |
| **Ghostty** | `fg` | `gf` |
| **Kitty** | `fk` | `kf` |

*(Path Finder support thanks to @olibob, Warp support thanks to @raghavpillai)*

In addition, the search result in Alfred will show you what the action will do in its subtitle:

![Finder → Terminal](https://raw.github.com/LeEnno/alfred-terminalfinder/master/screenshot_ft.png)

## Compatibility

- **iTerm**: Works with iTerm 3.x and 2.9.x. If you need support for 2.1.x, see the `2.1.x` branch on the original repo.

## Credits & Hat Tip

- Originally created by [LeEnno](https://github.com/LeEnno).
- Heavily inspired by [ssgreg's *Terminal in Finder's folder*](https://github.com/ssgreg/AlfredWorkflows/).
- Path Finder support by [olibob](https://github.com/olibob).
- Warp support by [raghavpillai](https://github.com/raghavpillai).
- Modern terminal support (WezTerm, Alacritty, Ghostty, Kitty) added in this fork by [bpetrynski](https://github.com/bpetrynski).
