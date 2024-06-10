# deluge-piaportplugin

This is a simple plugin for [Deluge](https://www.deluge-torrent.org/) that's meant to be used with [Gluetun](https://github.com/qdm12/gluetun).

Getting VPN port forwarding set up when using containers can be a pain since the port number is dynamic. This plugin automatically updates the incoming port for Deluge based on the current forwarded port.

## Usage

Updated to work with TrueNAS Scale Gluetun. Default location is /tmp/gluetun/forwarded_port

