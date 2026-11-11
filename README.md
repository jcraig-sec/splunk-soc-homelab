# Splunk SOC Homelab

This repository documents the Splunk labs I am completing as part of my Cyber Defense and Analysis coursework at San Diego City College. I am using these labs to get more hands-on experience with log collection, security monitoring, and working with Splunk.

I am running Splunk Enterprise on my MacBook and using different log sources to practice collecting, searching, and analyzing security events. I will continue adding to this repository as I complete more labs throughout the semester.

## Lab Progress

### Lab 01 - Collection Architecture Design
- Set up Splunk Enterprise and worked with the Universal Forwarder.
- Configured log collection for VPN and badge access events.
- Created a collection architecture for a simulated power utility environment.
- Identified monitoring gaps between IT and OT systems.

### Lab 02 - Log Source Onboarding and Normalization
- Imported VPN, badge access, and authentication logs into Splunk.
- Worked on mapping fields to the Splunk Common Information Model (CIM).
- Troubleshot authentication logs that were being grouped incorrectly.
- Corrected event breaking so Splunk recognized 379 unique authentication events instead of 65 grouped events.
- Compared authentication log hostnames against an asset inventory to identify monitoring coverage gaps.

## Tools Used
- Splunk Enterprise 10.6.1
- Splunk Universal Forwarder
- macOS
- Splunk Search Processing Language (SPL)
- Splunk Common Information Model (CIM)

## Future Labs

I will add screenshots, SPL searches, and notes from each lab as I complete them. The goal is to keep building on this project and document what I learn throughout the course.
