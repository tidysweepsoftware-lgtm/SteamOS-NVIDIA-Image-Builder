<img width="5712" height="4284" alt="IMG_2737" src="https://github.com/user-attachments/assets/74fe8238-b717-4649-884e-49bd9234f61b" />
<img width="5712" height="4284" alt="IMG_2739" src="https://github.com/user-attachments/assets/acad5e87-34a8-47e2-951a-7eb515a2dcd7" />
<img width="1101" height="769" alt="Screenshot 2026-07-29 070314" src="https://github.com/user-attachments/assets/1c62f8be-8ba4-4fdf-be2c-4ea8e3ed87b7" />



Description
-----------
NOW AVAILABLE IN MICROSOFT STORE:
https://apps.microsoft.com/detail/9NS4Z4L6VG32?hl=en-us&gl=US&ocid=pdpshare


SteamOS NVIDIA Image Builder is a guided Windows utility for advanced users
who want to prepare a copy of an official SteamOS recovery image for a PC with
an NVIDIA GeForce RTX GPU.

The app guides you through selecting a clean SteamOS image, choosing the
target RTX generation, preparing the Linux build engine, building the image,
and validating the result. It can configure the official Windows Subsystem
for Linux and Arch Linux environment for you. Windows may request
administrator permission and one restart while enabling these components.

The original image is never modified. The completed image, SHA256 checksum,
and detailed build report are placed in the output folder you choose.

Supported target profiles:
- NVIDIA GeForce RTX 20 series
- NVIDIA GeForce RTX 30 series
- NVIDIA GeForce RTX 40 series
- NVIDIA GeForce RTX 50 series

This is an independent experimental utility. It is not affiliated with,
endorsed by, or supported by Valve or NVIDIA. Results may vary by hardware.
Secure Boot must be disabled on the target PC. Always test with a spare drive
and keep backups.

Product features
----------------
- Guided one-click WSL2 and Arch Linux build-engine setup
- Automatic local NVIDIA GPU detection with manual target override
- RTX 20-, 30-, 40-, and 50-series target profiles
- Uses signed NVIDIA packages from official Arch Linux infrastructure
- Pins exact resolved package versions in the generated image
- Preserves the original SteamOS image
- Read-only validation of the completed image
- SHA256 checksum and build report
- Self-healing SteamOS update option
- Optional smaller image by removing CUDA compute components
- Portable Linux build-kit export
- WSL-compatible handling of Valve's casefold-enabled home partition
- Local processing with no accounts or tracking

What's new in 1.0.5
-------------------
- Uninstall Arch Linux button
- Verifies the selected environment is genuinely Arch Linux
- Clear permanent-deletion warning
- Defaults to No
- Disabled while building
- Never deletes completed images stored in Windows folders
- Refreshes the Linux environment list after removal

