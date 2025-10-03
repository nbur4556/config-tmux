# Tmux Configuration

## Installation

1. Clone this repository into your .config folder
2. Rename the directory to 'tmux'

```
mv path/to/.config/config-tmux path/to/.config/tmux
```

3. Create the plugin subdirectory

```
mkdir path/to/.config/tmux/plugins
```

4. Clone the tpm repository into plugins

```
cd path/to/.config/tmux/plugins
git clone git@github.com:tmux-plugins/tpm.git
```

5. Install plugins from tmux

```
tmux

# from a tmux session
<Leader>-I
```
