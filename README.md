<img width="1099" height="769" alt="Screenshot 2026-08-06 163234" src="https://github.com/user-attachments/assets/b5dc7865-3a29-4369-a22b-b95ebb7e6e46" />

<iframe width="560" height="315" src="[https://www.youtube.com/embed/video-id](https://youtu.be/0rwuAZqN0Ls)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


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

 

https://youtu.be/0rwuAZqN0Ls



SteamOS on NVIDIA desktop PCs is getting easier — major update now available

I’ve been developing SteamOS NVIDIA Image Builder, an independent Windows application that makes preparing a SteamOS installation image for NVIDIA-powered desktop and laptop PCs much simpler.

Instead of manually configuring Linux tools and entering a long series of commands, the application guides you through the process and prepares the NVIDIA-compatible image for you.

What’s new
Support for NVIDIA RTX 20, 30, 40 and 50 series GPUs

Guided NVIDIA driver integration

Automatic Linux build-environment setup

Improved SteamOS installation workflow

Better physical-drive detection

Drives clearly identified as empty, occupied, system-related or installer media

Empty drives shown as recommended installation targets

Clear warnings for drives containing Windows, partitions or personal files

Improved build validation, recovery and progress information

Option to remove the Arch Linux build environment when it is no longer needed

Tools for easier future NVIDIA driver maintenance

Arch Linux uninstall button in app

The original SteamOS recovery image is never modified. The application works from a copy, validates the finished image and generates a checksum and build report.

Download from Microsoft Store
Download SteamOS NVIDIA Image Builder

This tool is intended for desktop and laptop PCs, not handheld devices. It is experimental and unofficial, and it is not affiliated with, endorsed by or supported by Valve, NVIDIA or Microsoft.

Installation might take some time so please be patient!

Secure Boot may need to be disabled, and testing the generated image on a spare drive is strongly recommended. Installing an operating system can erase the selected drive, so always verify the drive information and keep a backup of important files.

The goal is to turn a complicated command-line procedure into a clear, guided process that more PC users can understand.

Feedback is very welcome—especially from people testing SteamOS on NVIDIA hardware. Which GPU are you using, and what would you like to see improved next?

