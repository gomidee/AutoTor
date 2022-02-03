# AutoTor FOR MAC OS - Gomidee
Install Tor Client on you mac with one click and set duration to change your ip address periodically

Features:
- All traffic is routed through Tor
- No need to constantly change IP Adress'

AutoTor 1.0.3 - Gomidee requires some dependencies
- Homebrew
  - Figlit (to display text)
  - Tor

The Gist:
- This script will verify if you have Homebrew and the required dependencies
- It will locate and rename torrc file
- Enable SOCKS Proxy and configure Server name (127.0.0.1) & port number to use when contacting the proxy server (9050) 
- Custom duration (in seconds) to change tor client ip address (optional)
