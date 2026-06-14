# scoop-bar

[Scoop](https://scoop.sh/) bucket for [Beyond All Reason](https://www.beyondallreason.info/)
on Windows, distributing the [bar-lobby](https://github.com/ExaDev/bar-lobby)
client (portable build).

## Install

```powershell
scoop bucket add bar https://github.com/ExaDev/scoop-bar
scoop install bar-lobby
```

## Status

`bucket/bar-lobby.json` is regenerated automatically on each `ExaDev/bar-lobby`
release by that repo's `update-scoop` job (which pushes here via a scoped SSH
deploy key — this bucket has no workflows of its own). The scaffold values become
real once bar-lobby publishes its first Windows `.zip` artifact.

The build is unsigned, so SmartScreen may warn on first launch.
