# ulogd-viz

ulogd-viz is a set of PHP scripts to visualize iptables / UFW logs with Google Chart / Google Maps.

## Install

You'll need the ulogd package and a firewall rule to trigger ulogd.
 iptables -I ufw-before-input  -j ULOG --ulog-nlgroup 1 --ulog-prefix ULOG

 