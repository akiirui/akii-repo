# Akii's Unofficial User Repository

This repository include some **AUR packages** and some packages **with custom patches**.

All packages build for `[testing]`, ensure enabled `[testing]`.

_This GitHub repo isn't include AUR PKGBUILDs except my packages._

### Usage

1. Add repo to your `pacman.conf`:

   ```
   [akatsuki]
   Server = https://repo.akii.work/$arch
   ```

2. [Add PGP key][archwiki]:

   - `0x94E976626C884E53`

   The PGP key file can find on [GitHub][key-github] and [Repository][key-repo].

[archwiki]: https://wiki.archlinux.org/index.php/Pacman/Package_signing#Adding_unofficial_keys
[key-github]: https://github.com/akiirui/repo/blob/main/akatsuki.pub
[key-repo]: https://repo.akii.ml/akatsuki.pub

### Troubleshooting

- Please contact me via [issues][issues].

[issues]: https://github.com/akiirui/repo/issues/new

---

### Packages

- [dofi-manager][dofi-manager] <sup>AUR</sup>
- [fish-git][fish-git] <sup>AUR</sup>
- [gnome-browser-connector][gnome-browser-connector] <sup>AUR</sup>
- [mpv-handler][mpv-handler] <sup>AUR</sup>
- [paru][paru] <sup>AUR</sup>
- [systemd-oomd-defaults][systemd-oomd-defaults] <sup>AUR</sup>
- [ttf-paratype][ttf-paratype] : Replace [AUR/ttf-paratype](https://aur.archlinux.org/packages/ttf-paratype/), remove fontconfig conf file.
- [v2ray-domain-list-china][v2ray-domain-list-china] <sup>AUR</sup>

[dofi-manager]: https://aur.archlinux.org/packages/dofi-manager
[fish-git]: https://aur.archlinux.org/packages/fish-git
[gnome-browser-connector]: https://aur.archlinux.org/packages/gnome-browser-connector
[mpv-handler]: https://aur.archlinux.org/packages/mpv-handler
[paru]: https://aur.archlinux.org/packages/paru
[systemd-oomd-defaults]: https://aur.archlinux.org/packages/systemd-oomd-defaults
[ttf-paratype]: https://github.com/akiirui/repo/tree/main/ttf-paratype
[v2ray-domain-list-china]: https://aur.archlinux.org/packages/v2ray-domain-list-china

---

### Devel Packages

**These packages haven't binary build, for archive only.**

- [akwaita-theme-git][akwaita-theme-git] <sup>AUR</sup>
- [dofi-manager-git][dofi-manager-git] <sup>AUR</sup>
- [mpv-handler-git][mpv-handler-git] <sup>AUR</sup>
- [paru-git][paru-git] <sup>AUR</sup>

[akwaita-theme-git]: https://aur.archlinux.org/packages/akwaita-theme-git/
[dofi-manager-git]: https://aur.archlinux.org/packages/dofi-manager-git/
[mpv-handler-git]: https://aur.archlinux.org/packages/mpv-handler-git/
[paru-git]: https://aur.archlinux.org/packages/paru-git/

---

### Archived Packages

**These packages not update anymore, for archive only.**

- [flat-remix-gnome][flat-remix-gnome]: Replace [AUR/flat-remix-gnome](https://aur.archlinux.org/packages/flat-remix-gnome/)

[flat-remix-gnome]: https://github.com/akiirui/repo/tree/main/flat-remix-gnome
