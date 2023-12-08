# Analyze network layer communication
<p>Scenario:</p>
<p> You are a cybersecurity analyst working at a company that specializes in providing IT consultant services. Several customers contacted your company to report that they were not able to access the company website www.yummyrecipesforme.com, and saw the error “destination port unreachable” after waiting for the page to load. 

You are tasked with analyzing the situation and determining which network protocol was affected during this incident. To start, you visit the website and you also receive the error “destination port unreachable.” Next, you load your network analyzer tool, tcpdump, and load the webpage again. This time, you receive a lot of packets in your network analyzer. The analyzer shows that when you send UDP packets and receive an ICMP response returned to your host, the results contain an error message: “udp port 53 unreachable.” </p>
- DNS and ICMP log  <img src="networklog.png">
- [Network traffic analysis report](https://docs.google.com/document/d/1wNgomprNGqIaI9hLMD7DSfnxbqh7GcBEdsG1cSQWOIk/edit?usp=sharing)

