
# TS-KERNEL LT (Linux Technology)

TS-KERNEL LT (Linux Technology) brings the core functionality of TS-KERNEL, originally for Windows, to Linux systems. It is designed to help you build and manage TS-DISTRO distributions on Linux.

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

- `.rpm` packages will be released later.
- For more details, see the scripts and configuration files in the `BTS/my-package` directory.
