TCP header interpretation from wireshark
->Source Port (srcport): 443
This indicates that the packet was sent from port 443, which is typically used for HTTPS.

Destination Port (dstport): 50152
This indicates that the packet was sent to port 50152.

Sequence Number: 1
The sequence number for this TCP segment. It represents the first byte of data in this segment.

Acknowledgment Number: 1
The acknowledgment number is set to 1, indicating that the sender is expecting the next segment to start with byte 1.

Header Length: 32 bytes (1000 in binary format)
This specifies the size of the TCP header. In this case, the header length is 32 bytes.

Flags: 0x010 (ACK)
The flags field is used to control various aspects of the connection. The flag 0x010 indicates that the ACK (Acknowledgment) flag is set.

Window Size: 350
This is the size of the receive window, which tells the sender the amount of data the receiver can accept.

Checksum: Not explicitly shown in the provided details but would be included in the full TCP header.

Urgent Pointer: Not present (typically 0 if the URG flag is not set).

UDP header interpretation from wireshark
->Using Packet No. 1 as an example:
Source Port: 443
This is typically used for HTTPS traffic.
Destination Port: 65056
This is a high-range ephemeral port, commonly used for temporary communication needs.
Length: 77 bytes
The length of the UDP packet, including the header and data.
Checksum: 0xf916 (unverified)
Used to detect errors in the UDP packet.
