# Dotfiles y configuraciones

Este archivo contiene las configuraciones y dotfiles que uso en mi computador. Ademas de los pasos que he hecho para instalar el sistema operativo que actualmente utilizo.

# Paquetes que utilizo

Para la instalacion del sistema operativo he seguido la guia de [Arch Linux](https://wiki.archlinux.org/title/Installation_guide) utilizando los siguientes paquetes:

- [linux-zen](https://wiki.archlinux.org/title/Kernel)
- linux-zen-headers
- linux-headers
- [base](https://wiki.archlinux.org/title/Meta_package_and_package_group_(Espa%C3%B1ol)#Meta_paquetes) y base-devel
- [sudo](https://wiki.archlinux.org/title/Sudo)
- [git](https://wiki.archlinux.org/title/Git)
- [vim](https://wiki.archlinux.org/title/Vim)
- [netwokmanager](https://wiki.archlinux.org/title/Networkmanager) y dhcpcd
- [grub](https://wiki.archlinux.org/title/Grub) y efibootmgr

## Primeras configuraciones

Como primeras coniguraciones, aparte de crear/modificar archivos de idioma, zona geografica, contraseñas, etc., he modificado el GRUB usando el tema [vimix](https://www.gnome-look.org/p/1009236).

    GRUB_DEFAULT=saved
    GRUB_TIMEOUT=1
    GRUB_SAVEDEFAULT=true
    GRUB_DISABLE_SUBMENU=y
    GRUB_THEME="/home/akey/Documentos/Betas/bash/grub/theme.txt"

# Servicios

Posterior ala instalacion del sistema operativo, he activado los servicios de `NetworkManager.service` y `dhcpcd.service`.

# Repositorios extras

Una vez instaldo el sistema operativo y activados los servicios, añado los repositorios de [yay](https://aur.archlinux.org/packages/yay-git), [paru](https://aur.archlinux.org/packages/paru-bin) y [chaotic-aur](https://aur.chaotic.cx/)

## Paquetes extras

Ademas de los paquetes de sistema operativo, codecs, etc., he instalado los siguientes paquetes:

- Fuentes
    - nerd-fonts-hack
    - noto-fonts
    - ttf-mac-fonts
    - ttf-ms-fonts

- Shell 
    - zsh

- Cursor
    - breeze-snow-cursor-theme

- Tema de escritorio
    - flat-remix-gtk 

- Teminales
    - alacritty
    - st
    - tilix

- Gestores de archivos
    - ranger
    - pcmanfm

- Editores de texto
    - neovim
    - visual-studio-code

- Gestor de ventas
    - qtile

- Gestor de sesiones
    - lightdm

## Configuraciones extras
- [Qtile](https://github.com/ADN227/aKLQtileCfg)
- [zsh](https://github.com/ADN227/aKLzshCfg)
- [neofetch](https://github.com/ADN227/aKLneofetchCfg)
- [ranger](https://github.com/ADN227/aKLrangerCfg)
- [rofi](https://github.com/ADN227/aKLrofiCfg)
- [alacritty](https://github.com/ADN227/aKLalacrittyCfg)
