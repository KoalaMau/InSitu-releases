# InSitu

A markdown editor where you write and read in the same place. Markdown renders as you type, and its syntax shows only around the caret. Your files stay plain markdown on your disk.

**[Download the latest version](https://github.com/KoalaMau/InSitu-releases/releases/latest)** for Windows or Linux.

## Which file do I need?

| You use | Download | Then |
| --- | --- | --- |
| Windows 10 or 11 | `InSitu_…_x64-setup.exe` | Run it. The `.msi` is the same app, for managed installs. |
| Ubuntu, Debian, Linux Mint | `InSitu_…_amd64.deb` | `sudo apt install ./InSitu_…_amd64.deb` |
| Fedora, openSUSE | `InSitu-…x86_64.rpm` | `sudo dnf install ./InSitu-…x86_64.rpm` |
| Any other Linux | `InSitu_…_amd64.AppImage` | `chmod +x InSitu_*.AppImage`, then run it. No install needed. |

All builds are for 64-bit Intel and AMD processors. macOS isn't supported.

### "Windows protected your PC"
The Windows installer isn't code-signed yet, so Windows SmartScreen may stop it the first time. Click **More info**, then **Run anyway**.

## Updates
- **Windows and AppImage:** InSitu checks for a new version shortly after it starts, and asks before installing it. You can also use **Help › Check for updates…**, or turn the automatic check off in **Preferences › General**.
- **.deb and .rpm:** download and install the new package from the [latest release](https://github.com/KoalaMau/InSitu-releases/releases/latest). Installing it over the old one keeps your settings.

## Optional extras
- **[Pandoc](https://pandoc.org/installing.html)** adds export to Word, OpenDocument, EPUB and LaTeX. PDF, HTML and PNG export work without it.

## Problems or ideas
Open an [issue](https://github.com/KoalaMau/InSitu-releases/issues). Say which version you have (**Help › About**) and your system.

This repository only hosts the installers; the source code is kept elsewhere.
