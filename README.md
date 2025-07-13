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

## 📥 Download Latest Release

Get pre-built binaries from the [Releases Section](https://github.com/CodeAbhi826/wireguard-android-builder/releases)

[![Latest Release](https://img.shields.io/github/v/release/CodeAbhi826/wireguard-android-builder?label=Latest%20Release&style=for-the-badge)](https://github.com/CodeAbhi826/wireguard-android-builder/releases)

## 🔄 Automatic Updates
- Daily builds at 12:00 UTC
- Auto-detects WireGuard source updates
- New releases published automatically

## 🛠️ How It Works
1. Daily check for WireGuard source updates
2. If updates found, triggers build workflow
3. Builds static ARM64 binaries
4. Creates new GitHub release with binaries

## Source Projects
- [wireguard-tools](https://git.zx2c4.com/wireguard-tools)
- [wireguard-go](https://git.zx2c4.com/wireguard-go)

## License
GPLv2 (wireguard-tools) and MIT (wireguard-go)