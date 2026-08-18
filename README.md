# LoreMonkey downloads

**[Download LoreMonkey for Windows](../../releases/latest)**

An AI copilot that listens to your TTRPG session and hands you in-character
suggestions at the right moment. Audio and transcription run entirely on your
own machine, so nothing you say at the table leaves it.

## Installing

1. Download `LoreMonkey_x.y.z_x64-setup.exe` from the
   [latest release](../../releases/latest).
2. Run it. Windows will warn that the publisher is unverified. Choose
   **More info**, then **Run anyway**. The app is not code-signed yet; a
   certificate is on the roadmap.
3. Choose whether to install for everyone or just yourself. Either is fine.
   Installing for everyone asks for admin rights, both at install time and
   when updating.
4. Launch LoreMonkey and sign in.

Updates are automatic. The app checks on launch, shows you what changed, and
installs on your say-so. You can also check whenever you like from
**Account**, under **App version**.

## Requirements

- Windows 10 or 11, 64-bit
- About 300 MB for the app itself
- Plus room for the speech model it downloads the first time you use it,
  between 150 MB and 3 GB depending on your hardware
- An NVIDIA graphics card is optional. With one, LoreMonkey offers a one-off
  1.3 GB download that lets it run its most accurate speech model in realtime

Your campaigns, settings and sign-in live in `%APPDATA%\LoreMonkey` and are
never touched by an update.

## Something not working?

The app writes what it is doing to
`%APPDATA%\LoreMonkey\loremonkey-backend.log`. If LoreMonkey will not start or
will not sign in, that file usually says why in one line, and it is the
quickest thing to send.

## This repository

Downloads only. The source lives in a private repository; there is nothing here
but release binaries and the update manifest.
