# Eclipse   ![eclipse logo](eclipse_logo.png)
Eclipse is a two-player strategy game where Light and Shadow armies battle on a 10x10 grid. 

## Contributing

The best way to contribute is to download and test pre-release versions from this repo. I have built the binaries for as many systems as I can, but it is difficult to thoroughly test on all operating systems. Thusly I will rely heavily on the feedback of others. You are absolutely welcome to make suggestions on the source files, but I cannot in good consience suggest or request that. The game.lua file alone is around 2,000 lines and I did not modularize the codebase well.  

### Installing and Testing the game
- Windows: Download and run the executable
- MacOS: Download and extract the zip file. You will need to allow the game to run by forcing it your privacy/security settings (first run only)
- Debian: sudo apt install ./eclipse_xx.yy.zz.deb
- Archive file: love eclipse.love

### About Online Multiplayer
This feature was designed for playing over LAN (Local Area Network). As such, a player is either the host (which is always player one) or joining the hosts game. It was not designed to run on a separate server (although it is probably possible). The server code (server.lua) is built in to the game and is run when a player selects "Host Game". For remote play over the internet, it is recommended to establish a VPN tunnel using services such as WireGuard or Tailscale rather than exposing ports directly through NAT port forwarding.

**Important:** An installation of the Lua Programming language is required to host a multiplayer game (the joining player does not need a lua installation). I am sorry for this inconvenience will work to fix this. However, Lua is very minimal and very easy to [install](https://www.lua.org/ftp/#source). The server is compatable with Lua5.1+. 

Lua is also available in many package managers:



## Bug Reports and Feature Requests
Please see the existing issues for a template if you are unsure of how to structure your report/request. If you encounter a bug that is not already listed please provide as much detail as possible about your system and the bug so that I can reproduce it. The issues tab will also give you a sense of the project timeline and what is being worked on currently.

## Acknowledgements 
- Eclipse is built using [Love2d](https://love2d.org/).
- Graphical assets were created using Canva and [Aseprite](https://www.aseprite.org/). The grid is rendered by Love2d's graphics api.
- Audio assets were all created with the [ChucK programming language](https://chuck.stanford.edu/)
- **The Players**: Thats you! Words can't describe how greatful I am if you have played this game, even if for just 5 minutes. You are the best <3
