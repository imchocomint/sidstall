# sidstall
 Installable ISO for Debian sid a.k.a. stable rolling release

## Download
In Releases. Only available as GitHub Actions artifact due to release upload limit.

## Install
Comes with KDE Plasma 6 and Calamares. Should be easy for you.

### Post-install (crucial)
Run `sudo apt modernize-sources`

After that, use a text editor (like nano) with root to open the file /etc/apt/sources.list.d/debian.sources. In the "Suites" section, change it to 'sid' or 'forky'. Update the system.

## Bundled software
- KDE Plasma 6
- zsh
- kitty
- btop
- flatpak
