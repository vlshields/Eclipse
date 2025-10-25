# WELCOME ![eclipse logo](logo_with_title.png)
Eclipse is a two-player strategy game where Light and Shadow armies battle on a 10x10 grid. 

## Contributing

The best way to contribute is to download and test pre-release versions from this repo. I have built the binaries for as many systems as I can, but it is difficult to thoroughly test on all operating systems. Thusly I will rely heavily on the feedback of others. You are absolutely welcome to make suggestions on the source files, but I cannot in good consience suggest or request that. The game.lua file alone is around 2,000 lines and I did not modularize the codebase well.  

### Installing and Testing the game
- **Windows:** Download the zip file and extract. Double click the exe to run the game.
- **MacOS:** Download and extract the zip file. The first time you launch the game you will be told that eclipse is not from the official app store. Follow the instructions in the prompt to override. 
- **Debian:** sudo apt install ./eclipse_xx.yy.zz.deb
- **Archive file:** love eclipse.love
- **AppImage:** Download and make it an executable. Run with ./eclipse.AppImage

### About Online Multiplayer
This feature was designed for playing over LAN (Local Area Network). As such, a player is either the host (which is always player one) or joining the hosts game. It was not designed to run on a separate server (although it is probably possible). The server code (server.lua) is built in to the game and is run when a player selects "Host Game". For remote play over the internet, it is recommended to establish a VPN tunnel using services such as WireGuard or Tailscale rather than exposing ports directly through NAT port forwarding.

**Important:** There is a dependency issue where love.sockets is conflicting with luasockets. What this means is that the host player must have luasockets installed on their system in order for server.lua to run. However, there is an experimental fix for this in pre-release v0.1.2. Please test it! 

### Anouncements

For now I will be focusing on packaging the game for for Windows and MacOS. Linux users are encouraged to use the .love file. This may change for the actual release version, but packaging for several systems is currently too much work. The package builds may not come out at the same time for every pre releasae version because right now there are more people playing/testing the game on MacOS.





## Bug Reports and Feature Requests
Please see the existing issues for a template if you are unsure of how to structure your report/request. If you encounter a bug that is not already listed please provide as much detail as possible about your system and the bug so that I can reproduce it. The issues tab will also give you a sense of the project timeline and what is being worked on currently.

## Acknowledgements 
- Eclipse is built using [Love2d](https://love2d.org/).
- Graphical assets were created using Canva and [Aseprite](https://www.aseprite.org/). The grid is rendered by Love2d's graphics api.
- Audio assets were all created with the [ChucK programming language](https://chuck.stanford.edu/)
- **The Players**: Thats you! Words can't describe how greatful I am if you have played this game, even if for just 5 minutes. You are the best <3
