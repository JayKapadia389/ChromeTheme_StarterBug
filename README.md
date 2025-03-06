# Chrome Theme

This repository contains a custom Chrome theme that changes the appearance of the browser. The theme is available as a packaged `.crx` file for easy installation and as an unpacked version for customization.

## Repository Structure

```
Chrome-Theme/
│── ChromeTheme.crx      # Packaged theme file
│── Unpacked/            # Unpacked source for customization
│   ├── images/          # Image assets used in the theme
│   ├── manifest.json    # Theme configuration
```

## Installation

### Method 1: Using the `.crx` File (Easy Installation)

1. Download the `ChromeTheme.crx` file from this repository.
2. Open Google Chrome and navigate to `chrome://extensions/`.
3. Enable **Developer Mode** (toggle switch in the top-right corner).
4. Drag and drop the `ChromeTheme.crx` file onto the extensions page.
5. Click **Add Theme** when prompted.

### Method 2: Using the Unpacked Source (For Customization & Development)

1. Download or clone this repository:
   ```sh
   git clone https://github.com/your-username/repository-name.git
   ```
2. Open Google Chrome and navigate to `chrome://extensions/`.
3. Enable **Developer Mode** (toggle switch in the top-right corner).
4. Click **Load unpacked** and select the `Unpacked` folder.
5. The theme will be applied instantly.

## Customization

If you want to modify the theme:

- Edit the `manifest.json` file inside the `Unpacked` folder.
- Replace images inside the `images/` directory.
- Use **Load unpacked** again from `chrome://extensions/` to apply the theme after making changes.

## Credits

Created by **Jay Kapadia** for **Google Summer of Code (GSoC) 2025** under **Chromium**.

---
