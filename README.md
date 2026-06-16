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
To complete this project, you will typically use a Linux environment (like Kali Linux, where theHarvester comes pre-installed) or install it via Python/pip.
where we will focus on two web--application
* Vulnbank.org
* bestina.onrender.com

           NOTE: permission have been giving by the org
  * Vulnbank.org is a vulnerable web--application created for cybersecurity pratices
   <img width="1918" height="839" alt="Screenshot_2026-06-16_08_32_01" src="https://github.com/user-attachments/assets/e0ec6175-2f52-429e-a047-6be781b23c3e" />
   <img width="1918" height="839" alt="Screenshot_2026-06-16_08_31_43" src="https://github.com/user-attachments/assets/a21d71be-5b7b-44e2-82f6-429cb5dfbd64" />

 after a deep scan
* 15 IPs founds
* 0 linkedin link
* No email found
* No people found
* No host found


* bestina.orender.com is an E-commerce shipping web- site powered by orender
 <img width="1918" height="839" alt="Screenshot_2026-06-16_08_47_22" src="https://github.com/user-attachments/assets/7369852d-7306-4c06-baea-3c5dc2ef30e9" />
<img width="1918" height="839" alt="Screenshot_2026-06-16_16_45_54" src="https://github.com/user-attachments/assets/cde11868-1595-455f-8e48-19b50331f689" />
After a deep scan
* 2 IPS found
* No emails found
* No people founf
* 19 host found

  
# Conclusion
 This project successfully demonstrates how automation can streamline open-source intelligence (OSINT) gathering during the reconnaissance phase of a security assessment. By wrapping theHarvester (v4.x+), this tool efficiently maps an organization's attack surface—uncovering subdomains, public email patterns, and active IP ranges from decentralized public feeds. The results underscore the critical importance of continuous asset discovery, enabling security teams to identify exposed infrastructure and shadow IT before malicious actors can exploit them.
  
  
