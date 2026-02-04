Lab 01: Enterprise Infrastructure Audit
Arielle Sidberry
Date: January 29 2026
Status: Completed

🎯 Objective
To analyze the 2021 Facebook outage and document the information on GitHub.

🛠️ Tools Used
Wireshark (Traffic Analysis)
Draw.io (Network Topology Mapping)
Linux Terminal
🔍 Key Findings
Root Cause: A routine maintenance command unintentionally disconnected Facebook's data centers from the wider internet.
Cascading Failure: Because the network was down, internal tools (like badge readers) also failed, delaying physical access to the servers.
💡 Lessons Learned
This lab highlighted the danger of Single Points of Failure. In the future, I would recommend out-of-band management for critical infrastructure to ensure access during a primary network collapse.

📸 Proof of Work
