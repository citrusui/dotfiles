# citrusui's dotfiles

A stylish command prompt config for Unix systems.

# Preview

![macOS Terminal](apple.png)
![Hyper](hyper.png)
![iTerm2](iterm2.png)

## Install

```sh
git clone https://github.com/citrusui/dotfiles
source dotfiles/setup.sh
```

### What's inside?

[`.bash_profile`](https://github.com/citrusui/dotfiles/blob/master/.bash_profile): Sets case-insensitivity, appends to .bash_history, autocorrects typos, and loads .bash_prompt.

[`.bash_prompt`](https://github.com/citrusui/dotfiles/blob/master/.bash_prompt): Additional color and functionality to the current prompt.

[`.bashrc`](https://github.com/citrusui/dotfiles/blob/master/.bashrc): Sources `.bash_profile`.

[`.editorconfig`](https://github.com/citrusui/dotfiles/blob/master/.editorconfig): Settings for your favorite text editor.

[`.gitconfig`](https://github.com/citrusui/dotfiles/blob/master/.gitconfig): Settings that modify Git color output and functionality.

[`.gitignore`](https://github.com/citrusui/dotfiles/blob/master/.gitignore): Just a few files to ignore in this repo.

[`.hushlogin`](https://github.com/citrusui/dotfiles/blob/master/.hushlogin): Suppresses the login message.

[`.hyper.js`](https://github.com/citrusui/dotfiles/blob/master/.hyper.js): Appearance configurations for Hyper.

[`.macos`](https://github.com/citrusui/dotfiles/blob/master/.macos): Loads `dotfiles.terminal` when on macOS.

[`.pantheon`](https://github.com/citrusui/dotfiles/blob/master/.pantheon): Color and functionality settings for Pantheon.

[`dotfiles.itermcolors`](https://github.com/citrusui/dotfiles/blob/master/dotfiles.itermcolors): Colorized output for iTerm2.

[`dotfiles.terminal`](https://github.com/citrusui/dotfiles/blob/master/dotfiles.terminal): Profile scheme for Terminal.app.

[`setup.sh`](https://github.com/citrusui/dotfiles/blob/master/setup.sh): Sets up these dotfiles.

### An update was released, how do I get the latest version?

Simple, just re-run the setup script:

```sh
source dotfiles/setup.sh
```

### What terminals are supported?

- macOS Terminal<sup>1</sup>
- [iTerm2](https://www.iterm2.com)
- [Hyper](https://hyper.is)
- [GNOME](https://wiki.gnome.org/Apps/Terminal)<sup>2</sup>
- [Pantheon](https://launchpad.net/pantheon-terminal)
- [Windows Bash](https://msdn.microsoft.com/commandline/wsl/about)<sup>3</sup>

<sup>1</sup> Does not support 24-bit colors.

<sup>2</sup> Basic support. Profiles must be managed through Gnome Terminal manually.

<sup>3</sup> 24-bit color support will be available in [future Windows builds](https://blogs.msdn.microsoft.com/commandline/2016/09/22/24-bit-color-in-the-windows-console/).

If you'd to see your terminal supported, open an [issue](https://github.com/citrusui/dotfiles/issues)!

## Credits

A huge thanks to Mathias Bynens for his [`dotfiles`](https://github.com/mathiasbynens/dotfiles) repo, from which this is based off of!
