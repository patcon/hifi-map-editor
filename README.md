# HiFi Map Editor

The purpose of this repo is to start experimenting with a map editor for High
Fidelity's `mapJSON` annotation layer. 

## Features

- [x] Displays hardcoded marker positions with proper HiFi coordinates.
- [x] Static background map with default HQ map.
- [x] Allows placing of new ephemeral markers on map (no state saved).
- [x] Render map JSON during live-editing (export).
- [x] Support deleting markers. (ctrl/command-click)
  - [ ] Tooltip on marker hover.
- [ ] Allow entering general map metadata.
- [ ] Allow state import from map JSON.
- [ ] Use custom background image from URL.
- [ ] Allow text to be specified.
- [ ] Allow circle shapes to be added.
- [ ] Allow rectangular shapes to be added.
- [ ] Allow state saving via localStorage.
- [ ] Convert app to use React.
- [ ] Support links (incl YouTube videos).
- [ ] Support images at markers
    - [ ] Support setting orientation.
    - [ ] Support visual image placement and scaling [`#1`](https://github.com/patcon/hifi-map-editor/issues/1)
- [ ] Support simple invitations to specific coordinates.
- [x] Pretty-print the mapJSON export.

## Usage

```
npm start
```

Then access the map at `localhost:5000`
