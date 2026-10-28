![FieldCalc](docs/banner.png)

# FieldCalc

**Field engineering calculations — offline, step by step, with PDF reports.**
By Arapai Technologies International · Advancing Innovation

FieldCalc covers electrical, electronics, civil and mechanical engineering, with a nuclear module for estimation and awareness only. Every result shows its formula and working, and can be exported as a PDF calculation sheet. It needs no internet connection, account or ads.

## Download

Get the latest version from the **[Releases page](../../releases/latest)**.

| Platform | File | Notes |
|----------|------|-------|
| Android 7.0+ | `FieldCalc-<version>.apk` | See *Installing on Android* below |
| Windows 10/11 (64-bit) | `FieldCalc-<version>-windows-x64.zip` | Unzip and run `FieldCalc.exe` |

FieldCalc will also be available on Google Play and the Microsoft Store. Store versions update automatically.

### Installing on Android
1. Download the `.apk` file on your phone.
2. Open it. If Android asks, allow your browser or file manager to **install unknown apps**.
3. Tap **Install**.

To check the download, compare its SHA-256 with the value listed in the release notes.

### Installing on Windows
1. Download and unzip the `.zip` file to a folder, for example `C:\FieldCalc`.
2. Run `FieldCalc.exe`.
3. If Windows SmartScreen shows "Windows protected your PC", choose **More info → Run anyway**. This appears because the download is not code-signed. The Microsoft Store version does not show it.

Calculation history is stored in `%APPDATA%\FieldCalc`.

## Screenshots

| Windows | Android |
|---------|---------|
| ![Desktop](docs/desktop.png) | ![Android](docs/android.png) |

## What's included

- **Electrical:** cable sizing and voltage drop (IEC 60364-5-52, BS 7671), load schedule, solar PV, battery bank, transformer, power factor correction, short-circuit current
- **Electronics:** resistor networks and dividers, RC/RL/LC filters, op-amp circuits, power supply, PCB trace width (IPC-2221), battery runtime, Edge AI estimates
- **Civil:** concrete volumes and materials, beam deflection, column load, pipe flow and drainage, soil bearing
- **Mechanical:** pump sizing, motor selection, shaft power, heat load, belt and pulley
- **Nuclear (estimation only):** dose rate, shielding thickness, isotope decay
- **Field measurement:** measure lengths from a photo using a reference object

On Android, the load schedule, solar off-grid, power supply and battery runtime calculators are available on Windows only for now.

> FieldCalc is a calculation aid. Have results checked by a qualified engineer before using them in design, construction or safety decisions. The nuclear module is not certified software.

## Privacy

FieldCalc collects no data. See the [privacy policy](PRIVACY_POLICY.md).

## Support

Email **arapaigroup@gmail.com**, or open an issue on this repository.

---
© 2026 Arapai Technologies International. All rights reserved.
