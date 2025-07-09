# FTP-Packet-Sniffing-Using-Custom-Windows-FTP-Server-in-VMware-Lab
Designed and deployed a Windows based FTP server using IIS within a VMware lab environment to simulate and analyze unencrypted network traffic via packet sniffing tools like Wireshark.

Skills Demonstrated:
-FTP Server Setup with IIS
-Virtual Network Setup with VMware
-Network Traffic Capture and Analysis
-Understanding of Insecure Protocols (FTP)
-Basic System Administration on Windows
-Client-Server Communication Simulation
-Packet Analysis and credentials Extraction
-Ethical Hacking Techniques (Sniffing attack)

Tools Used:
-VMware workstation
-Windows server 2012
-IIS (Internet Information Services)
-Wireshark
-Kali linux (used to initiate FTP sessions and interact with the server)

Procedure:
This project is divided into three phases:

PHASE-1 FTP Server Setup:
    -Create a folder named FTP in C drive which will be our data to be transfered
    -Go to the service manager and add roles and responsibilites
    -Then configure to set up IIS and enable FTP server
    -Install the requierd setup
    -Open the IIS and add a FTP site with the pathway of your folder in C drive

PHASE-2 FTP Server Access Through Client
    - In Kali Linux terminal, fire the ftp command with the server's IP,after opeining wireshark to start capturing
    - Login with neccessary credentials 
    - Carry out the necessary file commands needed

PHASE-3 Credentials Sniffing Through Wireshark
    - Open Wireshark, and capture the packets
    - Filter it using ftp filter

    ***Observe: you can see the username and password used to login clearly in the captured packets along with all the file commands carried out

Conclusion: Insecure protocols like FTP makes us realize the true importance of secure and encrytped data transfer protocols like SFTP, HTTPS, FTPS

                                                                          ***
  


1
