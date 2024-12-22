
# st 0.9.2

5 Patches thats all i need.
## Installation

If you can build normal st without any patches then you can compile this version too. You only need to install this font or change the font from config file.

```bash
wget -P ~/.local/share/fonts https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.2/JetBrainsMono.zip \
&& cd ~/.local/share/fonts \
&& unzip JetBrainsMono.zip \
&& rm JetBrainsMono.zip \
&& fc-cache -fv
```
    
## Patches

- anysize - unsightly gaps fix
- alpha - Transparancy changable from config
- scrollback - using mouse scroll wheel / Ctrl+Shift + J/K 
- gruvbox theme