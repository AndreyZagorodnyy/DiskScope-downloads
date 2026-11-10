# DiskScope

**DiskScope** is a free portable utility for Windows 10 and 11. It helps you see what uses disk space, choose temporary files to clean, and monitor your computer.

## Download

Open **Releases** in this repository and download `DiskScope-1.0-2026-11-11.zip` from the latest release. Extract the ZIP and run `DiskScope.exe`. No installation or account is required.

The release also provides `SHA256-archive.txt` to verify the downloaded ZIP and `diskscope.pub` to verify the EXE's internal signature. The internal signature is not a Windows publisher certificate, so SmartScreen may show a warning on first launch.

## Features

- CPU, GPU, and memory usage, with a configurable mini widget.
- Disk scans with a space map, categories, large files, and duplicates.
- An estimate of temporary files, caches, and Recycle Bin contents before you choose what to clean.
- Network transfer rates and applications with active connections.
- Optional background history of free disk space and folder growth monitoring.
- Drive speed and surface tests, plus health information available from Windows.
- Deleted file and post-format recovery scans; selected file, free-space, and volume wiping.

## Important limits

File recovery is not guaranteed. Save recovered files to a different physical drive. Wiping a whole volume deletes all its files. On SSDs and flash drives, logical overwriting cannot guarantee removal of every physical copy. Some sensor readings depend on Windows and the device driver.

This is a preview release of version 1.0. Automated checks and a manual review of the main screens have been completed. Full-volume wiping, saving recovered files, and the effect on in-game FPS have not been retested on the final build.

DiskScope works locally. Author: **Keksik**. The source code is not public yet; this repository hosts the description and downloadable releases.
