# scoop-windows-screen-manager

Scoop bucket for [wsm](https://github.com/OsirisFrik/windows-screen-manager) — a CLI tool to save and restore monitor configurations on Windows.

## Add this bucket

```bash
scoop bucket add wsm https://github.com/OsirisFrik/scoop-windows-screen-manager
```

## Install

```bash
scoop install wsm
```

## Update

```bash
scoop update wsm
```

## Uninstall

```bash
scoop uninstall wsm
```

## Usage

```bash
wsm save                  # save current monitor config to config.json
wsm save my-setup.json    # save to a custom file
wsm load config.json      # restore a saved configuration
```

For full documentation see the [main repository](https://github.com/OsirisFrik/windows-screen-manager).
