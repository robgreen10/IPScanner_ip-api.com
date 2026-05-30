Summary:

This Python tool automates threat intelligence by checking suspicious IP addresses to help security teams catch malicious activity early.
You enter an IP address, and the script initiates a secure API call to a server to pull back infrastructure details like the ISP, country, and organization.
It uses a defensive code framework with built-in network timeouts so the script never freezes if your internet connection drops.
The tool automatically analyzes the server's data against custom security rules to determine if the infrastructure looks safe or malicious.
I added my own custom high-risk rules to flag specific countries, so the scanner alerts you immediately if the traffic originates from China, France, or Russia.
