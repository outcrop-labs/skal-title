# Skål Title

A minimal [Omarchy](https://omarchy.org) shell plugin that shows the focused
window's title in the bar.

- Elides long titles at a configurable max width (default 280 px)
- Hides itself when no window has a title
- Follows the active bar's font and foreground color

## Install

```bash
omarchy plugin add https://github.com/outcrop-labs/skal-title.git --enable --yes
```

Or by hand: clone into `~/.config/omarchy/plugins/skal.title/`, then
`omarchy-shell shell rescanPlugins` and `omarchy plugin enable skal.title`.

## Removal

```bash
omarchy plugin remove skal.title
```
