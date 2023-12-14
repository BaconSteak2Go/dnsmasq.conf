#Setting wireless interface
interface=wlan0

#Setting IP Range for users
dhcp-range=192.168.1.2,192.168.1.250,12h

#Setting gateway IP Address
dhcp-option=3,192.168.1.1

#Setting DNS Server Address
dhcp-option=6,192.168.1.1

#dnsmasq is designed to provide DNS and optionally DHCP for a small network.
#dnsmasq caches DNS records which reduces load / improves performance
