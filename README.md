# Helper

VB6 Installation Helper Windows service host (`Helper.exe` / service name `InstallationHelper`) built with `NTSVC.ocx`, MSXML 4.0, and Scripting Runtime; driven by `config.xml` / `Description.xml` on a timer. Open `Helper.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Helper` (`Helper.vbp`) | VB6 | WinForms exe | Installation Helper |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Helper.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `NTSVC.ocx`

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Helper`.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
