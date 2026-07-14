# SelfishNet

Windows freeware for monitoring and controlling local network bandwidth usage. Originally released by Creadev.net (2007). This package is the v0.2 beta Vista/XP build.

> **Note:** Use only on networks you own or have permission to manage. Misuse may violate network policies or law.
> **Note:** I did not create this program, I am only posting it here as a way to preserve it.
## Layout

```
bin/                  Application and required libraries
  SelfishNet.exe      Main program (formerly SelfishNetv0.2-beta_vista.exe)
  *.dll, npf.sys      WinPcap / UI dependencies
deps/
  WinPcap_4_1_3.exe   Required WinPcap 4.1.3 installer
docs/
  help.html           Licenses, credits, and support contacts
  release-notes.txt   Changelog
LICENSE.txt           Full SelfishNet and third-party license text
README.md             This file
```

## Requirements

- Windows XP or Windows Vista (this build is not for Windows Server 2003)
- Administrator rights recommended for packet capture
- **[WinPcap 4.1.3](deps/WinPcap_4_1_3.exe)** (`WinPcap_4_1_3.exe`) — install this before running SelfishNet

You can also download WinPcap 4.1.3 from the official site: https://www.winpcap.org/install/

## How to run

1. Install WinPcap from [`deps/WinPcap_4_1_3.exe`](deps/WinPcap_4_1_3.exe) (reboot if the installer asks).
2. Open the `bin` folder.
3. Run `SelfishNet.exe`.
4. Keep the DLLs and `npf.sys` beside the executable; they are required at runtime.

## Credits

- **Author:** Benjamin Lassort
- **Project manager:** Clement Chazarra
- **Publisher:** [Creadev.net](http://www.creadev.net/)
- **Packet capture:** [WinPcap](http://www.winpcap.org/)
- **Icons:** David Vignoni (Nuvola / LGPL)
- **TreeGridView:** Mark Rideout

Tutorial previously mirrored at TheLacunaBlog: http://www.thelacunablog.com/?p=7189

## License

SelfishNet is distributed as freeware. See [LICENSE.txt](LICENSE.txt) and [docs/help.html](docs/help.html) for SelfishNet terms and included WinPcap notices.
