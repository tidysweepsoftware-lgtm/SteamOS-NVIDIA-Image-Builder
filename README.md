# SteamOS NVIDIA Image Builder

**Prepare a SteamOS recovery image for NVIDIA RTX-powered desktop and laptop PCs through a guided Windows interface.**

> [!WARNING]
> This is an independent, experimental utility. It is not affiliated with, endorsed by, or supported by Valve, NVIDIA, or Microsoft. Results can vary by hardware. Always keep backups and test the generated image on a spare drive first.

<img width="1099" height="769" alt="SteamOS NVIDIA Image Builder application interface" src="https://github.com/user-attachments/assets/b5dc7865-3a29-4369-a22b-b95ebb7e6e46" />

## Download

**NOW AVAILABLE IN MICROSOFT STORE**

<a href="https://apps.microsoft.com/detail/9NS4Z4L6VG32?hl=en-us&gl=US&ocid=pdpshare">
  <img
    src="https://img.shields.io/badge/Get_it_from-Microsoft_Store-0078D4?style=for-the-badge&logo=microsoft&logoColor=white"
    alt="Get SteamOS NVIDIA Image Builder from Microsoft Store"
    width="400">
</a>

## What it does

SteamOS NVIDIA Image Builder prepares a copy of a SteamOS recovery image for PCs equipped with supported NVIDIA GeForce RTX graphics cards.

The app guides you through selecting a clean SteamOS image, choosing the target RTX generation and driver, preparing the Linux build engine, building the modified image, and validating the result. It can configure Windows Subsystem for Linux 2 and the required Arch Linux environment for you.

The original recovery image is never modified. The completed image, its SHA-256 checksum, and a detailed build report are placed in the output folder you select.

## How it works

1. Install and open the application on Windows.
2. Select a clean SteamOS recovery image.
3. Choose an output folder.
4. Confirm the detected NVIDIA GPU family or select it manually.
5. Choose the NVIDIA driver and prepare the Linux build engine.
6. Build and validate the new image.
7. Write the completed image to installation media and test it on a spare drive.

Windows may request administrator permission and one restart while enabling WSL2 and the required Linux components.

## Requirements

- Windows 10 or Windows 11, 64-bit
- UEFI-capable desktop or laptop PC
- NVIDIA GeForce RTX 20, 30, 40, or 50 series GPU
- At least 20 GB of available storage
- Hardware virtualization enabled for WSL2
- Administrator permission
- Internet access while preparing the build engine and obtaining packages
- Secure Boot disabled on the target PC

## Supported GPU profiles

| GPU generation | Target profile |
|---|---|
| NVIDIA GeForce RTX 20 series | Turing |
| NVIDIA GeForce RTX 30 series | Ampere |
| NVIDIA GeForce RTX 40 series | Ada Lovelace |
| NVIDIA GeForce RTX 50 series | Blackwell |

## Features

- Guided WSL2 and Arch Linux build-engine setup
- Automatic local NVIDIA GPU detection with manual override
- RTX 20-, 30-, 40-, and 50-series target profiles
- NVIDIA packages obtained from official Arch Linux infrastructure
- Exact resolved package versions recorded in the generated image
- Original SteamOS image preserved
- Read-only validation of the completed image
- SHA-256 checksum and detailed build report
- Self-healing SteamOS NVIDIA driver maintenance option
- Improved physical-drive detection during SteamOS installation
- Empty, occupied, system-related, and installer drives clearly identified
- Optional smaller image by excluding CUDA compute components
- Portable Linux build-kit export
- Option to remove the Arch Linux build environment when it is no longer needed
- Local processing with no accounts or tracking

## Video tutorial

[![Watch the SteamOS NVIDIA Image Builder tutorial](https://img.youtube.com/vi/0rwuAZqN0Ls/maxresdefault.jpg)](https://www.youtube.com/watch?v=0rwuAZqN0Ls)

**[▶ Watch the complete tutorial on YouTube](https://www.youtube.com/watch?v=0rwuAZqN0Ls)**

## Installation safety

> [!CAUTION]
> Installing an operating system can permanently erase the selected drive. Carefully verify the drive model, capacity, contents, and warning status before continuing. Disconnect drives that should never be modified and keep a backup of all important files.

SteamOS NVIDIA support remains experimental. Display compatibility, Gamescope behavior, updates, and performance may differ between GPUs and systems.

## Privacy

Image preparation and validation run locally. The application does not require an account and does not include tracking. Internet access is used only when required to configure the build environment and obtain the necessary packages.

## Support and feedback

- **Report a problem:** [Open a GitHub issue](https://github.com/tidysweepsoftware-lgtm/SteamOS-NVIDIA-Image-Builder/issues)
- **Email:** [tidysweepsoftware@gmail.com](mailto:tidysweepsoftware@gmail.com)

Feedback from people testing different RTX GPUs and PC configurations is welcome.

## Disclaimer

SteamOS, NVIDIA, GeForce, RTX, Windows, and Microsoft Store are names or trademarks belonging to their respective owners. TidySweep Software is not affiliated with, endorsed by, or supported by Valve, NVIDIA, or Microsoft.
