# AI assistance disclosure

Ravenloft 2.x was developed with assistance from **OpenAI Codex**. The tool was used under the direction and review of the human maintainer; it is neither a maintainer nor a runtime dependency of the theme.

## Scope of assistance

Codex was used to:

- research current Obsidian theming conventions, CSS variables, manifest requirements, and the Style Settings format;
- audit the legacy stylesheet and assist with its variable-first refactor;
- help implement modern component coverage, accessibility states, responsive behaviour, and colour contrast;
- validate the stylesheet, embedded fonts, manifest files, and Style Settings metadata;
- review project documentation.

## Human direction and responsibility

The original theme, its visual identity, and its design principles were created by the author. The maintainer set the creative direction, made all release decisions, reviewed and tested the resulting changes, and remains responsible for the finished theme.

## What the theme ships

The project ships CSS, JSON metadata, documentation, and font binaries embedded in `theme.css`. It includes no AI model, OpenAI API client, telemetry, or integration with an AI service. Installing or using Ravenloft does not require an OpenAI account and does not send vault content to an AI service.

This disclosure does not alter the project's licensing. Theme source code and documentation remain covered by the [MIT License](LICENSE), while the embedded fonts retain their respective [SIL Open Font License terms](FONT-LICENSES.md).
