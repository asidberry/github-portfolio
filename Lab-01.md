# Lab-01.md

# Lab 01: Enterprise Infrastructure Audit
**Date:** January 2026  
**Status:** Completed  

## 🎯 Objective
To analyze the 2021 Facebook outage from a systems design perspective and identify the specific failure points in their BGP (Border Gateway Protocol) configuration.

## 🛠️ Tools Used
* [Wireshark](https://www.wireshark.org/) (Traffic Analysis)
* [Draw.io](https://www.drawio.com/) (Network Topology Mapping)
* Linux Terminal

## 🔍 Key Findings
1. **Root Cause:** A routine maintenance command unintentionally disconnected Facebook's data centers from the wider internet.
2. **Cascading Failure:** Because the network was down, internal tools (like badge readers) also failed, delaying physical access to the servers.

## 💡 Lessons Learned
This lab highlighted the danger of **Single Points of Failure**. In the future, I would recommend out-of-band management for critical infrastructure to ensure access during a primary network collapse.

## 🤝 GitHub Network
### Following (5+)

* [PaulineKabe](https://github.com/PaulineKabe)

Links to an external site.
* [z-alshehri] (https://github.com/z-alshehri)

Links to an external site.
* [N-alaiban](https://github.com/N-alaiban)

Links to an external site.
* [Mary Lou Hall](https://github.com/mocaorsa()

Links to an external site.
* [ClaireKamobaya](https://github.com/ClaireKamobaya)

### Forked Repositories (2+)
1. **[The Network Execution Tool](https://github.com/asidberry/NetExec.git)** by [PennywOrth](https://github.com/Pennyw0rth)
   - Description: An open-source repository maintained by a community that contributes tools and features for shared use.
   - Relevance: This matters for the IT-520 course because we are learning how to actively engage with the GitHub community. This page allows collaborators to come together to share tools, features, and resources they have discovered, helping to expand collective knowledge. I find it especially helpful for individuals who are new to GitHub and are just beginning to navigate the platform.

2. **[awesome-cybersecurity-learning-resources](https://github.com/asidberry/awesome-cybersecurity-learning-resources.git)** by [Jassics](https://github.com/jassics/awesome-cybersecurity-learning-resources)
   - Description: Jassics has compiled a variety of learning resources related to cybersecurity, including books, YouTube videos, free cybersecurity courses, certifications, and many other valuable sources of information.
   - Relevance: This is relevant to the IT-520 course because new students entering the program, particularly those majoring in cybersecurity, need a stronger understanding of the field. The course emphasizes how infrastructure serves as the core system that supports all operations, while cybersecurity functions to protect that infrastructure from potential threats.

## 📸 Proof of Work
![Network Diagram Placeholder](link-to-your-image-here.png)
<img width="1907" height="955" alt="terminal" src="https://github.com/user-attachments/assets/26fda20a-0120-4a34-9e91-de722791f6d0" />



