# Arrumi

A small desktop companion for your Mac: a dog or cat that lives at the edge of your screen while you take notes, keep things organized and focus.

<!-- Screenshot: add docs/screenshot.png (under ~1 MB) showing the pet at the screen edge with the panel open, then replace this comment with:
![Arrumi on the edge of a Mac screen, with the notes panel open](docs/screenshot.png)
-->

## Download

[Download Arrumi 0.6.0 beta 2](https://github.com/danikovalyov/arrumi/releases/tag/v0.6.0-beta.2)

Open a release and choose `Arrumi-…-macOS-arm64.zip` under **Assets**. GitHub's automatic **Source code** archives contain this repository's documentation, not the app. `SHA256SUMS.txt` is provided to verify the app download.

**Requirements:** Apple Silicon (M1 or newer), macOS 13 or newer.

This is an early testing build. It is not Developer ID signed or notarized, so macOS will warn you the first time you open it. The steps below explain how to get past that. The source code is maintained in a separate private repository.

## What it includes

- Eighteen dog and cat breeds.
- Notes, clickable links, checklists and collections.
- Focus sessions and a countdown beside your pet.
- Adjustable size, opacity, screen edge and interface color.
- Spanish and English. Notes and settings are stored locally.

## Install

Unzip the download and move `Arrumi.app` to Applications. Do not replace an existing version without keeping a copy.

## First time opening Arrumi

Because this build isn't notarized by Apple, macOS blocks it the first time. You only need to do this once.

**macOS 15 Sequoia and later**

1. Open `Arrumi.app` from Applications. macOS will say it can't verify the app.
2. Dismiss the warning (click **Done** or **OK**, not **Move to Trash**).
3. Go to **System Settings > Privacy & Security**.
4. Scroll down to the **Security** section. You'll see a message about Arrumi being blocked.
5. Click **Open Anyway**, then confirm with **Open Anyway** again and enter your password if asked.

**macOS 13 Ventura and macOS 14 Sonoma**

1. In Finder, right-click (or Control-click) `Arrumi.app` in Applications.
2. Choose **Open**.
3. Click **Open** in the dialog that appears.

**Optional: using Terminal**

If you're comfortable with Terminal, you can remove the quarantine flag instead:

```sh
xattr -dr com.apple.quarantine /Applications/Arrumi.app
```

After that, Arrumi opens normally. Look for it at the edge of your screen and in the menu bar.

## Support

[Report an issue](https://github.com/danikovalyov/arrumi/issues) with your macOS version, Mac processor, what happened and steps to reproduce it. Avoid attaching private notes or personal links.

Made by [Daniel Kovalyov](https://danikovalyov.com) · [GitHub](https://github.com/danikovalyov)
