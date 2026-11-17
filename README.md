# RCX Tower

Use the LEGO Mindstorms **USB IR tower** (RCX 1.0 / 2.0) on 64-bit Windows 10/11 and on
macOS, with no LEGO driver. It includes an NQC editor, firmware download, remote control of
the brick, and a bridge so BricxCC and other RCX software can use the tower.

This page only hosts the downloads. **[Get the latest version](../../releases/latest)**
(all versions are on the [Releases](../../releases) page).

## Which file

- **Windows**: `RCX-Tower-<version>-windows.exe`. Double-click it; nothing is installed.
  SmartScreen may warn about an unknown publisher: More info → Run anyway.
- **macOS, Apple silicon** (M1 and later): `RCX-Tower-<version>-mac-arm64.dmg`.
- **macOS, Intel**: `RCX-Tower-<version>-mac-x86_64.dmg`.

  Open the .dmg and drag RCX Tower to Applications. The app is not signed by Apple, so the
  first start is blocked: right-click the app, choose Open, then Open again (or System
  Settings → Privacy & Security → "Open Anyway").

## First start

On Windows, plug the tower in, open the **Setup** tab and click **Install tower driver**.
It binds the WinUSB driver that is already part of Windows; nothing is downloaded. The driver
is set per USB port, so do it again if you move the tower to a port it has not been in.
On macOS no driver is needed.

## Licences

RCX Tower is under the MIT licence. The apps include the LEGO RCX firmware 3.2.8 (copyright
The LEGO Group) and NQC by Dave Baum and John Hansen (Mozilla Public License 1.0, source at
<https://bricxcc.sourceforge.net/nqc/>). LEGO and Mindstorms are trademarks of the LEGO
Group, which does not sponsor or endorse this project.

This repository holds only the build workflow; the source is developed elsewhere.
