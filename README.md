# ARK-OS Software Development Kit (SDK)

## Overview

The `sdk/` repository contains public headers, Swift interface definitions, toolchain configurations, and API declarations required to develop applications and system extensions targeting ARK-OS.

---

## Intended Contents and Roadmap

As the userspace runtime and libraries mature, the SDK will provide:
- **Module Interfaces:** Public Swift module definitions for `libark` and system services.
- **C ABI Bindings:** Stable C header files exposing the kernel and platform runtime contracts.
- **Toolchain Profiles:** Target specifications and SDK manifests for cross-compiling Swift and native code for ARK-OS targets from Linux or macOS developer hosts.
- **Sysroot Blueprints:** Standardized header and library sysroot staging recipes.

---

## Status

- **Implementation Status:** Early Design / Planned.
- The SDK interfaces are populated as core library boundaries in `components/libraries/libark` and service contracts in `components/services` reach API stability.

---

## License

This repository is licensed under the Apache License, Version 2.0. See [LICENSE](file:///home/aarav/repo/arkos/sdk/LICENSE) for the full license text.
