# 💻 Used Laptop Full Inspection & Buying Guide

A complete guide to inspect and test a used laptop (e.g., Dell Latitude 7420) before buying.

---

## ✅ Pre-Purchase Questions (Ask Seller)
- Why are you selling it?
- Original or refurbished?
- What is the battery backup time?
- Any parts replaced? (SSD, screen, battery)
- Is there any screen issue, keyboard issue, or port not working?
- BIOS/BitLocker password set?
- Windows activated?

---

## 🧰 Tools You'll Need
- Pen drive (bootable Windows or Linux optional)
- Internet connection
- Software:
  - [HWiNFO](https://www.hwinfo.com/) or Speccy – System specs
  - [CrystalDiskInfo](https://crystalmark.info/en/software/crystaldiskinfo/) – SSD health
  - [BatteryInfoView](https://www.nirsoft.net/utils/battery_information_view.html) – Battery wear
  - [Dead Pixel Test](https://deadpixeltest.org/) – Display test
  - Online keyboard tester – https://keyboardtester.com/

---

## 🖼️ Display / Screen Checks

### 1. **Dead/Stuck Pixels**
- Go to [deadpixeltest.org](https://deadpixeltest.org)
- Check Red, Green, Blue, Black, and White backgrounds
- Look for black dots (dead pixels) or always-lit pixels (stuck)

### 2. **Touch Test** (if applicable)
- Use Paint or browser drawing tool
- Draw across the entire screen using multiple fingers

### 3. **Backlight Bleed**
- Open a black screen in a dark room
- Excess light from edges = backlight bleed (minor is okay)

### 4. **Ghosting / Burn-in**
- Show white background
- Check for faint images or shadows of past content

### 5. **Brightness and Color Uniformity**
- Open full white/gray image
- Should be evenly bright without yellow/blue tint or blotches

### 6. **Flickering Test**
- Record screen with your phone camera at 60fps
- Visible flickering = low-quality panel or PWM issue

---

## ⚙️ System & Hardware Info

### System Specs
- Open `HWiNFO` or `System Information`:
  - Check CPU model (e.g., i7-1165G7)
  - Installed RAM size and type (DDR4, LPDDR4x)
  - SSD brand & size
  - GPU type (Intel or Nvidia)

### Performance Test
- Open multiple apps (Browser, File Explorer, Video Player)
- Try Office apps or code editor (e.g., VS Code)
- Play 1080p/4K video and check smoothness

### SSD Health
- Use CrystalDiskInfo:
  - Look for “Good” status, no red/yellow warnings
  - Power-On Hours & Total Writes can indicate age

---

## 🔋 Battery Test
- Use BatteryInfoView or `powercfg /batteryreport` in CMD
- Check:
  - **Design Capacity vs Full Charge Capacity**
  - **Cycle count** (under 500 preferred)
  - Backup time should be at least 1.5–2 hours minimum

---

## 🔊 Keyboard, Audio, and Webcam

### Keyboard
- Use [keyboardtester.com](https://keyboardtester.com/)
- Test all keys (Fn, Esc, Backspace, arrows)

### Touchpad
- Test tap, two-finger scroll, gestures
- Check for jumpy or nonresponsive behavior

### Webcam
- Open Camera app – test photo & video
- Should work clearly in daylight

### Audio
- Play music, increase volume, plug in headphones

---

## 🔌 Ports & Connectivity

- USB Ports: Test with flash drive
- HDMI/DisplayPort: Connect to external monitor
- Type-C: Power delivery or data transfer
- SD Card slot: Insert card and test
- Wi-Fi: Connect to hotspot or router
- Bluetooth: Pair with phone/mouse
- Ethernet (if available): Test wired connection

---

## 🔒 BIOS & OS Check
- Enter BIOS/UEFI – Should not be password protected
- Ensure BitLocker is OFF
- Check if Windows is genuine and activated
  - Settings > System > Activation

---

## ✅ Final Checklist
- [ ] No dead pixels or flickering display
- [ ] Battery backup at least 2 hours
- [ ] SSD health is good (no warnings)
- [ ] All ports working
- [ ] Keyboard & touchpad tested
- [ ] Audio & webcam working
- [ ] No overheating under normal usage
- [ ] BIOS unlocked, Windows activated

---

