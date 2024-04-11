Round 2 - GDSC VIT VLR CYBERSECURITY
Task: Samuel 

Steps followed to identify the hidden flag

1. Opened the given .pcapng file using Wireshark
2. Traced which packets were involved in the transfer of data/files (here, HTTPS)
3. Exported all HTTPS objects and saved in another location on the system
4. Detected a .jsp file in the exports
5. The "login.jsp" file contains the HTML code of a login for a simple banking portal webpage.
