# Installing Animavyr on Windows

1. Open the [latest release page](https://github.com/Niaudio/Animavyr/releases/latest).
2. Download `Animavyr-Setup-x64.exe` or the versioned Windows x64 installer.
3. Download the matching `.sha256` file and compare the installer checksum before running it.
4. Run the installer and follow the Windows prompts.
5. Launch Animavyr from the Start menu or desktop shortcut.

## Unknown Publisher and SmartScreen

The current default installer is unsigned. Windows may therefore show an unknown-publisher or SmartScreen warning. Confirm that the download came from this repository's official Release page and that its SHA-256 matches the attached checksum before choosing to continue.

An unsigned installer is not evidence of tampering by itself, but it does not provide Authenticode publisher identity. Stop if the checksum differs or the download came from another location.

## LM Studio and ComfyUI

LM Studio and ComfyUI are optional and are not bundled with Animavyr. Install and run them separately only if you want to use the corresponding local AI features.
