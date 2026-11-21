# UniVex Releases

Downloads for **UniVex Hub** and the **UniVex Engine**.

UniVex Hub is the launcher for UniVex. It creates and opens your projects, and it downloads and
manages the engine versions they use. The engine itself is installed from inside the Hub.

## Get UniVex Hub

Open the [Releases](../../releases) page and download the installer for your system from the
newest `hub-v…` release:

| System  | File                                   |
| ------- | -------------------------------------- |
| Windows | `UniVexHubSetup-<version>-windows.exe` |
| Linux   | `UniVexHubSetup-<version>-linux`       |

### Windows

Run `UniVexHubSetup-<version>-windows.exe`, choose where to install, and finish the setup. UniVex Hub
is added to the Start menu, and `.uvproject` files open with it.

### Linux

```bash
chmod +x UniVexHubSetup-<version>-linux
./UniVexHubSetup-<version>-linux
```

Choose where to install and finish the setup. UniVex Hub is added to your applications menu, and
`.uvproject` files open with it.

### Removing UniVex Hub

On Windows, remove it from **Settings → Apps**. Removing the Hub keeps your projects, your project
list and the engines you downloaded.

## Get the engine

Start UniVex Hub and open the **Engines** page. It lists the published engine versions:

- **Stable**: releases tagged `v<version>`.
- **Beta**: prereleases tagged `v<version>-beta`.

Pick a version and download it. The Hub checks every package against its published SHA-256 checksum
before installing it. New projects can then be created for any installed version.

The `univex-engine-…` packages on the Releases page are there for the Hub to fetch; you do not need
to download them yourself.

## Release tags

| Tag              | Contains                                                          |
| ---------------- | ----------------------------------------------------------------- |
| `v<version>`     | Engine packages for Linux and Windows, each with a `.sha256` file |
| `hub-v<version>` | UniVex Hub installers for Linux and Windows                       |

---

© 2026 UniVex Studios. All rights reserved.
