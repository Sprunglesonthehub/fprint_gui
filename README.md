# fprint_gui

**fprint_gui** is a lightweight GTK4-based fingerprint management application for Linux. Built for **AcreetionOS**, it provides a clean, user-friendly graphical interface for enrolling and verifying fingerprints using the open-source `libfprint` and `fprintd` stack.

This application **only supports fingerprint readers with open-source firmware and drivers**. No proprietary components or blobs are used or required.

---

## ✨ Features

- Enroll and manage fingerprint data
- Verify fingerprints for login or authentication
- Built with **GTK4** for modern UI and Wayland support
- Integrates with `fprintd` and `libfprint`
- 100% open source and privacy-respecting
- Tailored for AcreetionOS users and philosophy

---

## 📦 Installation (AcreetionOS / Arch-based)

Install via the included **PKGBUILD**:

```bash
git clone https://acreetionos.org/git/fprint_gui.git
cd fprint_gui
makepkg -si
