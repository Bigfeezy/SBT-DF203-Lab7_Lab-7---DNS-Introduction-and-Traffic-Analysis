# SBT-DF203-Lab7_Lab-7---DNS-Introduction-and-Traffic-Analysis
SBT-DF203 Lab 7 — DNS Introduction and Traffic Analysis. Query/response field extraction, transaction matching, browser DNS inventory, and DNS-to-connection correlation via dig/Wireshark/tshark.
Practical assessment for the ICDFA SBT-DF203 course. Builds a normal DNS forensic
baseline: identifying the configured resolver, querying A/AAAA/MX/NS records with
dig, capturing and extracting DNS query/response fields at the packet level, and
matching transactions using transaction ID plus endpoint-tuple verification.

Includes a real browser DNS inventory (26 distinct domains queried for a single
page load) and a direct DNS-to-connection correlation, linking a resolved IP
address to the subsequent TCP SYN that used it.

**Contents:** DNS evidence captures (pcap/pcapng), dig outputs, tshark field
extractions, transaction-matching tables, screenshots, and the final report (PDF).

Submitted for SBT-DF203, Delivery Block 3/3, September 2026.
