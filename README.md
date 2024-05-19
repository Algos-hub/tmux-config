# Tmux Config File

This is my personal Tmux configuration file

The following plugins have been used:

Plugin Manager: ['tmux-plugins/tpm'](https://github.com/tmux-plugins/tpm)\
Standard base options: ['tmux-plugins/tmux-sensible'](https://github.com/tmux-plugins/tmux-sensible)\
Copy and paste: ['tmux-plugins/tmux-yank'](https://github.com/tmux-plugins/tmux-yank)\
Status line: ['o0th/tmux-nova'](https://github.com/o0th/tmux-nova)

# Installation

### 1: Install tpm

&nbsp;&nbsp;&nbsp;&nbsp;This tmux configuration requires the tpm. If you already have tpm installed you can skip this step.\
&nbsp;&nbsp;&nbsp;&nbsp;To install tmp you can follow their install guides in their official Github repo\
&nbsp;&nbsp;&nbsp;&nbsp;[here](https://github.com/tmux-plugins/tpm?tab=readme-ov-file#installation)

### 2: Install a nerd font

&nbsp;&nbsp;&nbsp;&nbsp;This tmux configuration also requires a nerd font to properly display icons and sections in the terminal.\
&nbsp;&nbsp;&nbsp;&nbsp;If you already have a nerd font installed in your terminal you can skip this step.\
&nbsp;&nbsp;&nbsp;&nbsp;You can find them alongside the installation guides in their official Github repo [here](https://github.com/ryanoasis/nerd-fonts)

### 3: Cloning this repo

&nbsp;&nbsp;&nbsp;&nbsp;Clone this repo and move the .tmux.conf file into your home directory.

```bash
    cd ~
    git clone https://github.com/Algos-hub/tmux-config
    mv ./tmux-config/.tmux.conf ~
```
&nbsp;&nbsp;&nbsp;&nbsp;Once that's done, open tmux and press `Prefix` + `I` (on a fresh intallation of tmux it should be `C-b`)

