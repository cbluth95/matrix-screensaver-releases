# Matrix Screensaver Pro

A high-performance Matrix-style digital rain screensaver for Windows with DirectX GPU acceleration.

![Matrix Screensaver](https://img.shields.io/badge/version-1.12.1-green)
![Platform](https://img.shields.io/badge/platform-Windows-blue)
![License](https://img.shields.io/badge/license-MIT-blue)

<img width="3750" height="1250" alt="logo-banner" src="https://github.com/user-attachments/assets/bfc34000-368c-48e1-80b2-24165b9eba5f" />

## ✨ Features

- 🚀 **60 FPS DirectX Rendering** - Smooth GPU-accelerated graphics
- 🎨 **Theme Presets** - Classic Green, Blue Matrix, Red Alert, Purple Haze, Rainbow
- 🌈 **Random Colors** - Each column in vibrant colors
- 🕐 **Clock Display** - Optional date and time overlay
- 🔄 **Mirror Mode** - Occasional upward-flowing columns
- 💬 **Easter Eggs** - Matrix quotes and messages
- 🎛️ **Live Settings** - Changes apply in real-time
- 🖥️ **Multi-Monitor** - Full support for multiple screens

## 📥 Download & Installation

### Latest Release: v1.12.1

**[Download MatrixSaverSetup-1.12.1.exe](https://github.com/cbluth95/matrix-screensaver-releases/releases/latest)**

### Installation Steps:

1. Download the installer from the [Releases page](https://github.com/cbluth95/matrix-screensaver-releases/releases)
2. Run `MatrixSaverSetup-1.12.1.exe` (no additional software required - includes .NET runtime)
3. Follow the installation wizard
4. Configure in Windows:
   - Right-click desktop → **Personalize**
   - Go to **Lock screen** → **Screen saver settings**
   - Select **"MatrixSaver"** from the dropdown
   - Click **Settings** to customize

## ⚙️ Configuration

### Speed & Density
- **Scroll Speed:** Controls how fast characters fall (1-100)
- **Variability:** Adds randomness to column speeds (0-100)
- **Density:** Control how many columns appear

### Theme Presets
Choose from predefined themes or create your own:
- **Classic Green** - Original Matrix style
- **Blue Matrix** - Cyberpunk cyan/blue theme
- **Red Alert** - Warning/danger red theme
- **Purple Haze** - Mystical violet/purple theme
- **Rainbow** - Random vibrant colors per column
- **Custom** - Define your own colors

### Display Options
- **Bold Characters** - Enhanced visibility
- **Show Title** - Display "The Matrix" overlay
- **Show Date & Time** - Clock in top-right corner
- **Glow Effect** - Character glow effect
- **Font Size** - Adjust character size (10-30px)

### Character Set
- **Katakana** - Japanese characters (authentic Matrix look)
- **Extended ASCII** - Alternative character set

### Special Effects
- **Mirror Mode** - Occasional upward-flowing columns
- **Easter Eggs** - Random Matrix quotes appear

## 🐛 Troubleshooting

### Settings Button Doesn't Work (Windows 11)
This is a known Windows 11 bug. Use these workarounds:

1. **Run Settings Directly:**
   - Open folder: `C:\Windows\System32\`
   - Right-click `MatrixSaver.scr`
   - Select **"Configure"**

2. **Command Line:**
   ```cmd
   C:\Windows\System32\MatrixSaver.scr /c
   ```

3. **Use the Settings shortcut** in the Start Menu (created during installation)

### Screensaver Doesn't Appear
- Verify installation in Screen Saver settings
- Check Windows power settings aren't overriding
- Try running `Refresh-Screensaver.bat` from the installation directory

### Performance Issues
- Update your graphics drivers
- Reduce density and font size in settings
- Disable glow effect if needed

## 📋 System Requirements

- **OS:** Windows 10 (64-bit) or Windows 11
- **RAM:** 100 MB minimum
- **Graphics:** DirectX 11 compatible GPU
- **Display:** 1920x1080 or higher recommended

## 📝 License

MIT License - Copyright (c) 2025 Cody Bluth

See [LICENSE](LICENSE) for full details.

## 🙏 Credits

Inspired by the Matrix film series.

Created by **Cody Bluth** - December 2025

## 📧 Support

For issues, questions, or feature requests:
- Open an issue on [GitHub Issues](https://github.com/cbluth95/matrix-screensaver-releases/issues)
- Check the [FAQ](https://github.com/cbluth95/matrix-screensaver-releases/wiki/FAQ) (coming soon)

---

*"Wake up, Neo..."*
