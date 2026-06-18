# RPCS3 — drDOOM69GAMING Build

Custom-tuned fork built for Ryzen 5700X3D with `-march=native` (znver3),
LLVM 18, and AMD RX 6800–friendly defaults. Packaged as a portable AppImage.

**Changes from upstream:**
- `-march=znver3 -mtune=znver3` / `USE_NATIVE_INSTRUCTIONS=ON`
- Branded version string: "drDOOM69GAMING Build"
- Developer settings tab always visible
- PPU & shader compilation hints default to off
- "Use Re-BAR memory for GPU uploads" setting removed
- Custom GitHub & YouTube buttons in About dialog

Built from commit `c0598f61` of [RPCS3/rpcs3](https://github.com/RPCS3/rpcs3).

---

[![GitHub Actions](https://img.shields.io/github/actions/workflow/status/RPCS3/rpcs3/rpcs3.yml?branch=master&logo=github&label=Actions)](https://github.com/RPCS3/rpcs3/actions/workflows/rpcs3.yml)
[![RPCS3 Discord Server](https://img.shields.io/discord/272035812277878785?color=5865F2&label=RPCS3%20Discord&logo=discord&logoColor=white)](https://discord.gg/rpcs3)

The world's first free and open-source PlayStation 3 emulator/debugger, written in C++ for Windows, Linux, macOS and FreeBSD.

You can find some basic information on our [**website**](https://rpcs3.net/). Game info is being populated on the [**Wiki**](https://wiki.rpcs3.net/).
For discussion about this emulator, PS3 emulation, and game compatibility reports, please visit our [**forums**](https://forums.rpcs3.net) and our [**Discord server**](https://discord.gg/RPCS3).

[**Support Lead Developers Nekotekina and kd-11 on Patreon**](https://www.patreon.com/Nekotekina)

## Contributing

If you want to help the project but do not code, the best way to help out is to test games and make bug reports. See:
* [Quickstart](https://rpcs3.net/quickstart)


## License

Most files are licensed under the terms of GNU GPL-2.0-only License; see LICENSE file for details. Some files may be licensed differently; check appropriate file headers for details.
