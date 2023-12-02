This folder contains a mock cybersecurity incident and accompanying analysis using tcpdump, conducted my myself. Please review the scenario below, followed by my analysis contained within this same folder.

You are a cybersecurity analyst working at a company that specializes in providing IT consultant services. Several customers contacted your company to report that they were not able to access the company website yummyrecipesforme.com, and saw the error “destination port unreachable” after waiting for the page to load. 

You are tasked with analyzing the situation and determining which network protocol was affected during this incident. To start, you visit the website and you also receive the error “destination port unreachable.” Next, you load your network analyzer tool, tcpdump, and load the webpage again. This time, you receive a lot of packets in your network analyzer. The analyzer shows that when you send UDP packets and receive an ICMP response returned to your host, the results contain an error message: “udp port 53 unreachable.” 

![image](https://github.com/LiamCantwell/Portfolio/assets/28920160/a1387e98-b04c-41b6-a2d4-8db859e84343)
