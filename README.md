# oh-my-posh-theme

A colorful and functional [Oh My Posh](https://ohmyposh.dev/) theme for Zsh, featuring a diamond-style layout with segments for user session, path, git status, python environment, and command exit status.

![Theme Preview](./preview.jpg)

## Installation

### Prerequisites

1.  **Oh My Posh**: Ensure you have Oh My Posh installed.
2.  **Nerd Font**: You need a [Nerd Font](https://www.nerdfonts.com/) installed and configured in your terminal to see the icons correctly.

### Setup

Add the following line to your `.zshrc` file to load this theme directly from the repository:

```bash
eval "$(oh-my-posh init zsh --config 'https://raw.githubusercontent.com/MaxGhi8/oh-my-posh-theme/main/max_oh_my_posh_theme.json')"
```

After adding the line, reload your shell config:

```bash
source ~/.zshrc
```

## Theme Segments

This theme includes the following segments (left-aligned):

1.  **Session**: Displays the current user (Yellow background).
2.  **Path**: Shows the current directory path (Orange background).
3.  **Git**: Displays git branch, status (modified, staged), and stash count (Teal background).
4.  **Python**: Shows the active python virtual environment or version (Blue background).
5.  **Status**: Indicates the success (Green) or failure (Red) of the last command.
