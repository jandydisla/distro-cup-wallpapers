# ☕ Distro Coffee

> **Brew your desktop with animated, Linux-themed coffee wallpapers.**

Bring some warmth to your workstation. **Distro Coffee** is a curated collection of high-quality, animated (and static) wallpapers featuring cozy cups of coffee styled around your favorite Linux distributions. Whether you rock Arch, Debian, Fedora, or CachyOS, we have a fresh pot brewing for you.

---

## 🎨 Preview

<div align="center">
  <img src="https://via.placeholder.com/800x450.png?text=Distro+Coffee+Preview" alt="Distro Coffee Showcase" width="100%" />
</div>

> *Live wallpapers work seamlessly with **KDE Plasma (Smart Video Wallpaper)**, **Hyprland (mpvpaper / swww)**, **Niri**, **Komorebi**, and **Wallpaper Engine**.*

---

## ☕ Featured Blends (Distros Included)

| Blend | Theme Description | Format |
| :--- | :--- | :--- |
| 🏹 **Arch Roast** | Minimalist dark roast with glowing cyan steam. | `.mp4` / `.webp` / `.png` |
| 🌀 **Debian Espresso** | Deep red swirl latte art served in a classic ceramic mug. | `.mp4` / `.webp` / `.png` |
| 🎩 **Fedora Cappuccino** | Smooth blue foam layers with clean, modern aesthetics. | `.mp4` / `.webp` / `.png` |
| ⚡ **CachyOS Cold Brew** | High-performance, ultra-smooth animated dark aesthetics. | `.mp4` / `.jpg` |
| 🟢 **Mint Matcha** | Relaxing, soft green tones for cozy workspace setups. | `.mp4` / `.png` |
| 🍊 **Ubuntu Steam** | Warm aubergine and vibrant orange roast vibes. | `.mp4` / `.png` |

---

## 🚀 Quick Setup

### 🐧 Linux (Hyprland / Wayland via `mpvpaper`)

```bash
# Clone the repository
git clone [https://github.com/your-username/distro-coffee.git](https://github.com/your-username/distro-coffee.git)
cd distro-coffee

# Run a video wallpaper on your output (e.g., eDP-1)
mpvpaper -o "no-audio loop" eDP-1 wallpapers/arch/arch-roast-4k.mp4
