# WELCOME ![eclipse logo](logo_with_title.png)

Eclipse is a two-player strategy game where Light and Shadow armies battle on a 10x10 grid.

## Installation

### Windows
1. Download the `.zip` file from the [releases page](https://github.com/vlshields/Eclipse/releases/)
2. Extract the archive to your preferred location
3. Double-click `eclipse.exe` to launch the game

### macOS
1. Download the `.zip` file from the [releases page](https://github.com/vlshields/Eclipse/releases/)
2. Extract the archive
3. Right-click `Eclipse.app` and select "Open"
4. When macOS warns that Eclipse isn't from the App Store, click "Open" to run anyway
   - You only need to do this the first time you launch the game

### Linux / Universal
1. Download `eclipse.love` from the [releases page](https://github.com/vlshields/Eclipse/releases/)
2. Install LÖVE 11.x from [love2d.org](https://love2d.org/) or your package manager
3. Run with: `love eclipse.love`

## Contributing

The best way to contribute is to download and test pre-release versions. While I've built binaries for multiple systems, thorough testing across all operating systems requires community help. Your feedback is invaluable!

### Testing Focus Areas
- Game mechanics and balance
- Online multiplayer functionality
- Platform-specific issues
- Performance on different hardware


## Online Multiplayer

Eclipse features LAN-based multiplayer where one player hosts (always Player 1) and the other joins. The server code is integrated into the game and runs when you select "Host Game".

### Remote Play Setup
For playing over the internet, we recommend establishing a VPN tunnel for security:
- [Tailscale](https://tailscale.com/) (easiest setup)
- [WireGuard](https://www.wireguard.com/) (more control)
- Avoid direct NAT port forwarding when possible

## Bug Reports & Feature Requests

Please check [existing issues](https://github.com/vlshields/Eclipse/issues) before submitting new ones. When reporting bugs, include:
- Your operating system and version
- Steps to reproduce the issue
- Expected vs. actual behavior
- Screenshots or error messages if applicable

The issues tab also shows our development roadmap and current priorities.

## Development Updates

Platform packaging is currently prioritized for Windows and macOS based on user feedback. Linux users should use the universal `.love` file for now. Release timing may vary between platforms as we respond to testing needs.

## Acknowledgements

- **Engine:** Built with [LÖVE](https://love2d.org/)
- **Graphics:** Created using Canva and [Aseprite](https://www.aseprite.org/), with grids rendered via LÖVE's graphics API
- **Audio:** Composed using the [ChucK programming language](https://chuck.stanford.edu/)
- **The Players:** Thank you to everyone who has tested Eclipse, even for just 5 minutes. You make this project possible! ❤️

---

*Copyright (C) 2025 Vince Shields*  
*Licensed under GPL-3.0 - see [LICENSE](LICENSE) file for details*  
*All source code and assets available at https://github.com/vlshields/Eclipse/releases/*
