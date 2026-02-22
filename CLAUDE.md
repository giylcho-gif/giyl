# GIYL Project Rules

## New Game Creation Checklist
When a new HTML game is created in this project, ALWAYS do the following:

1. **Add desktop shortcut**: Update `create_icons_v2.ps1` with the new game entry (file, name, bg, fg, accent, text, shape) and run it via PowerShell to generate the icon and desktop shortcut.
2. **Update index.html**: Add the new game to the sidebar menu in `index.html` under the appropriate category.

## Project Structure
- All games are standalone HTML files in the root directory (except `snowboard/index.html`)
- Icons are stored in `icons/` directory
- Desktop shortcuts are created via `create_icons_v2.ps1`
- 3D models are in `models/` directory
