# Volucris FBX Exporter

Batch export meshes to FBX with presets and custom origins.

## Features

- **Bundle Export** — merge multiple meshes into a single FBX, with a custom bundle name and the choice of a plain file or a dedicated export folder.
- **Assets Export** — export each mesh as its own FBX file, with full control over naming, duplicate handling, and folder structure.
- **Collection-based folder organization** — optionally mirror your Blender collection hierarchy into export folders, with editable custom folder names per collection.
- **Configurable duplicate suffix** — including the option to export bare mesh names with no suffix at all.
- **Per-object origin placement** — Median, Bottom Center, Top Center, or none.
- **Preview** — dry-run your export before committing, with one-click cleanup to restore your scene.
- **Overwrite protection** — optionally have exports abort instead of silently replacing existing files.
- **Bundled FBX preset** ("Default Volucris Export") plus full support for your own custom Blender FBX export presets.

## Installation

1. Download the latest `.zip` release from the [Releases page](../../releases).
2. In Blender, go to **Edit > Preferences > Get Extensions**.
3. Click the dropdown arrow next to "Install from Disk" and select the downloaded `.zip`.
4. Enable the extension if it isn't already.

The panel appears under **Properties Editor > Render tab > Volucris FBX Exporter**.

## Requirements

- Blender 5.0 or newer.

## Support / Reporting Issues

Found a bug or have a feature request? Please [open an issue](../../issues) on this repository. Include your Blender version, your OS, and steps to reproduce if you're reporting a bug.

## License

This project is licensed under the **GNU GPL v3.0 or later** — see [LICENSE](LICENSE) for the full text.

## Author

Łukasz Botor — [botieereg@gmail.com](mailto:botieereg@gmail.com)
