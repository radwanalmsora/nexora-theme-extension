# Nexora — Ultimate UI & Syntax Themes

A complete Visual Studio Code theme extension with three coordinated color themes and a matching file icon theme.

## Included themes

- **Nexora Obsidian** — deep graphite/navy, mint focus accents, vivid syntax.
- **Nexora Aurora** — violet night palette with cool cyan highlights.
- **Nexora Pearl** — bright, low-glare light palette.

## What is themed

Editor canvas and typography colors, syntax scopes, semantic tokens, bracket matching, selections, diagnostics, IntelliSense, hover cards, tabs, title bar, activity bar, explorer, search, source control decorations, terminal ANSI colors, panels, status bar, notifications, menus, inputs, buttons, widgets, scrollbars, minimap, and focus states.

The **Nexora File Icons** pack adds matching icons for common programming languages, config formats, documents, images, archives, and folders.

> VS Code themes can color supported workbench surfaces, but they cannot arbitrarily redesign every UI element, change layout, or inject custom CSS. The extension uses the official theme contribution APIs only.

## Install locally

1. Open this folder in VS Code.
2. Press `F5` to launch an Extension Development Host.
3. In the new window, open **Preferences: Color Theme** and select a Nexora theme.
4. Open **Preferences: File Icon Theme** and select **Nexora File Icons**.

## Build a VSIX

```bash
npm install
npx vsce package
```

The generated `.vsix` will be in the project root.

## GitHub Actions

The included workflow packages the extension on pushes, pull requests, and releases, then uploads the `.vsix` as a workflow artifact. You can also download it from the Actions run page.

## Before publishing

Open `package.json` and replace `YOUR_PUBLISHER_ID` with your exact Visual Studio Marketplace publisher ID. The publisher must match your Marketplace account. Update the repository URL if you publish the project.

## Compatibility

VS Code 1.85.0 and newer. No runtime code, external service, API key, or network access is required.

## License

MIT.
