# Pen-tools

#### Below is an assortment of open-source tools that I utilize when conducting penetration tests. They are categorized as follows:

    - Reconnaissance and Enumeration
    - Initial Exploitation
    - Privilege Escalation
    - Post Exploitation Information Gathering

### Reconnaissance and Enumeration
  - AutoRecon.py by Tib3rius @ https://github.com/Tib3rius/AutoRecon
    - AutoRecon essentially automates the use of fundamental tools such as Nmap, Nikto, Gobuster, etc.
    - The tool works recursively to an extent, running following up scripts based on information gathered by initial port scans. (i.e. if port 80 is found to open, Nikto will be run against it)
    - Multi-threading is also used by the tool, so while AutoRecon is still running port scans, follow up tools like the aforementioned Nikto can be started
    - 
