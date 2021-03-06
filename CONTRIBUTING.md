# Contributing to TileDB-FastQ

Thanks for your interest in TileDB-FastQ. The notes below give some pointers for filing issues and bug reports, or contributing to the code.

## Contributing Code
*By contributing code to TileDB-FastQ, you are agreeing to release it under the [MIT License](https://github.com/TileDB-Inc/TileDB/tree/dev/LICENSE).*

## Contribution Checklist
- Reporting a bug? Please include the following information
  - operating system and version (windows, linux, macos, etc.)
  - TileDB and TileDB-FastQ version (for example, the output of `conda list` or `git status`).
  - if possible, a minimal working example demonstrating the bug or issue (along with any data to re-create, when feasible)
- Please paste code blocks with triple backquotes (```) so that github will format it nicely. See [GitHub's guide on Markdown](https://guides.github.com/features/mastering-markdown) for more formatting tricks.

### Contribution Workflow

- [Please follow these instuctions to build from source](https://github.com/TileDB-Inc/TileDB-FastQ/blob/master/README.md)
- Make changes locally, then update build with `make`.
- Be sure to run `make check` to verify changes against tests (add new tests where applicable).
- Please submit [pull requests](https://help.github.com/en/desktop/contributing-to-projects/creating-a-pull-request) against the default [`master` branch of TileDB-FastQ](https://github.com/TileDB-Inc/TileDB-FastQ/tree/master).