# Reconnaissance-Gathering-target-intelligence-using-osint-tools
# theHarvester to map an organization's digital footprint (domains,emails,IP ranges
Reconnaissance in cybersecurity is the preliminary phase of a cyberattack where threat actors gather information and intelligence about a target system, network, or organization.
# Active vs. Passive Reconnaissance
Reconnaissance is divided into two primary strategic methodologies.
* __*Passive Reconnaissance:*__ Gathering information without interacting with the target system. It relies entirely on publicly available resources to avoid triggering security alerts.
* __*Active Reconnaissance:*__ Interacting directly with the target infrastructure to elicit a response. This technique yields highly accurate data but leaves traces in firewall and intrusion detection logs.
# Overview of theHarvester
___________________________
**theHarvester** is a popular open-source intelligence (OSINT) tool used during the __passive reconnaissance_ phase of a penetration test or security audit. It is designed to gather subdomains, email addresses, open ports, employee names, and virtual hosts from various public data sources like search engines (Google, Bing), PGP key servers, and professional networks (LinkedIn).Because it only queries external, third-party databases, using theHarvester is completely passive and will not alert the target organization.
# Step-by-Step Project Guide
To complete your project, you will typically use a Linux environment (like Kali Linux, where theHarvester comes pre-installed) or install it via Python/pip.
