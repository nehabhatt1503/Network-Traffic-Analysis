# Tcpdump
Tcpdump is a command-line packet sniffer that can directly capture and interpret data frames from a file or network interface. To capture network traffic from "off the wire," it uses the libraries pcap and libpcap, paired with an interface in promiscuous mode to listen for data.

```
└─$tcpdump --version
tcpdump version 4.99.4
libpcap version 1.10.4 (with TPACKET_V3)
OpenSSL 3.2.2 4 Jun 2024
```

```
└─$ tcpdump -D      //List Available Interfaces      
1.eth0 [Up, Running, Connected]
2.tun0 [Up, Running, Connected]
3.tun1 [Up, Running, Connected]
4.any (Pseudo-device that captures on all interfaces) [Up, Running]
5.lo [Up, Running, Loopback]
6.bluetooth-monitor (Bluetooth Linux Monitor) [Wireless]
7.nflog (Linux netfilter log (NFLOG) interface) [none]
8.nfqueue (Linux netfilter queue (NFQUEUE) interface) [none]
9.dbus-system (D-Bus system bus) [none]
10.dbus-session (D-Bus session bus) [none]
```

