# System Administration and IT Infrastructure Services
# Basic Server Setup – Apache Local Server

## Student Information
**Name:** Rivombo Ndhukwana  
**Course:** System Administration and IT Infrastructure Services  
**Task:** Practical – Basic Server Setup  
**Date:** 06 March 2026  

---

## Overview
This project demonstrates how to set up a simple **local web server using Apache on Linux**.  
The server hosts a basic HTML webpage stored in the Apache web directory.

The project also demonstrates understanding of:
- Web servers
- Linux system administration
- Folder structures
- Hosting a webpage locally

---

## Software Used

| Software | Purpose |
|--------|--------|
| Apache2 | Web server used to host the website |
| Linux (Ubuntu) | Operating system used for the setup |
| Terminal | Used to install and manage the server |

---

## Installation Steps

### 1. Update System





<img width="965" height="551" alt="sudo apt update" src="https://github.com/user-attachments/assets/0bf0095c-643b-47b9-ba9b-c105e58409d8" />


### 2: Install Apache Web Server



<img width="956" height="639" alt="sudo apt  install apache2 -y" src="https://github.com/user-attachments/assets/d0e6a5e1-3854-47de-a875-d6e0cdc4cb5c" />

### 3: Start and enable Apache Service


<img width="954" height="116" alt="sudo systemctl start   enable" src="https://github.com/user-attachments/assets/e891d0a0-1599-44c2-8319-beb8f251a2ed" />


### 4: Check Apache Status 



<img width="958" height="399" alt="sudo systemctl status apache2" src="https://github.com/user-attachments/assets/3a586472-1338-44ae-b1ea-c7e5efd55eaf" />

 ### 5: Test the Web Server


<img width="624" height="465" alt="default page" src="https://github.com/user-attachments/assets/df877577-0bd2-4299-9475-5228845bfff5" />

 ### 6: Locate Website Folder

<img width="513" height="48" alt="Locate Website Folder" src="https://github.com/user-attachments/assets/f0608494-e296-43c8-b9e3-89aade4ba2bc" />


### 7: Create a Simple Webpage


<img width="946" height="452" alt="index html" src="https://github.com/user-attachments/assets/1bedd4c5-345c-4b67-9a69-43c35936639d" />

### 8: View the Custom Webpage

<img width="952" height="337" alt="web page2" src="https://github.com/user-attachments/assets/e25569a1-741c-4adb-aee8-a38ca40a49a1" />


## Services Configured
Apache Web Server

Apache serves website files to users who access the server.
Systemd

Systemd manages system services like Apache.
Localhost

The server runs locally and is accessed using:
http://localhost

## Conclusion

This project demonstrates how to install and configure a basic Apache server on Linux and host a simple webpage locally.




