# Trec GRUB Theme

A clean, minimalist, and modern theme for the GRUB bootloader.

![Preview Placeholder](https://via.placeholder.com/800x450?text=Add+your+screenshot+here)

## Features

- **Minimalist Design**: Focused on clarity and simplicity.
- **Custom Fonts**: Uses a dedicated font for a unique look.
- **Centered Layout**: Elegant placement of the boot menu.
- **High Contrast**: Easy to read color palette.

## Installation

### 1. Copy the theme
Clone this repository and copy the `trec-theme` folder to your GRUB themes directory:

```bash
sudo mkdir -p /boot/grub/themes
sudo cp -r trec-theme /boot/grub/themes/
```

### 2. Configure GRUB
Edit your `/etc/default/grub` file:

```bash
sudo nano /etc/default/grub
```

Find the line starting with `GRUB_THEME` (or add it) and set it to:

```text
GRUB_THEME="/boot/grub/themes/trec-theme/theme.txt"
```

### 3. Update GRUB
Apply the changes by updating your GRUB configuration:

**On Ubuntu/Debian/Linux Mint:**
```bash
sudo update-grub
```

**On Arch Linux/Fedora/Manjaro:**
```bash
sudo grub-mkconfig -o /boot/grub/grub.cfg
```

## Credits
- Background image and assets included in the `trec-theme` directory.

## License
This project is released under the [Unlicense](./LICENSE). See the LICENSE file for details.
