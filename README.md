<div align="center">
<img height="256" src="https://github.com/ejbills/DockDoor/raw/main/DockDoor/Assets.xcassets/AppIcon.appiconset/icon_256x256@2x.png">
<h1>DockDoor</h1>
<h2><i>A new way of interacting with the Dock.</i></h2>
</div>

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/ejbills/DockDoor?style=flat-square)](https://github.com/ejbills/DockDoor/releases/latest/download/DockDoor.dmg)
![GitHub All Releases](https://img.shields.io/github/downloads/ejbills/DockDoor/total?label=Total%20Downloads&style=flat-square)
[![GitHub stars](https://img.shields.io/github/stars/ejbills/DockDoor)](https://github.com/ejbills/DockDoor/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/ejbills/DockDoor)](https://github.com/ejbills/DockDoor/network/members)
[![GitHub issues](https://img.shields.io/github/issues/ejbills/DockDoor?style=flat-square)](https://github.com/ejbills/DockDoor/issues)
[![GitHub license](https://img.shields.io/github/license/ejbills/DockDoor?style=flat-square)](https://github.com/ejbills/DockDoor/blob/main/LICENSE)
[![Contributors](https://img.shields.io/github/contributors/ejbills/DockDoor?style=flat-square)](https://github.com/ejbills/DockDoor/graphs/contributors)

**DockDoor** is a macOS application that adds a much-needed feature to your Mac: Dock previews.
Developed with Swift and SwiftUI, it offers seamless integration with macOS. DockDoor is designed for ease of use and intuitive interactions.
As an open-source project, it welcomes contributions from developers to enhance the application’s functionality, performance and user experience.

Minimum macOS version:
- 1.1.5 and older: **macOS 14 Sonoma**
- 1.1.6 and newer: **macOS 13 Ventura**

> [!TIP]
> If you encounter a bug or have a feature request, please open an issue on this repository. The developers will do their best to address the bug or fulfill your request!

If you appreciate this application, please consider **donating** to the developer. Any amount is appreciated! [![Buy Me a Coffee](https://img.shields.io/badge/Buy%20me%20a%20coffee-ffdd00?style=flat&logo=buy-me-a-coffee&logoColor=black)](https://www.buymeacoffee.com/keplercafe)

> [!NOTE]
> You can help translating this application in your own language. This is a crucial step in making DockDoor accessible to everyone, regardless of their knowledge level in English. [![Help translate the app here](https://img.shields.io/badge/Help%20translate%20here!-blue?style=flat-square)](https://crowdin.com/project/dockdoor/invite?h=895e3c085646d3c07fa36a97044668e02149115)

## Install

### Manual installation

[Download the latest release here](https://github.com/ejbills/DockDoor/releases/latest/download/DockDoor.dmg). Mount the downloaded file (`DockDoor.dmg`) and drag DockDoor to the `Applications` folder.

> [!NOTE]
> DockDoor is still actively being developed. To ensure you benefit from all the latest features, please keep your copy of the application up to date by enabling automatic updates in the app.

### Using Homebrew

You can also install DockDoor using [Homebrew](https://brew.sh/)! Just type or paste the following command into a Terminal:
```sh
brew install --cask dockdoor
```

## Usage

### Dock Peek feature
Hover over any application’s icon in the Dock to see its open windows.
Each traffic light button you see serves an intuitive function. Hold **`Option`** (⌥) to **force quit** the window’s application.
![Set keybind](./resources/dockPeekCommented.png)

- **How to use the Alt-Tab feature?**
  - To switch between windows, hold down the `Command` key (<strong>&#8984;</strong>) and press the `Tab` key (<strong>&RightArrowBar;</strong>) repeatedly until the desired window is highlighted. To go back, press `Shift` in addition to `Tab`. Release both keys to switch to the selected window.
  - Disabling the default `Cmd + Tab` keybind will allow the user to set a custom keybind.
      - User chooses one of the modifier keys presented on the screen (`Command`, `Option` or `Control`);
      - User clicks on `Start Recording Keybind`;
      - User presses the key they want to associate with the previously selected modifier key;
      - Keybind is now set!
      
      ![Set keybind](./resources/setKeybind.gif)

- **How to use the dock peeking feature?**
  - Simply hover over any application with active windows in the Dock.
- **What are the traffic light buttons that appear in the preview window?**
  - 🟣 **Quit** the window’s app. You can hold the `Option` **(⌥)** key while clicking to **force quit**.
  - 🔴 **Close** the window
  - 🟡 **Minimize** the window
  - 🟢 Enter the window to **full screen**

### FAQ

- I disabled the menu bar icon and now I can’t access settings
  - Simply search for "DockDoor" using the macOS built-in Spotlight and open the application. The settings window should appear.
- I clicked on the purple quit button in the preview and the app doesn’t close
  - You can hold the `Option` **(⌥)** key while clicking to **force quit**.
 
## Installation (for contributors)

### Prerequisites

- **macOS 13.0** or later.
- **Xcode** installed on your machine.

### Setting Up the Project

1. **Fork** the repository.
2. **Clone** your forked repository to your local machine.
3. **Open** the project in Xcode.
4. **Build** and **run** the project.

## How to Contribute

Contributions to DockDoor are welcome! Here’s how you can get started:

### Prerequisites

- Basic knowledge of **Swift** and **SwiftUI**.

### Contribution Guide

1. **Branching**
    - Base all new features off of `main`.
    - Create a new branch for each feature or bug fix: `git checkout -b feature/your-feature-name`.
2. **Coding Standards**
    - Follow Swift coding conventions and style guidelines.
    - Aim for clear, concise, and expressive code.
3. **Documentation**
    - Document your code using comments to explain complex logic or functionality.
4. **Testing**
    - Write unit tests for new features or changes.
    - Ensure existing tests pass before submitting a pull request.
5. **Open a pull request**
    - Do a self-review of your code.
6. **Enjoy!**