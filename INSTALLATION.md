# Installation Guide - Matrix Screensaver Pro

## Quick Install (Recommended)

1. **Download** the latest installer: `MatrixSaverSetup-1.12.1.exe`
2. **Run the installer** (right-click → Run as administrator if needed)
3. **Follow the wizard** - it will automatically:
   - Install the screensaver to `C:\Windows\System32\`
   - Create Start Menu shortcuts
   - Install required .NET runtime (if not present)
4. **Configure Windows:**
   - Right-click desktop → **Personalize**
   - **Lock screen** → **Screen saver settings**
   - Select **"MatrixSaver"**
   - Click **Preview** to test
   - Click **Settings** to customize (see note below)

## Configuration

### Opening Settings (Important)

⚠️ **Known Issue:** The Settings button in Windows 11's screensaver control panel may not work due to a Windows bug.

**Workarounds:**

**Method 1 - Use Start Menu Shortcut:**
- Search for "Matrix Screensaver Settings" in Start Menu
- Click to open settings directly

**Method 2 - Manual Launch:**
1. Open File Explorer
2. Navigate to `C:\Windows\System32\`
3. Find `MatrixSaver.scr`
4. Right-click → **Configure**

**Method 3 - Command Line:**
```cmd
C:\Windows\System32\MatrixSaver.scr /c
```

**Method 4 - PowerShell:**
```powershell
Start-Process "C:\Windows\System32\MatrixSaver.scr" -ArgumentList "/c"
```

## Manual Installation (Advanced)

If you prefer not to use the installer:

1. **Extract files** from the installer or download the portable version
2. **Copy `MatrixSaver.scr`** to `C:\Windows\System32\`
   ```cmd
   copy MatrixSaver.scr C:\Windows\System32\MatrixSaver.scr
   ```
3. **Refresh screensaver cache:**
   ```cmd
   RunDll32.exe desk.cpl,InstallScreenSaver %SystemRoot%\System32\MatrixSaver.scr
   ```

## Uninstallation

### Via Windows Settings (Recommended)
1. Go to **Settings** → **Apps** → **Installed apps**
2. Find **"Matrix Screensaver Pro"**
3. Click the three dots → **Uninstall**

### Manual Uninstall
1. Delete `C:\Windows\System32\MatrixSaver.scr`
2. Delete settings: `%LocalAppData%\MatrixSaver\`
3. Remove Start Menu shortcuts (if any)

## Troubleshooting

### "File is blocked" or "Windows protected your PC"
This is normal for new executables. Click **"More info"** → **"Run anyway"**

### Screensaver doesn't appear in list
1. Restart Windows
2. Try running as administrator
3. Run the refresh command:
   ```cmd
   RunDll32.exe desk.cpl,InstallScreenSaver %SystemRoot%\System32\MatrixSaver.scr
   ```

### Settings won't save
- Check folder permissions: `%LocalAppData%\MatrixSaver\`
- Try running settings as administrator once

### Performance issues
- Update graphics drivers
- Reduce density in settings
- Disable glow effects
- Lower font size

## System Requirements

- **Operating System:** Windows 10 (64-bit) or Windows 11
- **Processor:** Any modern CPU (dual-core recommended)
- **Memory:** 100 MB RAM minimum
- **Graphics:** DirectX 11 compatible GPU
- **Storage:** 50 MB available space
- **.NET:** Included in installer (self-contained)

## Multi-Monitor Setup

The screensaver automatically detects and displays on all connected monitors. No additional configuration needed.

## Command Line Options

For advanced users:

```cmd
MatrixSaver.scr /s        # Run screensaver
MatrixSaver.scr /c        # Open configuration
MatrixSaver.scr /p [HWND] # Preview mode
```

## Need Help?

- Check the [main README](README.md) for features and usage
- Report issues on [GitHub Issues](https://github.com/cbluth95/matrix-screensaver-releases/issues)
- See the FAQ (coming soon)

---

*Enjoy the digital rain!*
