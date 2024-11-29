# Tcpdump
Tcpdump is a command-line packet sniffer that can directly capture and interpret data frames from a file or network interface. To capture network traffic from "off the wire," it uses the libraries pcap and libpcap, paired with an interface in promiscuous mode to listen for data.

``` └─$ - tcpdump --version
tcpdump version 4.99.4
libpcap version 1.10.4 (with TPACKET_V3)
OpenSSL 3.2.2 4 Jun 2024
```
