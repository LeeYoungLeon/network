Some examples of using libpcap and header decoding

* `pkt_lengths`: a minimal libpcap program that prints packet lengths
* `pkt_lengths_file`: can read packets from interface or from pcap file
* `compile_filter`: compiles a filter expression
* `hardcoded_filter`: filter expression hardcoded from tcpdump -dd 
* `decode_tcp_headers`: decode link level, ip and udp or tcp header 
* `iface_stats`: gather interface statistics periodically
* `signal_driven_capture`: use signal driven I/O with pcap socket, iface stats
* `multi_mode`: read from interface or one PCAP or watch incoming pcap directory
* `pkt_bloom` : small libpcap program that creates a Bloom filter from packets
* `cross_border`: run bitwise test to see if an IP packet crosses a cidr border
