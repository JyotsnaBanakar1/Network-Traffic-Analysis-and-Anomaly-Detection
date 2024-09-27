Overview
This report presents a methodology for detecting Distributed Denial of Service (DDoS) attacks using Wireshark and Snort. The project involved capturing and analyzing network traffic to identify potential DDoS attempts, specifically focusing on instances where more than 100 packets originated from the same source within a minute.

Wireshark was utilized for real-time packet capturing, while Snort served as a network intrusion detection system (NIDS) with rule-based alerts. Alerts triggered by Snort were analyzed in Wireshark to understand the nature of the threats, with suspicious IPs cross-referenced against threat intelligence databases.

The findings indicated several potential DDoS attempts, highlighting the effectiveness of the detection framework. Recommendations include continuous monitoring, regular rule updates, and additional security measures to enhance network resilience against attacks.
