# Troubleshooting

## The installer checksum does not match

Do not run the installer. Delete it and download it again from the official GitHub Release page. If the mismatch persists, open a Bug Report without attaching the installer itself.

## Windows shows an unknown publisher warning

The current default installer is unsigned. Verify the source URL and SHA-256 before deciding whether to continue. See [Installation](installation.md).

## LM Studio or ComfyUI cannot connect

- Confirm the service is running.
- Confirm the endpoint configured in Animavyr matches the service address and port.
- Check the service's own logs and firewall settings.
- Review whether an imported workflow or custom node expects an external endpoint.

## A project or media file is unavailable

Confirm that the selected workspace, drive, network share, and referenced files are still available. Restore from backup if files were moved or removed outside Animavyr.
