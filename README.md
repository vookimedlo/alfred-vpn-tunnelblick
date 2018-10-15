# alfred-vpn-tunnelblick
[Alfred 3][1] workflow for controlling Tunnelblick VPN connections.


# Installation
1) Have a [Tunnelblick][3] installed and configured.
2) Install [alfred-vpn-tunnelblick][2] workflow.
3) All further workflow updates are handled automatically.

## Usage
In Alfred, type `vpn`. This initiates a scanning of actual VPN state.
Then, you could connect to or disconnect from your VPN servers.

![alfred-vpn-tunnelblick-submenu-connect-disconnect](doc/images/alfred-vpn-connect-disconnect.png?raw=true "")

In case of multiple VPN servers availibility you can use either the `Connect to all` or `Disconnect from all` command. 

![alfred-vpn-tunnelblick-submenu-connect-all](doc/images/alfred-vpn-connect-all.png?raw=true "")

## Configuration
Workflow is configurable by workflow variables.

Optional settings:
- `keyword` contains the main workflow keyword, which is used to start this workflow. By default, it's set to `vpn`.

![alfred-vpn-tunnelblick-workflow-variables](doc/images/alfred-vpn-workflow-variables.png?raw=true "")

[1]: https://www.alfredapp.com/
[2]: https://github.com/vookimedlo/alfred-vpn-tunnelblick/releases/latest
[3]: https://tunnelblick.net/
