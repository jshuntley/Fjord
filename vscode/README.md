# Fjord VS Code Theme

A calming color scheme inspired by Nord and Ayu Mirage. Features a dusk-blue base with soft leaf-green accents, amber selections, and crisp blue/cyan separation.

## Installation

### From VS Code Extensions

1. Open the Extensions view (Cmd/Ctrl + Shift + X)
2. Search for "Fjord"
3. Click Install

### Manual Installation (Development)

1. Clone or copy the fjord repository to your VS Code extensions directory:
   - **macOS/Linux**: `~/.vscode/extensions/fjord-1.0.0`
   - **Windows**: `%USERPROFILE%\.vscode\extensions\fjord-1.0.0`

2. Restart VS Code

3. Select the theme via Command Palette (Cmd/Ctrl + Shift + P) → "Preferences: Color Theme" → "Fjord"

## Color Palette

- **Base**: #1B2532 (dusk blue)
- **Foreground**: #E4EDE5 (crisp white)
- **Selection**: #FFD285 (amber)
- **Functions**: #FFD285 (amber)
- **Keywords**: #9DD99A (soft green)
- **Control Keywords**: #BFE9BB (bright green) - **bold**
- **Types**: #5DA6EA (blue)
- **Strings**: #9DD99A (green)
- **Comments**: #6C7A86 (dim) - *italic*
- **Operators**: #7BB8FF (bright blue)
- **Members/Properties**: #B8E7E9 (cyan)

## Troubleshooting

If colors don't appear after installation:

1. **Clear cache**: Delete the VS Code cache folder
   - macOS: `rm -rf ~/Library/Application\ Support/Code/Cache`
   - Linux: `rm -rf ~/.config/Code/Cache`
   - Windows: Delete `%APPDATA%\Code\Cache`

2. **Reload**: Press Cmd/Ctrl + Shift + P and run "Developer: Reload Window"

3. **Verify**: Check that the theme is selected in Settings (Cmd/Ctrl + ,) → "Color Theme"

4. **Restart**: Fully close and restart VS Code

## Features

- ✓ Consistent syntax highlighting across languages
- ✓ Optimized UI colors for readability
- ✓ Semantic token highlighting support
- ✓ Bracket pair colorization
- ✓ Git decoration colors
- ✓ Terminal colors matching the theme
