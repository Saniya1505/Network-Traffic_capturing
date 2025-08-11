# Network Traffic Capture and Analysis using Wireshark

## Objective
The goal of this task was to capture live network packets using Wireshark and analyze them to identify basic protocols and traffic types.

## Tools Used
- **Wireshark** (for packet capturing and analysis)

## Steps Performed
1. **Installed Wireshark** on the system.
2. **Selected the active network interface** to capture traffic.
3. **Started the capture** and generated network activity by browsing websites and performing ping operations.
4. **Captured live traffic for around one minute** to ensure sufficient data.
5. **Stopped the capture** once enough packets were recorded.
6. **Applied protocol filters** (e.g., `TCP`, `DNS`, `UDP`) to examine different traffic types.
7. **Identified at least 3 protocols** from the captured data:
   - **TCP**: Used for reliable communication between devices.
   - **DNS**: Used for resolving domain names to IP addresses.
   - **UDP**: A lightweight, connectionless protocol for fast data transfer.
8. **Exported the capture file** in `.pcap` format for submission.
9. **Prepared a report** summarizing the captured data and findings, along with screenshots of filtered protocol views.

## Findings
- The network traffic contained multiple protocols.
- **TCP** packets showed reliable communication between client and server.
- **DNS** packets showed domain name resolution requests and responses.
- **UDP** packets demonstrated fast, connectionless communication.

## Deliverables
- `.pcap` file containing captured network traffic.
- Detailed analysis report with protocol-specific observations and screenshots.
