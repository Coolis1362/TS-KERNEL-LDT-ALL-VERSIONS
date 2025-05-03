
# TS-KERNEL LDT (Linux Technology)

TS-KERNEL LDT (Linux Debian Technology) brings the core functionality of TS-KERNEL, originally for Windows, to Linux systems. It is designed to help you build and manage TS-DISTRO distributions on Linux.

## Features

- Core TS-KERNEL boot and user management scripts
- TS-KERNEL Language support
- User and admin configuration
- Bootloader and shutdown utilities
- Ready for extension and custom Linux distributions

## Project Structure

```plaintext
1.x.x/
  1.0.x/
    1.0.0/
      BTS/
        my-package/
          DEBIAN/
            control         # Package metadata
            postinst        # Post-install script
            postrm          # Post-remove script
          usr/
            bin/
              root/
                boot/
                  shutdown_windows.py
                  ts-distro-distro_name.py
                  bootloader/
                  python/
                  ts_kernel_language/
                ts-desktop/
                users/
```

See `filesystem for ts-kernel 1.0.1a2.txt` for a detailed breakdown.

## Installation

1. Make sure you have Python 3 installed.
2. Install the `.deb` package:
   ```bash
   sudo dpkg -i ts-kernel-lt_1.0.0_amd64.deb
   ```
3. After installation, you’ll see:
   ```
   TS-KERNEL Linux Technology Has Been Installed, Have fun Making TS-DISTRO Distros On Linux!
   ```

## Removal

To uninstall:
```bash
sudo dpkg --remove ts-kernel-lt
```

## Maintainer

- Coolis1362

## Notes

- For more details, see the scripts and configuration files in the `BTS/my-package` directory.
- Debian Package May Contain Bugs, Please Report Them.
- This Was Made In Kali Linux 2025.1 WSL and Good With `Debian`, `Ubuntu`, `Debian-based distros`, and `Ubuntu-based distros`.
- WARNING: THIS IS ONLY FRO `Debian`, `Ubuntu`, `Debian-based distros`, AND `Ubuntu-based distros`, SO IF YOU HAVE A RED HAT-BASED DISTRO (A DISTRO BASED ON A RED HAT-BASED DISTRO COUNTS AS A RED HAT-BASED DISTRO), GIT THE `.rpm` PACKAGE [HERE](https://github.com/Coolis1362/TS-KERNEL-RHT-ALL-VERSIONS)
