# Hackdog Releases

Public binary release repository for Hackdog applications. Application source code is maintained separately; installers and update manifests are attached to GitHub Releases.

## Applications and tag namespaces

| Application | Tag namespace | Downloads / source |
| --- | --- | --- |
| Phooto Studio (PhotoStudio) | `phootoeditor-vX.Y.Z` | [Releases](https://github.com/hackdog33456/HackdogRelease/releases?q=phootoeditor) · [Source](https://github.com/hackdog33456/PhotoStudio) |
| RelayDesk | `relaydesk-vX.Y.Z` | [Releases](https://github.com/hackdog33456/HackdogRelease/releases?q=relaydesk) |
| TokenMonitor | `tokenmonitor-vX.Y.Z` | [Releases](https://github.com/hackdog33456/HackdogRelease/releases?q=tokenmonitor) |

## Phooto Studio 0.36.0

PhotoStudio now contains the original PhootoEditor source and Git history. Version 0.36.0 packages the latest ICC engine, document rendering and image/photo/AI working-pixel integration. Public ICC editing and several ICC interchange operations remain restricted.

- [Release notes](photostudio/0.36.0.md)
- [Download 0.36.0 installer and update assets](https://github.com/hackdog33456/HackdogRelease/releases/tag/phootoeditor-v0.36.0) (published 2026-09-29)
- Windows x64 installer: `PhootoEditor-0.36.0-win-x64.exe`
- Update assets: installer `.blockmap`, `latest.yml`, and `SHA256SUMS.txt`
- Native document format: v19; catalog: v6. Preserve original documents before upgrading; older versions cannot read the new format.
- Windows installer is not Authenticode signed. See each release's notes for its signing and validation status.

This is a multi-product repository. Updaters must filter their own tag namespace; the repository-wide Latest label is not a product-specific update feed. Phooto Studio keeps its existing application ID, data location, installer naming and `phootoeditor-v` namespace.
