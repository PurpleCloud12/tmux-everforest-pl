## Source Plugin
1) This is a fork of [TanglingTreats/tmux-everforest](https://github.com/TanglingTreats/tmux-everforest)
2) I created this fork to customize the theme further and take no credit for the base theme's work
### Tmux Plugin Manager
This would require the [plugin manager](https://github.com/tmux-plugins/tpm) to be installed and configured within `.tmux.conf` .
```bash
set -g @plugin 'PurpleCloud12/tmux-everforest-pl' # Adds to the list of plugins
set -g @tmux-everforest 'dark-medium' # Sets the option to select the theme. Also the default.

## Attribution
- [Everforest](https://github.com/sainnhe/everforest) colorschemes from [sainnhe](https://github.com/sainnhe/)
- The configuration and scripts that made this possible is inspired from [tmux-gruvbox](https://github.com/egel/tmux-gruvbox).
