# Turkish English Translator Installer

Standalone Windows installer package for **Turkish English Translator**.

## Original Project Repository

- https://github.com/arifemreselvi/lexitren-tr-en-offline-translator

## Quick Download

- Download only the installer executable: `output/TurkishEnglishTranslatorSetup.exe`

## Creator

- **Arif Emre Selvi**
- 2nd year MIS (Management Information Systems) student

## Package Contents

- `output/TurkishEnglishTranslatorSetup.exe` - compiled installer
- `TurkishEnglishTranslatorInstaller.iss` - Inno Setup source script
- `CHECKSUMS.txt` - SHA256 hash for integrity verification

## Quick Install

1. Download `output/TurkishEnglishTranslatorSetup.exe`
2. Run the installer
3. Complete the setup wizard
4. Launch **Turkish English Translator** from Start Menu or desktop shortcut

## Verify File Integrity (Optional)

PowerShell:

```powershell
Get-FileHash ".\output\TurkishEnglishTranslatorSetup.exe" -Algorithm SHA256
```

Compare the result with `CHECKSUMS.txt`.

## Build Installer From Script

Requires Inno Setup 6.

```powershell
& "C:\Users\<YourUser>\AppData\Local\Programs\Inno Setup 6\ISCC.exe" ".\TurkishEnglishTranslatorInstaller.iss"
```

## System Requirements

- Windows 10 or Windows 11 (64-bit)
- Minimum 1 GB free disk space recommended
