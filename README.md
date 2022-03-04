# zmap-githubactions
[![kali-tools-top10 with zmap CI workflow](https://github.com/githubfoam/zmap-githubactions/actions/workflows/kali-tools-top10-wf.yml/badge.svg)](https://github.com/githubfoam/zmap-githubactions/actions/workflows/kali-tools-top10-wf.yml)  
[![zmap IPV6 with alpine  CI workflow](https://github.com/githubfoam/zmap-githubactions/actions/workflows/alpine-ipv6-wf.yml/badge.svg)](https://github.com/githubfoam/zmap-githubactions/actions/workflows/alpine-ipv6-wf.yml)  
[![zmap IPV6 with ubuntu  CI workflow](https://github.com/githubfoam/zmap-githubactions/actions/workflows/ubuntu-ipv6-wf.yml/badge.svg)](https://github.com/githubfoam/zmap-githubactions/actions/workflows/ubuntu-ipv6-wf.yml)  
[![zmap with alpine  CI workflow](https://github.com/githubfoam/zmap-githubactions/actions/workflows/alpine-wf.yml/badge.svg)](https://github.com/githubfoam/zmap-githubactions/actions/workflows/alpine-wf.yml)  
[![zmap with archlinux  CI workflow](https://github.com/githubfoam/zmap-githubactions/actions/workflows/archlinux-wf.yml/badge.svg)](https://github.com/githubfoam/zmap-githubactions/actions/workflows/archlinux-wf.yml)  
[![zmap with debian CI workflow](https://github.com/githubfoam/zmap-githubactions/actions/workflows/debian-wf.yml/badge.svg)](https://github.com/githubfoam/zmap-githubactions/actions/workflows/debian-wf.yml)  
[![zmap with fedora CI workflow](https://github.com/githubfoam/zmap-githubactions/actions/workflows/fedora.yml/badge.svg)](https://github.com/githubfoam/zmap-githubactions/actions/workflows/fedora.yml)  
[![zmap with kalilinux/kali-rolling  CI workflow](https://github.com/githubfoam/zmap-githubactions/actions/workflows/kalilinux-wf.yml/badge.svg)](https://github.com/githubfoam/zmap-githubactions/actions/workflows/kalilinux-wf.yml)  
[![zmap with macos  CI workflow](https://github.com/githubfoam/zmap-githubactions/actions/workflows/macos-wf.yml/badge.svg)](https://github.com/githubfoam/zmap-githubactions/actions/workflows/macos-wf.yml)  
[![zmap with ubuntu  CI workflow](https://github.com/githubfoam/zmap-githubactions/actions/workflows/ubuntu-wf.yml/badge.svg)](https://github.com/githubfoam/zmap-githubactions/actions/workflows/ubuntu-wf.yml)    

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
