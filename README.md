# default-dotfiles

Collection of default dotfiles for easy reference
(focus on bash/sh shells).

## Ubuntu

Ubuntu 20.04 from `multipass shell`.

## Fedora

Fedora core 35 from `podman machine ssh`.

## macOS

macOS 12.0.1 Monterey

SSH configuration has changed layout from macOS 11 (Big Slur)'s single `sshd_config` file. Instead, `sshd_config` now sources `sshd_config.d/100-macos.conf` to enable password authentication.

## OpenBSD

OpenBSD 7.0

Default shell in openbsd is ksh <https://www.openbsdhandbook.com/openbsd_for_linux_users/>.

To add bash:

```sh
su
pkg_add bash
exit
chsh -s bash
# logout and login
```
