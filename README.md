# WireGuard Android ARM64 Builder

[![Build Status](https://github.com/yourusername/wireguard-android-builder/actions/workflows/build.yml/badge.svg)](https://github.com/yourusername/wireguard-android-builder/actions)

Automated builds of WireGuard tools for rooted Android devices (ARM64). Provides always-updated binaries without manual compilation.

## Features
- Daily automatic builds
- ARM64 optimized static binaries
- Userspace implementation (no kernel dependencies)
- Small footprint (~5MB total)
- Works on any rooted Android device

## Download Binaries
1. Go to [Actions tab](https://github.com/yourusername/wireguard-android-builder/actions)
2. Select latest successful workflow run
3. Download `wireguard-android-binaries` artifact

## Included Files
| File | Purpose |
|------|---------|
| `wg` | Configuration tool |
| `wg-quick` | Connection manager |
| `wireguard-go` | Userspace implementation |
| `build-info.txt` | Build timestamp |



## Build Triggers
- Automatic daily builds
- Manual trigger via GitHub UI
- Source code updates (via repository_dispatch)
- Push to main branch

## Source Projects
- [wireguard-tools](https://git.zx2c4.com/wireguard-tools)
- [wireguard-go](https://git.zx2c4.com/wireguard-go)

## License
GPLv2 (wireguard-tools) and MIT (wireguard-go)