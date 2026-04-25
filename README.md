<<<<<<< HEAD
# waybar-custom
=======
/!\ Disclaimer : 
Only configuration for my personally conf(I'm on sway, not hyprland), if you want all config please use "Hyprland-dots -- DerAnsari"
/!\


# waybar-custom and sway conf

Install :

./system_monitoring

    btop - Resource monitor with Gruvbox theming
    cava - Audio visualizer for aesthetics
    fastfetch - Clean system information display

./window_management

    waybar - Status bar with custom modules
    wofi - Application launcher

./applications

    kitty(or foot but need modify file) - Terminal emulator with Gruvbox colors
    vesktop - Discord client with custom styling
    yazi - File manager with vim-like (very style)

./utilities

    sway-screenshot - Screenshot tool
    zshrc - Shell configuration with aliases and theming

### ** Setup **

**Fonts (Required for proper display):**

```bash
# Install Iosevka Nerd Fonts

yay -S ttf-iosevka-nerd ttf-iosevka-nerd-mono

# Alternative: Download from Nerd Fonts releases

wget https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.2/Iosevka.zip
wget https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.2/IosevkaMono.zip
unzip Iosevka.zip -d ~/.local/share/fonts/
unzip IosevkaMono.zip -d ~/.local/share/fonts/**Fonts (Required for proper display):**
```bash
# Install Iosevka Nerd Fonts
yay -S ttf-iosevka-nerd ttf-iosevka-nerd-mono

```

```bash

sudo pacman -S fastfetch waybar rofi kitty 

yay -S sway-screenshot vesktop yazi cava btop

```



>>>>>>> f2d691c (Add existing file)
