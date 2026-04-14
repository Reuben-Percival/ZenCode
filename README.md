<div align="center">

<img src="https://img.shields.io/badge/version-1.0.0-6c63ff?style=for-the-badge" alt="Version"/>
<img src="https://img.shields.io/badge/license-GNU%20GPL%20v3-00d9a3?style=for-the-badge" alt="License"/>
<img src="https://img.shields.io/badge/PRs-welcome-ff6b6b?style=for-the-badge" alt="PRs Welcome"/>
<img src="https://img.shields.io/badge/platform-Windows%20%7C%20Linux-lightgrey?style=for-the-badge" alt="Platform"/>

<br/><br/>

```
 ______          ____          _
|__  / ___ _ __ / ___|___   __| | ___
  / / / _ \ '_ \ |   / _ \ / _` |/ _ \
 / /_|  __/ | | | |__| (_) | (_| |  __/
/____|\___|_| |_|\____\___/ \__,_|\___|
```

### A clean, minimal code editor built for developers.

[Download](#installation) · [Features](#features) · [Screenshots](#screenshots) · [Contributing](#contributing) · [Docs](#documentation)

<br/>

</div>

---

## What is ZenCode?

**ZenCode** is a lightweight, open-source code editor designed with one goal in mind: get out of your way. With a distraction-free interface, buttery-smooth syntax highlighting, and a thoughtfully minimal UI, ZenCode lets you focus on what matters — writing great code.

Whether you're editing a quick script or working through a large project, ZenCode gives you a calm, productive environment with no bloat, no clutter, and no compromise on performance.

---

## Features

* **Syntax Highlighting** — Rich, accurate highlighting for 50+ languages powered by a custom tokenizer
* **Dark & Light Themes** — Carefully crafted themes that are easy on the eyes, day or night
* **Blazing Fast** — Instant startup, instant file loading — no waiting around
* **Minimal UI** — Every element earns its place; nothing is there without a reason
* **File Tree Explorer** — Clean sidebar navigator with fuzzy search
* **Smart Search & Replace** — Regex-powered find and replace across single files or entire projects
* **Integrated Terminal** — A sleek embedded terminal so you never have to leave the editor
* **Plugin System** — Extend ZenCode with a simple, well-documented plugin API
* **Keyboard-First** — Full command palette and shortcut system for mouse-free workflows
* **Auto Save** — Never lose your work again

---

## Screenshots

> *Screenshots coming soon — contributors welcome!*

---

## Installation

### Pre-built Binaries

Download the latest release for your platform from the [Releases](https://github.com/Free-Software-People/ZenCode/releases) page.

| Platform | Download                       |
| -------- | ------------------------------ |
| Windows  | `ZenCode-Setup-x64.exe`        |
| Linux    | `ZenCode-linux-amd64.AppImage` |

### Build from Source

#### Prerequisites

* [CMake](https://cmake.org/) 3.20+
* [Git](https://git-scm.com/)
* [Ninja](https://ninja-build.org/) (optional but recommended for faster builds)
* A C++17-compatible compiler (MSVC 2019+ on Windows, GCC 10+ or Clang 12+ on Linux)

#### Windows

```bash
# Clone the repository
git clone https://github.com/Free-Software-People/ZenCode.git
cd zencode

# Configure (CMake)
cmake -B build -DCMAKE_BUILD_TYPE=Release

# OR configure with Ninja
cmake -B build -G Ninja -DCMAKE_BUILD_TYPE=Release

# Build
cmake --build build
```

#### Linux

```bash
# Clone the repository
git clone https://github.com/Free-Software-People/ZenCode.git
cd zencode

# Configure (CMake)
cmake -B build -DCMAKE_BUILD_TYPE=Release

# OR configure with Ninja
cmake -B build -G Ninja -DCMAKE_BUILD_TYPE=Release

# Build
cmake --build build
```

> For a debug build, replace `Release` with `Debug` in the configure step.

---

## Supported Languages

ZenCode ships with syntax highlighting for:

`JavaScript` `TypeScript` `Python` `Rust` `Go` `C` `C++` `C#` `Java` `Ruby` `PHP` `Kotlin` `HTML` `CSS` `SCSS` `JSON` `YAML` `TOML` `Markdown` `Bash` `SQL` `GraphQL` and more...

Don't see your language? [Request it](https://github.com/Free-Software-People/ZenCodeissues/new) or [add it yourself](#contributing)!

---

## Keyboard Shortcuts

| Action               | Shortcut       |
| -------------------- | -------------- |
| Open Command Palette | `Ctrl+Shift+P` |
| Quick Open File      | `Ctrl+P`       |
| Find in File         | `Ctrl+F`       |
| Find in Project      | `Ctrl+Shift+F` |
| Toggle Terminal      | `` Ctrl+` ``   |
| Toggle Sidebar       | `Ctrl+B`       |
| New File             | `Ctrl+N`       |
| Save                 | `Ctrl+S`       |

---

## Configuration

ZenCode stores its config in `~/.zencode/config.json` on Linux and `%APPDATA%\\ZenCode\\config.json` on Windows. Here's a quick example:

```json
{
  "theme": "zen-dark",
  "fontSize": 14,
  "fontFamily": "JetBrains Mono",
  "tabSize": 2,
  "wordWrap": true,
  "autoSave": true,
  "minimap": false,
  "lineNumbers": true
}
```

---

## Documentation

Full documentation is available at **[zencode.dev/docs](https://zencode.dev/docs)** *(coming soon)*.

Topics covered:

* Getting Started
* Theme Customization
* Plugin Development
* Keybinding Configuration
* Language Support

---

## Contributing

Contributions are what make open source great — and ZenCode welcomes them warmly.

### How to contribute

1. **Fork** this repository
2. **Create** a feature branch: `git checkout -b feature/amazing-feature`
3. **Commit** your changes: `git commit -m 'Add amazing feature'`
4. **Push** to the branch: `git push origin feature/amazing-feature`
5. **Open a Pull Request**

### Areas we'd love help with

* Translations / i18n
* New themes
* Plugin development
* Documentation improvements
* Bug fixes
* Tests

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a pull request.

---

## Roadmap

* [ ] Git integration (diff viewer, blame, status)
* [ ] LSP (Language Server Protocol) support
* [ ] Multi-cursor editing improvements
* [ ] Collaborative editing (live share)
* [ ] Extension marketplace
* [ ] AI-powered code completion

---

## License

ZenCode is licensed under the **GNU General Public License v3.0 (GNU GPL v3)**.

You are free to use, modify, and distribute this software under the terms of the GNU GPL v3 as published by the Free Software Foundation.

This program is distributed in the hope that it will be useful, but **WITHOUT ANY WARRANTY**, without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

For full license details, see the [LICENSE](LICENSE) file.

---

## Acknowledgements

ZenCode is built with care and inspired by the best parts of many great editors. A huge thank you to all [contributors](https://github.com/your-org/zencode/graphs/contributors) who have helped shape this project.

---

<div align="center">

Made with care and a love for clean code.

**[Back to top](#)**

</div>
