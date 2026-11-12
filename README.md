# Soạn Nôm

Type Chữ Nôm (𡨸喃) from Telex in any app, on macOS, Windows and Linux. Made by [Nôm Na Việt](https://nomnaviet.com).

Type a word in Telex (`vieejt`), and pick its Nôm character from the list: Space takes the first, 1–9 pick by number, the arrows move and turn pages, Esc puts the list away. After a word, it suggests the characters that often come next, picked the same way. Syllables, toneless typing and compounds all work, on the Nôm Na Việt dictionary.

This repository holds the downloads only. The same input method is also in the [Nôm Na Việt app](https://nomnaviet.com) for iPhone and Android, and in the [Soạn Nôm IME](https://chromewebstore.google.com/detail/kmlmnpafcnomgnbpobldglokdhepembe) Chrome extension.

## Download

From the [latest release](https://github.com/nomnaviet/soan-nom/releases/latest):

| System | File |
|---|---|
| macOS 12 or later | `SoanNom-<version>.dmg` |
| Windows 10 or 11 (64-bit) | `SoanNom-Setup-<version>.exe` |
| Ubuntu, Debian (22.04 / 12 or later) | `ibus-nom_<version>_amd64.deb` (ARM: `_arm64.deb`) |
| Fedora and other RPM systems | `ibus-nom-<version>.x86_64.rpm` (ARM: `.aarch64.rpm`) |

`SHA256SUMS` in each release lists every file's checksum.

## Install

### macOS

1. Open the `.dmg` and drag **Nôm** onto **Input Methods** (macOS asks for your password).
2. Open the Input Methods folder and double-click **Nôm**. It joins the input menu at once.
3. Switch to it from the input menu or with Control-Space.

If Nôm does not show up, add it in System Settings → Keyboard → Text Input → Edit → + → Vietnamese, or log out and back in.

### Windows

1. Run `SoanNom-Setup-<version>.exe`. Windows may warn about an unknown publisher (the installer is not code-signed yet): choose More info → Run anyway.
2. Switch to Nôm with Windows+Space. It is listed under Vietnamese, which the installer adds if you did not have it.

Apps that were already open pick Nôm up once you reopen them. Both 64-bit and 32-bit apps are supported. Uninstall from Settings → Apps.

### Linux (IBus)

```sh
sudo apt install ./ibus-nom_<version>_amd64.deb      # Ubuntu, Debian
sudo dnf install ./ibus-nom-<version>.x86_64.rpm     # Fedora
ibus restart
```

Then add it: GNOME Settings → Keyboard → Input Sources → + → Vietnamese → Nôm (other desktops: `ibus-setup` → Input Method → Add). Switch with Super+Space.

## Problems and ideas

Write to support@nomnaviet.com, or open an issue here.
