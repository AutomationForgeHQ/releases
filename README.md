# Automation Forge — releases

Downloadable builds of the Automation Forge plugins for Unreal Engine 5.8, one release per plugin version, packaged per engine version (`<Plugin>-<version>-UE5.8-Win64.zip`, with symbols in a separate zip).

Binaries only. The source of every open plugin lives in that plugin's own repository under this organisation; everything else is closed, and its implementation stays in the private monorepo.

The hub and the `forge` CLI install from here through the manifest published in [`automation-forge`](https://github.com/AutomationForgeHQ/automation-forge). The manifest carries a SHA-256 for every asset and each release carries a `SHA256SUMS.txt`, so a download is verified against what CI built — but neither the manifest nor the binaries are code-signed yet, and Windows machines running Smart App Control may refuse the DLLs until they are.

Nothing is listed on Fab yet. When something is, it will be linked from [kovati.dev](https://kovati.dev).
