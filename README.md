# Jellyfin MPV Shim

This is the flatpak package for Jellyfin MPV Shim.

Please see: https://github.com/iwalton3/jellyfin-mpv-shim

## Updating

Use this command to update pypi-dependencies.
```
flatpak-pip-generator 'jellyfin-mpv-shim[all]' --output pypi-dependencies
```

Then add `--no-build-isolation` to the `pypi-dependencies.json` file.

## Based On

 - https://github.com/RomanKharin/flatpak-it-all
 - https://github.com/flathub/io.github.celluloid\_player.Celluloid

