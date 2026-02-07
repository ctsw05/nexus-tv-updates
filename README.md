# 📺 NEXUS TV - INSTALLATION GUIDE

## Why Does Windows Block This App?

Nexus TV is a **safe, legitimate IPTV player**, but Windows shows security warnings because:

- ✖️ **Not code-signed** - Digital certificates cost $200/year (we're an independent project)
- ✖️ **New application** - Windows doesn't recognize the publisher yet
- ✖️ **Heuristic detection** - Antivirus flags unknown software by default

**This is a FALSE POSITIVE** - the app is completely safe.

---

## 🛡️ What Nexus TV Does NOT Do

The app is safe and does NOT:

❌ Steal your data  
❌ Install viruses or malware  
❌ Access your personal files  
❌ Send information to third parties  
❌ Mine cryptocurrency  
❌ Encrypt your files  
❌ Track your activity  
❌ Install spyware  

**What it DOES do:**
✅ Stream IPTV content you provide  
✅ Check for updates from GitHub (our official repository)  
✅ Store your playlists and preferences locally on your PC  
✅ Run in system tray for quick access  

These are **normal behaviors** for an IPTV player, but antivirus software can't verify this without a digital signature.

---

## 🔍 How to Verify It's Safe

**Option 1: Check VirusTotal**
1. Upload the .exe to [VirusTotal.com](https://www.virustotal.com/)
2. Most antivirus engines will show it's clean
3. Any detections are heuristic false positives, not actual threats

**Option 2: Check the Source Code**
- All code is open source on GitHub
- No hidden or obfuscated code

---

## 📥 Installation Instructions

### Step 1: Download
Download `Nexus-TV-Setup-1.0.1.exe` from:
- [GitHub Releases([https://github.com/ctsw05/nexus-tv-updates/releases/tag/NexusTV-IPTV-PLAYER](https://github.com/ctsw05/nexus-tv-updates/releases/tag/NexusTV-IPTV-PLAYER))) (recommended)
- Official website (if you have one)

### Step 2: Install (Windows Defender)

When you run the installer, Windows will show a warning:

**"Windows protected your PC"**

This is expected. Here's how to proceed:

1. Click **"More info"** on the warning screen
2. Click **"Run anyway"** button
3. Follow the installation wizard
4. Launch Nexus TV from Start Menu or Desktop

**Visual Guide:**
```
┌─────────────────────────────────────┐
│  Windows protected your PC          │
│                                     │
│  Windows Defender SmartScreen       │
│  prevented an unrecognized app...   │
│                                     │
│  [More info]  ← Click here first    │
└─────────────────────────────────────┘

Then:

┌─────────────────────────────────────┐
│  Windows protected your PC          │
│                                     │
│  App: Nexus TV Setup.exe            │
│  Publisher: Unknown publisher       │
│                                     │
│  [Run anyway]  ← Click here         │
└─────────────────────────────────────┘
```

### Step 3: If Using Avast Antivirus

If Avast blocks the installation:

**Option A: Temporarily Allow**
1. Right-click Avast icon in system tray
2. Select **"Avast shields control"**
3. Choose **"Disable for 10 minutes"**
4. Install Nexus TV
5. Re-enable Avast

**Option B: Add Exception**
1. Open Avast
2. Go to **Menu → Settings → Exceptions**
3. Click **"Add Exception"**
4. Browse to `Nexus TV Setup.exe`
5. Click **"Add Exception"**
6. Run installer

**Option C: After Installation**
1. Install with Avast disabled (Option A)
2. Add `C:\Program Files\Nexus TV\` to Avast exceptions
3. Re-enable Avast
4. App will run normally

### Step 4: If Using Other Antivirus

**Norton, McAfee, Bitdefender, etc.:**
1. Temporarily disable antivirus
2. Install Nexus TV
3. Add installation folder to antivirus exceptions:
   - `C:\Program Files\Nexus TV\`
   - `C:\Users\YourName\AppData\Local\nexus-tv\`
4. Re-enable antivirus

---

## ❓ Frequently Asked Questions

### Why isn't the app code-signed?

Code signing certificates cost $200-500 per year and require business verification. As an independent open-source project, we haven't obtained one yet. This doesn't mean the app is unsafe - it just means Windows can't verify the publisher.

### Will you get code signing in the future?

We're considering it, but can't make promises. For now, the app works perfectly without it - you just need to click "Run anyway" once during installation.

### Why does the app need internet access?

Nexus TV needs internet to:
- Stream IPTV content from your playlists
- Download EPG (TV guide) data
- Check for app updates from GitHub

This is normal for any IPTV player.

### Can I use Nexus TV offline?

You need internet to stream content, but the app itself will run offline. You just won't be able to watch anything without an internet connection.

### Does the app phone home or collect data?

**No.** Nexus TV:
- Does NOT send telemetry
- Does NOT track your viewing
- Does NOT collect personal information
- Only connects to: your IPTV streams, EPG servers, and GitHub for updates

Everything is stored locally on your computer.

### What if I still don't trust it?

That's totally fine! Security concerns are valid. Here's what you can do:
1. Review the [source code on GitHub]
2. Scan with [VirusTotal.com](https://www.virustotal.com/)
3. Run in a virtual machine or Windows Sandbox first
4. Ask technical questions in our [GitHub Issues](https://github.com/ctsw05/nexus-tv/issues)

We have nothing to hide - all code is open source.

---

## 🆘 Still Having Issues?

### Installation Fails Completely

Try:
1. Run installer as Administrator (right-click → Run as administrator)
2. Disable antivirus temporarily
3. Check you have enough disk space (200MB needed)
4. Ensure Windows 10/11 64-bit

### App Won't Launch After Install

1. Check antivirus didn't quarantine it
2. Add exception to antivirus
3. Reinstall with antivirus disabled
4. Check Windows Event Viewer for errors

### Other Problems

- **Report bugs:** [GitHub Issues]([https://github.com/ctsw05/nexus-tv/issues](https://github.com/ctsw05/nexus-tv-updates/issues))
- **Ask questions:** [GitHub Discussions](https://github.com/ctsw05/nexus-tv/discussions)

---

## ✅ Installation Complete!

Once installed, you can:

1. **Add playlists** - Click "Playlists" → "Add New Playlist"
2. **Set up EPG** - Go to "TV Guide" → "EPG Settings"
3. **Start watching** - Browse channels and enjoy!

**Keyboard Shortcuts:**
- `Space` - Play/Pause
- `F` - Fullscreen
- `Ctrl+F` - Search
- `Esc` - Exit Fullscreen

---

<div align="center">

**Questions? Issues?**

[GitHub Issues](https://github.com/ctsw05/nexus-tv/issues) • [Documentation](https://github.com/ctsw05/nexus-tv/wiki) • [Source Code](https://github.com/ctsw05/nexus-tv)

**Thank you for using Nexus TV!** 📺

# 📺 NEXUS TV - INSTALLATION GUIDE

## Why Does Windows Block This App?

Nexus TV is a **safe, legitimate IPTV player**, but Windows shows security warnings because:

- ✖️ **Not code-signed** - Digital certificates cost $200/year (we're an independent project)
- ✖️ **New application** - Windows doesn't recognize the publisher yet
- ✖️ **Heuristic detection** - Antivirus flags unknown software by default

**This is a FALSE POSITIVE** - the app is completely safe.

---

## 🛡️ What Nexus TV Does NOT Do

The app is safe and does NOT:

❌ Steal your data  
❌ Install viruses or malware  
❌ Access your personal files  
❌ Send information to third parties  
❌ Mine cryptocurrency  
❌ Encrypt your files  
❌ Track your activity  
❌ Install spyware  

**What it DOES do:**
✅ Stream IPTV content you provide  
✅ Check for updates from GitHub (our official repository)  
✅ Store your playlists and preferences locally on your PC  
✅ Run in system tray for quick access  

These are **normal behaviors** for an IPTV player, but antivirus software can't verify this without a digital signature.

---

## 🔍 How to Verify It's Safe

**Option 1: Check VirusTotal**
1. Upload the .exe to [VirusTotal.com](https://www.virustotal.com/)
2. Most antivirus engines will show it's clean
3. Any detections are heuristic false positives, not actual threats

**Option 2: Check the Source Code**
- All code is open source on GitHub
- No hidden or obfuscated code

---

## 📥 Installation Instructions

### Step 1: Download
Download `Nexus-TV-Setup-1.0.1.exe` from:
- [GitHub Releases([https://github.com/ctsw05/nexus-tv-updates/releases/tag/NexusTV-IPTV-PLAYER](https://github.com/ctsw05/nexus-tv-updates/releases/tag/NexusTV-IPTV-PLAYER))) (recommended)
- Official website (if you have one)

### Step 2: Install (Windows Defender)

When you run the installer, Windows will show a warning:

**"Windows protected your PC"**

This is expected. Here's how to proceed:

1. Click **"More info"** on the warning screen
2. Click **"Run anyway"** button
3. Follow the installation wizard
4. Launch Nexus TV from Start Menu or Desktop

**Visual Guide:**
```
┌─────────────────────────────────────┐
│  Windows protected your PC          │
│                                     │
│  Windows Defender SmartScreen       │
│  prevented an unrecognized app...   │
│                                     │
│  [More info]  ← Click here first    │
└─────────────────────────────────────┘

Then:

┌─────────────────────────────────────┐
│  Windows protected your PC          │
│                                     │
│  App: Nexus TV Setup.exe            │
│  Publisher: Unknown publisher       │
│                                     │
│  [Run anyway]  ← Click here         │
└─────────────────────────────────────┘
```

### Step 3: If Using Avast Antivirus

If Avast blocks the installation:

**Option A: Temporarily Allow**
1. Right-click Avast icon in system tray
2. Select **"Avast shields control"**
3. Choose **"Disable for 10 minutes"**
4. Install Nexus TV
5. Re-enable Avast

**Option B: Add Exception**
1. Open Avast
2. Go to **Menu → Settings → Exceptions**
3. Click **"Add Exception"**
4. Browse to `Nexus TV Setup.exe`
5. Click **"Add Exception"**
6. Run installer

**Option C: After Installation**
1. Install with Avast disabled (Option A)
2. Add `C:\Program Files\Nexus TV\` to Avast exceptions
3. Re-enable Avast
4. App will run normally

### Step 4: If Using Other Antivirus

**Norton, McAfee, Bitdefender, etc.:**
1. Temporarily disable antivirus
2. Install Nexus TV
3. Add installation folder to antivirus exceptions:
   - `C:\Program Files\Nexus TV\`
   - `C:\Users\YourName\AppData\Local\nexus-tv\`
4. Re-enable antivirus

---

## ❓ Frequently Asked Questions

### Why isn't the app code-signed?

Code signing certificates cost $200-500 per year and require business verification. As an independent open-source project, we haven't obtained one yet. This doesn't mean the app is unsafe - it just means Windows can't verify the publisher.

### Will you get code signing in the future?

We're considering it, but can't make promises. For now, the app works perfectly without it - you just need to click "Run anyway" once during installation.

### Why does the app need internet access?

Nexus TV needs internet to:
- Stream IPTV content from your playlists
- Download EPG (TV guide) data
- Check for app updates from GitHub

This is normal for any IPTV player.

### Can I use Nexus TV offline?

You need internet to stream content, but the app itself will run offline. You just won't be able to watch anything without an internet connection.

### Does the app phone home or collect data?

**No.** Nexus TV:
- Does NOT send telemetry
- Does NOT track your viewing
- Does NOT collect personal information
- Only connects to: your IPTV streams, EPG servers, and GitHub for updates

Everything is stored locally on your computer.

### What if I still don't trust it?

That's totally fine! Security concerns are valid. Here's what you can do:
1. Review the [source code on GitHub]
2. Scan with [VirusTotal.com](https://www.virustotal.com/)
3. Run in a virtual machine or Windows Sandbox first
4. Ask technical questions in our [GitHub Issues](https://github.com/yourusername/nexus-tv/issues)

We have nothing to hide - all code is open source.

---

## 🆘 Still Having Issues?

### Installation Fails Completely

Try:
1. Run installer as Administrator (right-click → Run as administrator)
2. Disable antivirus temporarily
3. Check you have enough disk space (200MB needed)
4. Ensure Windows 10/11 64-bit

### App Won't Launch After Install

1. Check antivirus didn't quarantine it
2. Add exception to antivirus
3. Reinstall with antivirus disabled
4. Check Windows Event Viewer for errors

### Other Problems

- **Report bugs:** [GitHub Issues](https://github.com/ctsw05/nexus-tv/issues)
- **Ask questions:** [GitHub Discussions](https://github.com/ctsw05/nexus-tv/discussions)

---

## ✅ Installation Complete!

Once installed, you can:

1. **Add playlists** - Click "Playlists" → "Add New Playlist"
2. **Set up EPG** - Go to "TV Guide" → "EPG Settings"
3. **Start watching** - Browse channels and enjoy!

**Keyboard Shortcuts:**
- `Space` - Play/Pause
- `F` - Fullscreen
- `Ctrl+F` - Search
- `Esc` - Exit Fullscreen

---

<div align="center">

**Questions? Issues?**

[GitHub Issues](https://github.com/ctsw05/nexus-tv/issues) • [Documentation](https://github.com/ctsw05/nexus-tv/wiki) • [Source Code](https://github.com/ctsw05/nexus-tv)

**Thank you for using Nexus TV!** 📺
<img width="3840" height="2088" alt="Screenshot 2026-02-07 011245" src="https://github.com/user-attachments/assets/b203e093-9c43-4fbe-ae0b-51f5bf27f17f" />
<img width="3840" height="2088" alt="Screenshot 2026-02-07 013426" src="https://github.com/user-attachments/assets/848fb149-1560-4241-9026-1d013a14f63a" />


</div>

</div>
