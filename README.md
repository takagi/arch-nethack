# arch-nethack (custom)

Arch Linux packaging for NetHack with a small keymap tweak. This repository is a manual fork of the original Arch Linux packaging repo on GitLab (not a GitLab-hosted fork).

Original repo: https://gitlab.archlinux.org/archlinux/packaging/packages/nethack

## Changes
- Swap letter-movement keys so `b` -> `n` and `n` -> `m` (SE).
- Move the `m` prefix (nopickup/reqmenu) to `b` so `m` is free for movement.

## Build
```
makepkg -sf
```

## Install
```
sudo pacman -U nethack-*.pkg.tar.zst
```
