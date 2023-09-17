# ux310u-dotfiles-arch-hyprland
короч
чтобы дрова на нвидию воркали в хипленде, надо просто качнуть nvidia-dksm и добавить флаг nvidia_drm.modeset=1 в конец этой строки >> "GRUB_CMDLINE_LINUX_DEFAULT=" , которая находится в /etc/default/grub
чтобы работал сон через комбинацию FN + F1, надо качнуть acpid и ввести systemctl enable --now acpid.service
для вайргварда просто качнуть wireguard-tools
всё остальное интуитивно понятно
