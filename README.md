# sidstall
Installable ISO for Debian sid a.k.a. stable rolling release

## Self-service guide (recommended)
Fork the repo.

Open Actions. Open the only workflow on the left side of the window. Click the big green button. Input a tag name (or leave it be), then click the big green button at the bottom of the screen. Wait 25 minutes and you have your install media (click on the Action run, then scroll down and it will give you a link to download the zip file that has the ISO).

## Download (deprecated)
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
