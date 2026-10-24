Nova Linux

An experimental Debian-based mobile Linux project for Xiaomi Redmi 8 (olive).

Nova Linux is an open-source project exploring the possibility of running a Debian-based Linux environment on the Xiaomi Redmi 8 smartphone.

Project Information

- Project: Nova Linux
- Target device: Xiaomi Redmi 8 ("olive")
- Architecture: ARM64 (AArch64)
- Base system: Debian GNU/Linux (Trixie)
- Desktop environment: Phosh
- Display server: Wayland
- Init system: systemd
- Networking: NetworkManager
- Filesystem: ext4

Features and Goals

- Debian-based ARM64 root filesystem
- Mobile-friendly Phosh interface
- Wayland graphical environment
- systemd service management
- NetworkManager integration
- Modular build scripts and configuration files
- Future hardware support for the Xiaomi Redmi 8

Project Status

Experimental — work in progress.

The repository contains an initial project scaffold and build-related files. A complete, verified bootable operating system for the Xiaomi Redmi 8 is not yet available.

Device-specific kernel support, device tree configuration, boot image integration, hardware drivers, and bootloader compatibility still require development and testing.

Repository Contents

The repository may include:

- Build scripts
- Root filesystem configuration
- System configuration files
- Application source code
- Documentation and development notes

Target Device

Xiaomi Redmi 8 ("olive")

- SoC: Qualcomm Snapdragon 439
- CPU architecture: ARM64
- Intended userspace: Debian Trixie ARM64

Hardware compatibility and boot functionality must be verified on the actual device.

Development

Development is focused on building the ARM64 userspace, preparing the mobile graphical environment, and investigating the device-specific components needed for booting Linux.

Contributions, testing, documentation improvements, and hardware research are welcome.

Disclaimer

This project is experimental software provided for development and educational purposes. It is not an official Xiaomi product and is not affiliated with Xiaomi.

Do not attempt to flash unverified images to your device. Bootloader unlocking and firmware modifications may erase data or make the device unusable.

License

No license has been selected yet. Until a license is added, the source code is not automatically granted an open-source reuse license.
