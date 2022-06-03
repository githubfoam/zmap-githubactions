# zmap-githubactions
[![kali-tools-top10 with zmap CI workflow](https://github.com/githubfoam/zmap-githubactions/actions/workflows/kali-tools-top10-wf.yml/badge.svg)](https://github.com/githubfoam/zmap-githubactions/actions/workflows/kali-tools-top10-wf.yml)  
[![zmap CI workflow](https://github.com/githubfoam/zmap-githubactions/actions/workflows/zmap-wf.yml/badge.svg)](https://github.com/githubfoam/zmap-githubactions/actions/workflows/zmap-wf.yml)  


[![Docker Automated build](https://img.shields.io/docker/automated/dockerfoam/onos.svg?style=plastic)](https://hub.docker.com/r/dockerfoam/zmap-fedora/)  
[![Docker Pulls](https://img.shields.io/docker/pulls/dockerfoam/onos.svg?style=plastic)](https://hub.docker.com/r/dockerfoam/zmap-fedora/)    
[![Docker Stars](https://img.shields.io/docker/stars/dockerfoam/onos.svg?style=plastic)](https://hub.docker.com/r/dockerfoam/zmap-fedora/)  
~~~~
https://github.com/zmap/zmap
 
docker run --rm --net=host ubuntu/zmap:latest zmap --list-probe-modules  
tcp_synscan
tcp_synackscan
icmp_echoscan
icmp_echo_time
udp
ntp
upnp
dns
bacnet
~~~~
~~~~
# IPv6 support

+ docker run --rm --net=host ubuntu-1604/zmap-ipv6:latest zmap --list-probe-modules
tcp_synscan
tcp_synackscan
icmp_echoscan
icmp_echo_time
udp
ntp
upnp
dns
bacnet
tcp_synopt
ipv6_tcp_synscan
ipv6_tcp_synopt
ipv6_udp
ipv6_dns
icmp6_echoscan
quic_initial
ipv6_quic_initial

 + docker run --rm --net=host ubuntu-1804/zmap-ipv6:latest zmap --list-probe-modules
tcp_synscan
tcp_synackscan
icmp_echoscan
icmp_echo_time
udp
ntp
upnp
dns
bacnet
tcp_synopt
ipv6_tcp_synscan
ipv6_tcp_synopt
ipv6_udp
ipv6_dns
icmp6_echoscan
quic_initial
ipv6_quic_initial


docker run --rm --net=host alpine/zmap-ipv6:latest zmap --list-probe-modules 
tcp_synscan
tcp_synackscan
icmp_echoscan
icmp_echo_time
udp
ntp
upnp
dns
bacnet
tcp_synopt
ipv6_tcp_synscan
ipv6_tcp_synopt
ipv6_udp
ipv6_dns
icmp6_echoscan
quic_initial
ipv6_quic_initial
~~~~

~~~~
https://github.com/zmap/zmap
https://github.com/tumi8/zmap
https://ipv6hitlist.github.io/
~~~~
