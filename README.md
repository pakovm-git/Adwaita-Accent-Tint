# Adwaita-Accent-Tint
A lightweight, native-feeling CSS theme for GNOME 48+ (GTK4/Libadwaita) that subtly blends your system accent color into the application backgrounds.

This theme uses GTK's `mix()` function against the **official Libadwaita base hex codes**. The result is a 7.5% tint that preserves all native shadows, card depths, and high-contrast elements.

## Installation

### 1. Apply to Native Apps
Copy the CSS file into your local GTK4 config directory:

1. Open or create `~/.config/gtk-4.0/gtk.css`.
2. Paste the contents of the `gtk.css` file from this repository.
3. Fully close and reopen any GTK4 app (like Settings or Files) to see the changes.

### 2. Apply to Flatpak Apps
Because Flatpak applications run in an isolated sandbox, they cannot see your custom CSS by default. You need to grant them read-only access to your config folder.

Run this command in your terminal:
```bash
flatpak override --user --filesystem=xdg-config/gtk-4.0:ro


## Donate
Send some Bitcoin over Lightning to: pakovm@getalby.com


<p align="center">
<img width="449" height="449" alt="lnqrsmall" src="https://github.com/user-attachments/assets/50a49464-b88f-4c17-9f2a-48d8ba2e9f72" />
</p>
