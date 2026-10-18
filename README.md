# Godigi 👋

Open-source macOS developer tools, network diagnostics, and MCP integrations.

## Featured Project: [Hopwatch](https://github.com/godigi/hopwatch)

**[Hopwatch](https://github.com/godigi/hopwatch)** ([Website](https://godigi.github.io/hopwatch/) • [Latest Release](https://github.com/godigi/hopwatch/releases/latest)) is the zero-jargon network monitor and diagnostic companion for macOS (SwiftUI menu bar app + Bash CLI).

* 🎯 **Hop Attribution Chain:** Pinpoints whether an internet problem is caused by a local Mac app, Wi-Fi, your router, DNS, bufferbloat, or your ISP (`[Mac] ──► [Router] ──► [ISP]`).
* ⚡ **Live Menu Bar Telemetry:** Real-time gateway and internet RTT, packet loss, and automatic arrival checks on macOS Sonoma (14+) and Sequoia (15+).
* 🔍 **40+ Network Probes:** Bufferbloat (idle vs. loaded RTT), Path MTU black holes, captive portal detection, sticky Wi-Fi APs, DNS hijacking, double-NAT, and local process bandwidth attribution.
* 🛠️ **1-Click Guided Repairs:** Actionable fixes in the GUI and CLI (`hopwatch --repair`) plus 1-click redacted support summaries.

### Quick Install (macOS)

```sh
curl -fsSL https://raw.githubusercontent.com/godigi/hopwatch/main/install-app.sh | bash
```

Or via Homebrew:

```sh
brew tap godigi/hopwatch https://github.com/godigi/hopwatch.git
brew install --cask hopwatch
```

🔗 **Links:**
* GitHub Repository: [https://github.com/godigi/hopwatch](https://github.com/godigi/hopwatch)
* Documentation & Landing Page: [https://godigi.github.io/hopwatch/](https://godigi.github.io/hopwatch/)
* Download macOS DMG: [https://github.com/godigi/hopwatch/releases/latest](https://github.com/godigi/hopwatch/releases/latest)
