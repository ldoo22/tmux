# Custom tmux Config File

This repository contains my custom tmux configuration file. Feel free to use it for your own tmux setup.

## Installation

To get started, clone this repository by running the following command in your terminal:

```bash
git clone https://github.com/ldoo22/tmux.git ~/.config/
```

## Setup

Once you have cloned the repository, you'll need to install the plugins. 

Install tmux plugins manager:

```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

Launch tmux and use the following keybinding:

```
prefix + i
```

The `prefix` key is usually set to `Ctrl + b` by default. So, to install the plugins, press `Ctrl + b` first, then release it and press `i`.

With the plugins installed, your custom tmux configuration should be up and running.

If 'prefix + i' does not work try: 

```
. ~/.tmux/plugins/tpm/bin/install_plugins
```

Enjoy your personalized tmux setup! If you have any questions or suggestions, feel free to reach out. Happy coding!
