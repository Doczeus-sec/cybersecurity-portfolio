# Packet Analysis Investigation

## Objective
Analyze captured network traffic to understand DNS queries, TCP handshakes, and encrypted TLS session

## Tool Used
- Wireshark

## Steps Performed
1. Captured live traffic from the Wi-Fi interface.
2. Filtered DNS traffic using: 'dns'
3. Identified domains contacted by the system.
4. Examined TLS Client Hello packets to extract Server Name Indication (SNI).
5. Followed TCP streams to inspect encrypted traffic patterns.

## Findings
- Observed DNS queries to several domains.
- Detected TLS encrypted sessions over port 443.
- Identified domains contacted by background applications.

## Skills Demonstrated
- Network traffic inspection
- DNS analysis
- TLS handshake interpretation
