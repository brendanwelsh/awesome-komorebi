# Awesome Komorebi [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, bars, themes, guides, and companions for komorebi, the tiling window manager for Windows.

komorebi tiles your windows on top of the Desktop Window Manager. It is driven by the `komorebic` CLI, ships with the `komorebi-bar` status bar, and is usually paired with a hotkey daemon such as `whkd`. It is free for personal use; commercial use requires an individual license via [sponsorship](https://komorebi.lgug2z.com/about/licensing/).

Every link here was checked and resolves at the time of writing.

## Contents

- [Window manager](#window-manager)
- [Status bars](#status-bars)
- [Hotkeys and keyboard](#hotkeys-and-keyboard)
- [Workspace switchers and tray](#workspace-switchers-and-tray)
- [Theming and color](#theming-and-color)
- [Utilities and integrations](#utilities-and-integrations)
- [Configuration](#configuration)
- [Libraries](#libraries)
- [Companion apps](#companion-apps)
- [Dotfiles and example setups](#dotfiles-and-example-setups)
- [Guides and tutorials](#guides-and-tutorials)
- [Articles and comparisons](#articles-and-comparisons)
- [Alternative window managers](#alternative-window-managers)
- [Related lists](#related-lists)
- [Community](#community)

## Window manager

- [komorebi](https://github.com/LGUG2Z/komorebi) - The tiling window manager itself, bundling the `komorebic` CLI and the `komorebi-bar` status bar.

## Status bars

- [hitokage](https://github.com/codyduong/hitokage) - Configurable status bar written in Rust and scripted in Lua.
- [komorebi-bar](https://komorebi.lgug2z.com/reference/bar-windows/) - First-party status bar bundled with the window manager, configured via `komorebi.bar.json`.
- [YASB](https://github.com/amnweb/yasb) - Highly configurable Python status bar with a first-class workspace widget.
- [Zebar](https://github.com/glzr-io/zebar) - Cross-platform widgets and taskbars (web tech) with a built-in workspace provider.

## Hotkeys and keyboard

- [AutoHotkey](https://github.com/AutoHotkey/AutoHotkey) - Windows automation and scripting language, an alternative way to bind shortcuts.
- [komokana](https://github.com/LGUG2Z/komokana) - First-party automatic, application-aware kanata keyboard-layer switching driven by window focus.
- [whkd](https://github.com/LGUG2Z/whkd) - First-party simple hotkey daemon and the recommended way to bind shortcuts.

## Workspace switchers and tray

- [komorebi-switcher](https://github.com/amrbashir/komorebi-switcher) - Minimal workspace switcher embedded directly in the Windows taskbar.
- [komorebi-tray](https://github.com/starise/komorebi-tray) - Tray app to start, stop, and manage the window manager.
- [komorebi-tray-grid](https://github.com/h0tk3y/komorebi-tray-grid) - Tray icon that renders a per-monitor grid of the current workspace state.
- [komoswitch](https://github.com/tuasananh/komoswitch) - Lightweight native Windows 11 taskbar workspace switcher.
- [komotray](https://github.com/urob/komotray) - Minimal tray icon that shows the active workspace.

## Theming and color

- [Built-in themes](https://komorebi.lgug2z.com/usage/themes/) - Docs for applying the bundled Catppuccin and Base16 themes to borders and the bar.
- [Catppuccin](https://github.com/catppuccin/catppuccin) - Pastel theme (Latte, Frappé, Macchiato, Mocha) supported natively for borders and the bar.
- [tacky-borders](https://github.com/lukeyou05/tacky-borders) - Customizable animated window borders for Windows 10 and 11.
- [Tinted Theming](https://github.com/tinted-theming/home) - Base16/Base24 scheme system; the bundled Base16 themes come from here.
- [Tinty](https://github.com/tinted-theming/tinty) - Base16/Base24 color-scheme manager for theming many apps at once.
- [yasb-themes](https://github.com/amnweb/yasb-themes) - Community gallery of ready-made themes for the YASB bar.
- [yasb-wallpaper-engine-color-sync](https://github.com/brendanwelsh/yasb-wallpaper-engine-color-sync) - Tint your YASB bar and taskbar to match the active Wallpaper Engine wallpaper.

## Utilities and integrations

- [komoflow](https://github.com/pro470/Flow.Launcher.Plugin.komoflow) - Flow Launcher plugin to send commands from the launcher.
- [komorebi-loading](https://github.com/SuppliedOrange/komorebi-loading) - Shows a loading screen while the window manager starts up.
- [komorebi.el](https://github.com/eraschle/komorebi.el) - Emacs package for driving the window manager from within Emacs.
- [KomorebiShellExtension](https://github.com/Zira3l137/KomorebiShellExtension) - Windows right-click (shell) menu for managing the window manager.
- [masir](https://github.com/LGUG2Z/masir) - First-party focus-follows-mouse daemon for Windows 11 and later.
- [streamdeck-komorebi](https://github.com/kdeenanauth/streamdeck-komorebi) - Elgato Stream Deck plugin that shows state and sends commands.
- [wpm](https://github.com/LGUG2Z/wpm) - First-party process manager for autostarting the window manager and its companions.

## Configuration

- [komorebi-application-specific-configuration](https://github.com/LGUG2Z/komorebi-application-specific-configuration) - First-party curated per-application rules so more apps tile correctly out of the box.
- [komorebi-custom-layout-generator](https://github.com/LGUG2Z/komorebi-custom-layout-generator) - First-party interactive tool to generate custom layouts as JSON.

## Libraries

- [komorebi-client](https://github.com/LGUG2Z/komorebi/tree/master/komorebi-client) - First-party Rust crate to subscribe to events and send commands over the named pipe.

## Companion apps

- [ExplorerPatcher](https://github.com/valinet/ExplorerPatcher) - Restores and customizes the Windows taskbar and Start menu.
- [Microsoft PowerToys](https://github.com/microsoft/PowerToys) - Microsoft's utility suite (Run, Command Palette, FancyZones) that pairs well.
- [Nilesoft Shell](https://github.com/moudey/Shell) - Scriptable, themeable File Explorer context menus.
- [Rainmeter](https://github.com/rainmeter/rainmeter) - Desktop widget and skin engine for custom panels and overlays.
- [StartAllBack](https://startallback.com/) - Paid taskbar, Start, and Explorer customizer.
- [TranslucentTB](https://github.com/TranslucentTB/TranslucentTB) - Lightweight tool to make the taskbar translucent or transparent.
- [Wallpaper Engine](https://store.steampowered.com/app/431960/Wallpaper_Engine/) - Animated and interactive wallpapers, popular for desktop ricing.
- [Windhawk](https://github.com/ramensoftware/windhawk) - Customization marketplace whose taskbar mods reshape the native taskbar.

## Dotfiles and example setups

- [ConnorSweeneyDev/.config](https://github.com/ConnorSweeneyDev/.config) - Windows dotfiles combining the window manager with whkd, YASB, AutoHotkey, and Neovim.
- [jacquindev/windots](https://github.com/jacquindev/windots) - Windows 11 dotfiles with a Catppuccin-themed bar setup.
- [sundathree/.dotfiles](https://github.com/sundathree/.dotfiles) - YASB-focused Windows 11 dotfiles with several bar themes.
- [SuppliedOrange/dotfiles](https://github.com/SuppliedOrange/dotfiles) - Windows dotfiles featuring whkd and a custom loading screen.

## Guides and tutorials

- [Official documentation](https://komorebi.lgug2z.com/) - Installation, configuration, usage, and CLI reference.
- [Quickstart](https://komorebi.lgug2z.com/guides/quickstart/) - Official step-by-step first-time setup.
- [Example configurations](https://lgug2z.github.io/komorebi/example-configurations.html) - Annotated example configs to copy from.
- [Configuration examples (haoblackj)](https://zenn.dev/haoblackj/articles/komorebi-example) - In-depth walkthrough with a full annotated config (Japanese).
- [Tiling on Windows starter guide](https://binfo-hodake.com/posts/komorebi-starter/) - Starter guide covering whkd, bar widgets, and themes (Japanese).
- [Tutorials playlist (Jeezy Codes)](https://www.youtube.com/playlist?list=PLllZnrEJu89AJzPSvO7racNyfvPmJupkx) - Community video series on install, layouts, stacks, and features.
- [Transform Your Windows Desktop](https://www.youtube.com/watch?v=oiARKvmQM9c) - Beginner-friendly install and setup walkthrough video.

## Articles and comparisons

- [Show HN: Komorebi](https://news.ycombinator.com/item?id=33168263) - Original launch discussion with the author and community.
- [4 Windows 11 tiling managers (XDA)](https://www.xda-developers.com/windows-11-tiling-window-managers-will-change-how-you-use-your-pc/) - Compares the field, including GlazeWM, Whim, and Jwno.
- [I replaced Snap Layouts with a tiling WM (MakeUseOf)](https://www.makeuseof.com/i-replaced-windows-snap-layouts-with-a-tiling-window-manager-and-got-the-linux-experience-i-wanted/) - Hands-on comparison favoring komorebi's layout engine.

## Alternative window managers

- [FancyWM](https://github.com/FancyWM/fancywm) - Dynamic tiling window manager for Windows focused on zero-config use (C#).
- [GlazeWM](https://github.com/glzr-io/glazewm) - Tiling window manager for Windows inspired by i3, paired with the Zebar bar (Rust).
- [Jwno](https://github.com/agent-kilo/jwno) - Tiling window manager for Windows scriptable in Janet (Lisp).
- [Whim](https://github.com/dalyIsaac/Whim) - Pluggable dynamic window manager with swappable layout engines (C#, alpha).
- [workspacer](https://github.com/workspacer/workspacer) - Tiling window manager configured in C#, in the style of dwm, i3, and xmonad (maintenance mode).

## Related lists

- [Awesome Windows](https://github.com/0PandaDEV/awesome-windows) - Curated list of Windows apps, including window managers.
- [awesome-komorebi (official)](https://github.com/LGUG2Z/awesome-komorebi) - The maintainer's own curated list of ecosystem projects.

## Community

- [Community page](https://komorebi.lgug2z.com/about/community/) - Official overview of where to get help.
- [Discord](https://discord.gg/mGkn66PHkx) - Official community chat for help and discussion.
- [GitHub Discussions](https://github.com/LGUG2Z/komorebi/discussions) - Q&A and announcements on GitHub.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](contributing.md) first. In short: one entry per line, alphabetical within its section, with a working link and a short description.

---

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Brendan Welsh has waived all copyright and related or neighboring rights to this work. See [LICENSE](LICENSE).
