# Configuraciones en Linux

[![alacritty.jpg](https://i.postimg.cc/qB2YtGBK/alacritty.jpg)](https://postimg.cc/vDHXkfV8)

Este archivo contiene los paquetes y configuraciones que uso en mi computador. Ademas de los pasos que he hecho para instalar el sistema operativo que actualmente utilizo.

## Paquetes que uso
Para la instalacion del sistema operativo he seguido la guia de [Arch Linux](https://wiki.archlinux.org/title/Installation_guide) utilizando los siguientes paquetes:

**Kernel**:
- [linux-zen](https://wiki.archlinux.org/title/Kernel#Officially_supported_kernels)
    - linux-zen-headers
- linux-firmware
- [mkinitcpio-firmware](https://aur.archlinux.org/packages/mkinitcpio-firmware)

**Paquetes necesarios**:
- [netwokmanager](https://wiki.archlinux.org/title/Networkmanager) y dhcpcd
- [grub](https://wiki.archlinux.org/title/Grub) y efibootmgr
- [os-prober](https://archlinux.org/packages/community/x86_64/os-prober/)

**Administradores de paquetes**:
- [yay](https://aur.archlinux.org/packages/yay-bin)
    ```Shell
    pacman -S git
    mkdir trash
    cd trash
    git clone https://aur.archlinux.org/yay-bin.git
    cd yay-bin
    makepkg -si
    cd ...
    rm -rf trash
    ```

- [paru](https://aur.archlinux.org/packages/paru)
- [pikaur](https://aur.archlinux.org/packages/pikaur)
- [chaotic-aur](https://aur.chaotic.cx)

**Shell**:
- [zsh](https://wiki.archlinux.org/title/Zsh)
    - [oh-my-zsh](https://ohmyz.sh)

**Herramientas**:
- [base](https://wiki.archlinux.org/title/Meta_package_and_package_group_(Espa%C3%B1ol)#Meta_paquetes) y base-devel
- [sudo](https://wiki.archlinux.org/title/Sudo)
- [git](https://wiki.archlinux.org/title/Git)
- [xorg-server](https://wiki.archlinux.org/title/Xorg)
- [xorg-xrandr](https://wiki.archlinux.org/title/Xorg)

**Volumen**:
- [alsa-utils](https://wiki.archlinux.org/title/Advanced_Linux_Sound_Architecture#ALSA_utilities) y alsa-plugins
- [pulseaudio](https://wiki.archlinux.org/title/PulseAudio) y pavucontrol

**Gestor de contraseñas**:
- [seahorse](https://wiki.archlinux.org/title/GNOME/Keyring)

**IDEs y editores**:
- [arduino](https://archlinux.org/packages/community/x86_64/arduino-cli/)[-cli](https://arduino.github.io/arduino-cli/0.23/installation/#use-the-install-script)
    ```Shell
    pacman -S arduino-cli
    mkdir trash
    cd trash
    curl -fsSL https://raw.githubusercontent.com/arduino/arduino-cli/master/install.sh | sh
    mv bin/arduino-cli /usr/bin/arduino-cli
    cd ..
    rm -rf trash
    ```
- [visual-studio-code-bin](https://aur.archlinux.org/packages/visual-studio-code-bin)
- [neovim](https://wiki.archlinux.org/title/Neovim)

**Fuentes**:
- [apple-fonts](https://aur.archlinux.org/packages/apple-fonts)
- [hack-nerd-fonts](https://aur.archlinux.org/packages/nerd-fonts-hack)
- [ttf-ms-fonts](https://aur.archlinux.org/packages/ttf-ms-fonts)

**Menús**:
- [rofi](https://wiki.archlinux.org/title/Rofi)

**Gestores de archivos**:
- [pcmanfm](https://wiki.archlinux.org/title/PCManFM)
- [ranger](https://wiki.archlinux.org/title/Ranger)

**Navegadores**:
- [brave](https://aur.archlinux.org/packages/brave-bin)
- [vivaldi](https://wiki.archlinux.org/title/Vivaldi)

**Oficina**:
- [libre](https://archlinux.org/packages/extra/x86_64/libreoffice-fresh/)[office](https://archlinux.org/packages/extra/x86_64/libreoffice-fresh/-es)
- [notable](https://aur.archlinux.org/packages/notable-bin)
- [teams-for-linux](https://aur.archlinux.org/packages/teams-for-linux)
- [zathura](https://wiki.archlinux.org/title/Zathura)

**Tarbajo remoto**:
- [rdesktop](https://wiki.archlinux.org/title/Rdesktop)
- [remmina](https://wiki.archlinux.org/title/Remmina)

**Gestor de ventanas**:
- [bspwm](https://wiki.archlinux.org/title/Bspwm)
    - [sxhkd](https://wiki.archlinux.org/title/Sxhkd)
    - [polybar](https://wiki.archlinux.org/title/Polybar)
- [qtile](https://wiki.archlinux.org/title/Qtile)

**Gestor de usuarios**:
- [lightdm](https://wiki.archlinux.org/title/LightDM)
    - [lightdm-gtk-greeter](https://archlinux.org/packages/extra/x86_64/lightdm-gtk-greeter/)

**Otros**:
- [feh](https://wiki.archlinux.org/title/Feh)
- [gotop](https://aur.archlinux.org/packages/gotop)
- [lolcat](https://archlinux.org/packages/community/any/lolcat/)
- [neofetch](https://archlinux.org/packages/community/any/neofetch/)
- [picom](https://wiki.archlinux.org/title/Picom)
- [python-psutil](https://archlinux.org/packages/community/x86_64/python-psutil/)
- [ueberzug](https://archlinux.org/packages/community/x86_64/ueberzug/)

## Configuraciones
- [GRUB](https://github.com/adnksharp/Lgrub)
- [zsh](https://github.com/adnksharp/LzshCfg)
- [alacritty](https://github.com/adnksharp/LalacrittyCfg)
- [ranger](https://github.com/adnksharp/LrangerCfg)
- [neofetch](https://github.com/adnksharp/LneofetchCfg)
- [Qtile](https://github.com/adnksharp/LQtileCfg)
- [rofi](https://github.com/adnksharp/LrofiCfg)
- [bspwm](https://github.com/adnksharp/Lbspwm)

##### Mi primer configuración
- [arch-old-config](https://github.com/adnksharp/LarchOLD)
