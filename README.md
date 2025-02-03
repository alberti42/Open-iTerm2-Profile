# Open iTerm2 Profile for LaunchBar

This repository provides an action for [LaunchBar](https://www.obdev.at/products/launchbar/actions.html) that allows users to quickly open a terminal session using any available [iTerm2](https://iterm2.com/) profile. The action lists all configured profiles in iTerm2, and selecting one from the dropdown menu in LaunchBar opens a new tab with the chosen profile in an existing iTerm2 window. If no iTerm2 window is open, a new window is launched.

![Screenshot](Images/iTerm2_profiles_list_screenshot.jpg)

## Contents

This repository includes the following components:

- **Pre-packaged Action**: `Action Open iTerm2 Profile.lbaction.zip`, ready for installation.
- **Source Code**:
  - `default.py` – Retrieves available iTerm2 profiles and provides them to LaunchBar.
  - `iterm2_launcher.scpt` – AppleScript for opening a new tab or window with the selected profile.
  - `open_profile.py` – Handles profile selection and executes the appropriate script to launch iTerm2.

## Installation

### Option 1: Manual Installation

1. **Download** the pre-packaged action from [Action Open iTerm2 Profile.lbaction.zip](https://github.com/alberti42/Open-iTerm2-Profile-for-LaunchBar/raw/main/Action%20Open%20iTerm2%20Profile.lbaction.zip).
2. **Extract** the `.lbaction` file from the zip archive.
3. Move `Open iTerm2 Profile.lbaction` to the LaunchBar Actions folder:
   ```
   ~/Library/Application Support/LaunchBar/Actions
   ```
4. **Restart LaunchBar** to load the new action.

### Option 2: Automatic Installation

Simply double-click the `Open iTerm2 Profile.lbaction` file. This will install the action automatically in LaunchBar.

## Usage

- Open **LaunchBar** and type `iTerm2` or part of the action name.
- Select **"Open iTerm2 Profile"**.
- A dropdown menu will appear, listing all available iTerm2 profiles.
- Choose a profile to open a new tab in the existing iTerm2 window, or a new window if none is open.

## Requirements

- macOS
- [LaunchBar](https://www.obdev.at/products/launchbar/)
- [iTerm2](https://iterm2.com/)

## Donations

If you find this action useful, consider supporting its development with a donation.

[<img src="Images/buy_me_coffee.png" width=300 alt="Buy Me a Coffee QR Code"/>](https://buymeacoffee.com/alberti)

## Author

- **Author:** Andrea Alberti
- **GitHub Profile:** [alberti42](https://github.com/alberti42)
- **Donations:** [![Buy Me a Coffee](https://img.shields.io/badge/Donate-Buy%20Me%20a%20Coffee-orange)](https://buymeacoffee.com/alberti)

Feel free to contribute to the development of this action or report any issues in the [GitHub repository](https://github.com/alberti42/Open-iTerm2-Profile-for-LaunchBar/issues).
