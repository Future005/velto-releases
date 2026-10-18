# Velto for Mac

Downloads only. Velto's source code is private and is not in this repository.

**Get Velto:** [velto.bhavishya.io](https://velto.bhavishya.io), or the latest file under
[Releases](https://github.com/Future005/velto-releases/releases/latest).

- Needs macOS 14 or later, on Apple silicon or Intel.
- Runs on your Mac. Your voice and words stay on it.

## First open (beta)

Beta builds are not notarised by Apple yet, so macOS stops the first open with
"Apple could not verify Velto". Click Done, then open System Settings, Privacy & Security,
scroll to Security and click **Open Anyway** next to Velto. Step by step, with a button that
opens the right settings page: [velto.bhavishya.io/install](https://velto.bhavishya.io/install).

## Check the file

Each release has a `Velto.dmg.sha256`. In Terminal:

```
shasum -a 256 ~/Downloads/Velto.dmg
```

The result should match the number in that file.
