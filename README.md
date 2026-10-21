# HelpMake-Vscode-Extension

Syntax highlighting for [HelpMake](https://github.com/Gag91/Help_Make), a lightweight language-agnostic build system.

## Features

- Syntax highlighting for `HelpMake.txt` and `.helpmake` files
- Comments (`#`)
- Block keywords (`InputFiles`, `Includes`, `Flags`, `Fetch`, `Modules`, `PreBuild`, `PostBuild`, `Copy`, `Set`, `Arguments`, `Config`, `Dependency`)
- Config and dependency names highlighted distinctly (`Config: debug {`, `Dependency: raylib {`)
- All scalar fields (`Compiler`, `Version`, `Output`, `Kind`, `Run`, `Jobs`, `PCH`, `Depends`)
- All dependency fields (`Git`, `Url`, `Path`, `Tag`, `Commit`, `Hash`, `Build`, `Include`, `Link`, `LinkDir`, `LinkFlags`)
- Variable expansion (`[[name]]`)

## Usage

Just open a `HelpMake.txt` file. Highlighting works automatically.

## License
This program is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Icon
Icon made with Canva.