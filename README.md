# enable-konsole-on-bazzite
This adds the konsole desktop file to your share/applications directory

This is needed because the ublue devs decided to replace the native konsole with the pytix terminal which does not fit with the KDE desktop. This is a way to have konsole without having the flatpak.

## Install

Make the directory just to be sure that it exist

```bash
mkdir -p ~/.local/share/applications
```

Install the desktop file by running this

```bash
wget -P ~/.local/share/applications https://raw.githubusercontent.com/dnkmmr69420/enable-konsole-on-bazzite/refs/heads/main/org.kde.konsole.desktop
```

### Remove

To remove, just run this


```bash
rm -f ~/.local/share/applications/org.kde.konsole.desktop
```
