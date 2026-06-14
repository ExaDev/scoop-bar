# scoop-bar

[Scoop](https://scoop.sh/) bucket for [Beyond All Reason](https://www.beyondallreason.info/)
on Windows, distributing the [bar-lobby](https://github.com/ExaDev/bar-lobby)
client (portable build).

## Install

```powershell
scoop bucket add bar https://github.com/ExaDev/scoop-bar
scoop install bar
```

Upgrade later with `scoop update bar`. The Start Menu shortcut is "Beyond All
Reason".

## Status

`bucket/bar.json` is regenerated automatically on each `ExaDev/bar-lobby`
release by that repo's `update-scoop` job, which pushes here via a scoped SSH
deploy key (this bucket has no workflows of its own).

The build is unsigned, so SmartScreen may warn on first launch.
