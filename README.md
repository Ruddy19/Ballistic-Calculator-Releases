# Ballistic Calculator — Releases

Official release mirror for **Ballistic Calculator**, the offline long-range
ballistics calculator for Android.

<p align="center">
  <img src="icon.png" width="260" alt="Ballistic Calculator app icon">
</p>

## Download

The newest version is always the **top entry on the [Releases page](../../releases)** —
open that page on your Android phone and tap the `.apk` to install. Every version
keeps its own release notes there.

For a quick overview of the app — what it does, how to install it and the licence
terms — see the **[Ballistic Calculator site](https://ruddy19.github.io/Ballistic-Calculator-Releases/)**.

Install: download the APK on your Android device and open it. The first time,
Android asks you to allow installing apps from this source — tap **Settings** on
that prompt, switch on **Allow from this source**, then go back and tap **Install**.

> If Google Play Protect shows an "App scan recommended" step, let the scan finish
> before retrying — a timed-out scan can report "App not installed".

**Which file?** Each release carries two APKs:
`Ballistic-Calculator-<version>.apk` for 64-bit ARM phones — essentially every phone
sold since 2016 — and `Ballistic-Calculator-<version>-universal.apk`, which adds the
older 32-bit ARM build. Install the first one; if Android refuses it, the universal
APK is the one for that device.

## What it does

- **Trajectory table** from 50 m to 1000 m: drop, windage, MOA, kinetic energy,
  time of flight and scope clicks for your own click value.
- **Wind matrix** — drift and holds across 2–20 m/s crosswinds, in cm, MOA or clicks.
- **G1 point-mass solver** with zero range selected from presets or any distance.
- **Ammunition lookup** over a bundled library of published factory loads, component
  bullets and reference starting loads, searchable by cartridge.
- **Caliber catalogue** of 150+ rifle cartridges, plus any custom caliber you add.
- **Current weather** from MET Norway — temperature, station pressure and wind filled
  straight into the environment inputs.
- **Offline everywhere else.** Setups, custom calibers and preferences are saved on
  the device; only the weather tab needs a connection.

## Earlier versions

Every build is listed on the [Releases page](../../releases) with its own APK and
notes. Once there are earlier builds, the five most recent will be tabled here.

## Updates

Each release installs over the top and keeps your saved setups, custom calibers and
preferences. There is no separate updater to install.

## Licensing

Ballistic Calculator is **commercial software, licensed and not sold**. The
end user licence terms are in [EULA.md](EULA.md) and are also shown in the app on
first launch.

Bundled open-source packages remain under their own licences; the app lists every
one of them, with its verbatim licence text, under **Privacy → Third-party licences**.

## Privacy

See [PRIVACY.md](PRIVACY.md). In short: no account, no analytics, no advertising.
Inputs and custom calibers stay on the device. The only network request is the
weather tab asking MET Norway for conditions at your approximate location, and only
when you open that tab.

## Source

The application source is maintained in a **private** repository. This mirror is the
public distribution channel and holds release artifacts only.
