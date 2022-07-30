# Cloudflare Warp Scripts

Sometimes Cloudflare Warp will not work because of restrictions set by your ISP or even the government, this repository provides tips, scripts and tools to make it work easier for you.


##WARP Ingress IP
These are the IP addresses that the WARP client will connect to. All traffic from your device to the Cloudflare edge will go through these IP addresses.

IPv4 Range: 162.159.193.0/24
IPv6 Range: 2606:4700:100::/48


##WARP UDP Ports
WARP utilizes UDP for all of its communications. By default, the UDP Port required for WARP is: UDP 2408. WARP can fallback to: UDP 500, UDP 1701, or UDP 4500.


Source: https://developers.cloudflare.com/cloudflare-one/connections/connect-devices/warp/deployment/firewall#udp-ports
