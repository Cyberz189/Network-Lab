# Network-Lab

## Objective
[Brief Objective]

Utilize Wireshark to identify and analyze potentially suspicious activity within the FTP (File Transfer Protocol) protocol, aiming to detect unauthorized access, data exfiltration, or malicious file transfers. Through packet inspection and protocol analysis, the objective is to pinpoint anomalies such as unusual login attempts, unauthorized file uploads or downloads, unexpected data transfers, or suspicious commands issued during FTP sessions. This process aims to enhance network security by identifying and mitigating potential threats, thereby safeguarding sensitive data and preventing unauthorized access to network resources.


### Skills Learned

- Mastery of Wireshark commands for advanced analysis.
- Expertise in deciphering network logs.
- Proficient in identifying attack signatures and patterns.
- Deep understanding of network protocols and security weaknesses.
- Strengthened critical thinking and cybersecurity problem-solving abilities.
  
### Tools Used

Wireshark

## Steps
![IMG_8584](https://github.com/Cyberz189/Network-Lab/assets/163569052/44523cc3-9ec3-4a33-aaac-82f6c9879eb9)

ftp.response.code == 213 in the search bar isolates the packets and only shares file status due to the "213" code

![IMG_8581](https://github.com/Cyberz189/Network-Lab/assets/163569052/678854e3-efc5-4b9a-aeb4-250d57e0fe66)

By right-clicking and going to follow > TCP stream this allows me to see all of the TCP traffic in a raw readable format since TCP isn't a secure protocol 

![IMG_8582](https://github.com/Cyberz189/Network-Lab/assets/163569052/656f4ddc-8278-4693-910a-fb50db1753e2)


Every screenshot should have some text explaining what the screenshot is about.

Example below.

*Ref 1: Network Diagram*
