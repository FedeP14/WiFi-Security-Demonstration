# WiFi Security Demonstration 🔐

This repository contains a comprehensive project exploring vulnerabilities and attack methods on wireless networks. The project focuses on the widely used WPA2 protocol and highlights critical security concepts through practical simulations conducted in a controlled environment.

## 🌟 Overview

Wireless networks are ubiquitous, but their security is often underestimated. This project bridges theoretical knowledge with hands-on experimentation to analyze and demonstrate common vulnerabilities in wireless network security. The findings emphasize the importance of encryption protocols and strong authentication mechanisms.

## 🚀 Simulations

The project includes the following simulations:

1. **WPA2 Handshake Capture and Brute-Force Attack**  
   - Demonstrated the capture of the WPA2 four-way handshake using `aircrack-ng` tools.
   - Performed a dictionary attack to recover weak passwords and highlighted the need for strong passphrases.

2. **Evil Twin Attack**  
   - Created a rogue access point (Evil Twin) mimicking a legitimate network using `airbase-ng`.
   - Showcased the risks of user deception and the importance of server certificate verification.

3. **Data Interception on Open Networks**  
   - Simulated the interception of plain-text data (username and password) transmitted over an unencrypted network.
   - Analyzed the captured HTTP traffic with `Wireshark`, demonstrating the risks of unprotected communications.

## 🛠 Tools Used

- **Aircrack-ng Suite**: Tools like `airomon-ng`, `airodump-ng`, `airbase-ng`, and `aireplay-ng` for network monitoring, packet capture, and injection.
- **Wireshark**: Network protocol analyzer for inspecting captured traffic.
- **Python**: Hosted a simple HTTP site for data interception demonstrations.

