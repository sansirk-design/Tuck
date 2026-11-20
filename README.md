# Tuck

**The notch on your Mac, put to work.** Music, colors and files, one click away.

Tuck turns the notch into a small island that opens when you click it and tucks away when you leave. On screens without a notch, like an external monitor, it shows a small circle at the top of the screen that opens like a droplet, with every feature intact.

**[Download Tuck for Mac](https://github.com/sansirk-design/Tuck/releases/latest/download/Tuck.dmg)** · Version 0.1.0 · 1.2 MB · Apple Silicon, macOS 14 or later

## What it does

- **Music with live lyrics.** Follows whatever is playing on your Mac (the same source Control Center uses). Synced lyrics, scrubbing, ±10 seconds, loop and volume.
- **Color picker.** Pick any pixel on screen with ⌃⌥C. HEX, RGB, HSL and OKLCH, copied in one click. Keeps your last 12 colors.
- **Files to PDF.** Drop images and documents onto the notch, keep adding, then make one PDF on your Desktop.
- **Remove background, convert, AirDrop.** Drop a photo to cut out the subject on device, convert between JPG, PNG, HEIC, AVIF and TIFF, or AirDrop it.
- **Every screen gets an island.** The notch on a MacBook, a small circle on any other display.

Hovering only peeks; a click opens. Tuck idles at about 14 MB of memory and 0% CPU.

## Install

1. Download **Tuck.dmg** and open it.
2. Drag **Tuck** into **Applications**.
3. Open **Tuck** from Applications.

Tuck has no Dock icon: click the notch to open it, scroll inside it to switch features, right-click it for settings.

### Seeing a message instead? Find yours below.

Tuck is free and isn't signed through a paid Apple developer account, so macOS may block it the first time. These steps are only needed once.

<details>
<summary><b>"Apple could not verify "Tuck" is free of malware…"</b></summary>

1. Click **Done** (not *Move to Trash*).
2. Open **System Settings → Privacy & Security**.
3. Scroll down to **Security**. Next to *"Tuck" was blocked to protect your Mac*, click **Open Anyway**.
4. Enter your Mac password, then click **Open Anyway** again.
</details>

<details>
<summary><b>"Tuck is damaged and can't be opened."</b></summary>

Tuck isn't damaged; this is the same block with scarier wording.

1. Click **Cancel** (not *Move to Trash*).
2. Open **Terminal** (Applications → Utilities → Terminal).
3. Paste this, press **Return**, and Tuck opens:

```sh
xattr -dr com.apple.quarantine /Applications/Tuck.app && open /Applications/Tuck.app
```
</details>

<details>
<summary><b>"Tuck can't be opened because it is from an unidentified developer"</b></summary>

1. Click **OK**.
2. In Applications, **right-click Tuck → Open**, then click **Open**.
</details>

<details>
<summary><b>"…isn't supported on this type of Mac"</b></summary>

Tuck needs an Apple Silicon Mac (M1 or newer). It doesn't run on Intel Macs.
</details>

<details>
<summary><b>Nothing seems to happen</b></summary>

Tuck lives in the notch, not the Dock. Move your mouse to the notch (or the small dot at the top of an external screen) and click.
</details>

## Permissions Tuck asks for

On first launch Tuck asks for access to three folders, once, and says why:

- **Downloads:** to show files AirDropped to you.
- **Desktop:** to save the PDFs you make.
- **Documents:** to save converted images and cut-outs next to your files.

The only thing Tuck sends over the internet is the song's title, artist, album and length, to look up synced lyrics on [LRCLIB](https://lrclib.net). You can turn that off in Settings.

## Uninstall

Quit Tuck (right-click the notch → Settings → Quit Tuck), then drag it from Applications to the Trash.

---

Made by Sanjan Sirkar · [Portfolio](https://sansirk-design.github.io/#case-tuck)
