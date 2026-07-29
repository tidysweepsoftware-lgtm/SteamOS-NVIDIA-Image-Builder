SteamOS NVIDIA Image Builder 1.0.2
=================================

What this EXE does
------------------
- Selects and validates a clean, decompressed official SteamOS recovery .img.
- Can install and configure the official WSL2 and Arch Linux build engine.
- Checks the selected environment for every required Linux tool.
- Supports NVIDIA RTX 20-, 30-, 40-, and 50-series target profiles.
- Detects a locally installed NVIDIA GPU, with a manual target override.
- Copies the source image into Linux storage so it is never modified in place.
- Runs the original hardened builder without disabling any security checks.
- Validates the completed image read-only.
- Copies the image, SHA256 and build report into the chosen Windows folder.
- Can create a portable build kit for a real Arch-based Linux PC or VM.

What this EXE does NOT do
-------------------------
- It does not contain or redistribute SteamOS or NVIDIA software.
- It does not flash a USB drive.
- It does not install SteamOS or erase a Windows disk.
- It cannot make NVIDIA support official.

Linux build engine
------------------
Select Set up in the app. Windows may request administrator permission and
may require one restart while it enables official WSL2 components. The app
then installs the official Arch Linux distribution and these tools:
losetup, blkid, btrfs, debugfs, rsync, curl, depmod, sed, awk, tar, zstd, pacman,
python3, readelf, sha256sum, findmnt, mount, umount, mountpoint, udevadm,
chroot, systemctl, and Linux loop-device support.

Allow more than 20 GiB free beside the image and in Linux storage.

Safety
------
Use only a clean recovery image downloaded directly from Valve. Secure Boot
must be disabled on the target PC. Test the generated installer on a spare
SSD and keep backups. The later SteamOS installation step is destructive when
the wrong disk is deliberately selected and confirmed.

This independent project is not affiliated with or endorsed by Valve or
NVIDIA. SteamOS, Steam, NVIDIA, GeForce, and RTX are marks of their respective
owners. See the embedded MIT license and source documentation.
