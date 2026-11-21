# Scheduler{+}

A desktop music scheduler for radio. Scheduler{+} builds the day's music log from your library,
hour templates and rules, explains every choice it makes, and lets you edit the result by hand.
It works offline and keeps each station in a single file.

This repository holds the published builds. Download them from
[Releases](https://github.com/airadiolabs/schedulerplus-releases/releases).

## Downloads

| System | File |
|---|---|
| Linux, x86_64 | `schedulerplus-<version>-linux-x86_64.deb`, `.rpm` or `.AppImage` |
| Linux, ARM64 | `schedulerplus-<version>-linux-arm64.deb`, `.rpm` or `.AppImage` |
| macOS 11 or later, Apple silicon and Intel | `schedulerplus-<version>-macos-universal.dmg` |
| Windows, x86_64 | `schedulerplus-<version>-windows-x86_64-setup.exe` or `.msi` |

`SHA256SUMS.txt` lists the checksums.

## First launch

The builds are not code-signed yet (the macOS one is not notarized either).

- **Linux:** install the `.deb` (Debian, Ubuntu) or `.rpm` (Fedora, openSUSE), or make the
  `.AppImage` executable and run it. Scheduled tasks need the `.deb` or `.rpm`, which put the
  `schedulerplus` command in a fixed place.
- **macOS:** open the `.dmg` and drag Scheduler{+} Native to Applications. The first time, macOS
  refuses to open it: open **System Settings** → **Privacy & Security**, and choose
  **Open Anyway** next to the message about Scheduler{+} Native. It opens normally after that.
  The macOS build is the new native interface, a preview: it works on the same station files.
- **Windows:** run the setup program. If SmartScreen appears, choose **More info** →
  **Run anyway**.

New stations are saved in `Documents/SchedulerPlus/Stations`.

## Status

Early test builds: for trying out, not yet for running a station on air. Back up your stations.
