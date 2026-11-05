# NVIDIA Driver 385.08

This repository contains an archived NVIDIA graphics driver package, version
385.08, for supported Windows systems. It includes the original NVIDIA
installer, display driver files, HD Audio components, NView profiles, NVWMI
components, and localized installer resources.

## Installation

Run `setup.exe` from the repository root on a compatible Windows installation.
The installer supports x86 and AMD64 platforms according to the package
metadata. Create a system restore point and back up important data before
installing legacy drivers.

## Repository Contents

- `Display.Driver/`: NVIDIA display driver and graphics runtime files
- `HDAudio/`: NVIDIA HD Audio driver files
- `Display.NView/`: NView configuration profiles
- `NVWMI/`: NVIDIA WMI components
- `NVI2/`: installer interface resources and localized strings
- `setup.exe`: package installer

The large `Display.Driver/NvCplSetupInt.exe` file is stored with Git LFS. Git
LFS must be installed before cloning or checking out the complete package.

## License

The included driver binaries, installer, and documentation remain subject to
their respective NVIDIA license terms. See `EULA.txt`, `license.txt`, and the
license files included in the component directories.