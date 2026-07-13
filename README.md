# SelfishNet

Windows freeware for monitoring and controlling local network bandwidth usage. Originally released by Creadev.net (2007). This package is the v0.2 beta Vista/XP build.

> **Note:** Use only on networks you own or have permission to manage. Misuse may violate network policies or law.

## Layout

```
bin/                  Application and required libraries
  SelfishNet.exe      Main program (formerly SelfishNetv0.2-beta_vista.exe)
  *.dll, npf.sys      WinPcap / UI dependencies
docs/
  help.html           Licenses, credits, and support contacts
  release-notes.txt   Changelog
LICENSE.txt           Full SelfishNet and third-party license text
README.md             This file
```

## Requirements

- Windows XP or Windows Vista (this build is not for Windows Server 2003)
- Administrator rights recommended for packet capture

## How to run

1. Open the `bin` folder.
2. Run `SelfishNet.exe`.
3. Keep the DLLs and `npf.sys` beside the executable; they are required at runtime.

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
