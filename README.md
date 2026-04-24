# Lexitren Turkish English Translator Installer

Standalone Windows installer package for **Turkish English Translator**.

## Original Project Repository

- https://github.com/arifemreselvi/lexitren-tr-en-offline-translator

## Quick Download

- **[Download Installer EXE (output folder)](https://github.com/arifemreselvi/lexitren-tr-en-offline-translator-installer/raw/main/output/TurkishEnglishTranslatorSetup.exe)**
- **[Download Installer EXE (Latest Release - Recommended)](https://github.com/arifemreselvi/lexitren-tr-en-offline-translator-installer/releases/latest/download/TurkishEnglishTranslatorSetup.exe)**

## Developer

- **Arif Emre Selvi**
- 2nd year MIS (Management Information Systems) student

## Package Contents

- `output/TurkishEnglishTranslatorSetup.exe` - compiled installer
- `TurkishEnglishTranslatorInstaller.iss` - Inno Setup source script
- `CHECKSUMS.txt` - SHA256 hash for integrity verification

## Quick Install

1. Download `TurkishEnglishTranslatorSetup.exe` from one of the links above
2. Run the installer
3. Complete the setup wizard
4. Launch **Turkish English Translator** from Start Menu or desktop shortcut

## Verify File Integrity (Optional)

PowerShell:

```powershell
Get-FileHash ".\output\TurkishEnglishTranslatorSetup.exe" -Algorithm SHA256
