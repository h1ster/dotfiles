# CRUX + sowm dotfiles

# Software Stack

* **OS**: [CRUX GNU/Linux](https://crux.nu)
* **WM**: [sowm](https://github.com/dylanaraps/sowm)
* **Terminal**: `st-patched` (https://github.com/tinyopsec/st-patched/tree/main)
* **Launcher**: `dmenu`
* **Editor**: `neovim` (Currently transitioning to GNU/Emacs)
* **Wallpaper Manager**: `feh`
* **Sysinfo**: `mfetch`

# Repository Structure

* `sowm/` — Window manager source code with my custom `config.h`.
* `st-patched/` — Simple Terminal source code with applied patches.
* `mfetch/` — Minimal Linux fetch script.
* `.xinitrc` — Xorg initialization script (starts `feh`, `sxhkd`, and the WM).
* `wallpaper/` — The background image used in this setup.

# Wallpaper
The wallpaper image is included directly in this repository under `wallpaper/pri5857.jpg`.
The `.xinitrc` assumes this repo is cloned to `~/dotfiles`; adjust the `feh` path if you keep it elsewhere.

# License
This project is licensed under the GNU General Public License v3.0.
See the [LICENSE](LICENSE) file for the full license text.

