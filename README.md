# Mac Setup!


## 1. Install: Homebrew 
[The Missing Package Manager for macOS (or Linux)](https://docs.brew.sh/Manpage)
Run each command in order:

A. Install.

        /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

B. Set path for bash and/or zshell

        echo 'PATH="/usr/local/bin:$PATH"' >> ~/.bash_profile 
        echo 'PATH="/usr/local/bin:$PATH"' >> ~/.zshrc

C. Check version to determine functionality. If functional, turn off analytics.

        brew -v
        brew analytics off

## 2. Install: Warp
[The terminal for the 21st century](https://www.warp.dev)

A. Install.

        brew install --cask warp

B. Turn off telemetry/analytics in options.

C. Create a custom themes directory.

        mkdir -p ~/.warp/themes/
        
[Optionally merge with this repo if desired.](https://github.com/warpdotdev/themes)

D. Place the included 'Personal.yaml' theme in:

        ~/.warp/themes/themes

E. Place the included 'keybindings.yaml' in:
        
        ~/.warp
        
F. Place the included 'starship.toml' in:

        ~/.config

G. Unzip FiraCode and move the folder into fontbook.app
# Install Latest Build of Each coding tool.

### Install Python
 
[Install](https://www.python.org/downloads/macos/)
 
### Install PyCharm
 
[Install](https://www.jetbrains.com/pycharm/download/#section=mac)

### Install Visual Studio

[Install](https://code.visualstudio.com/download)

### Install Github Desktop

[Install](https://desktop.github.com)



























