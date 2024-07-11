# CompTIA Security+ (SY0-701)

## **Índice**   
1. [General Security Concepts](#id1)
2. [Threats, Vulnerabilities, and Mitigations](#id2)
3. [Security Architecture](#id3)
4. [Security Operations](#id4)
5. [Security Program Management and Oversight](#id5)
6. [Practice Test](#id6)
7. [Resources](#id7)
   
## General Security Concepts<a name="id1"></a>
Texto del primer apartado

## Threats, Vulnerabilities, and Mitigations<a name="id2"></a>
Texto del segundo apartado

## Security Architecture<a name="id3"></a>
Texto del primer apartado

## Security Operations<a name="id4"></a>
Texto del segundo apartado

## Security Program Management and Oversight<a name="id5"></a>
Texto del primer apartado

## Practice Test<a name="id6"></a>

**1. Chris desires systems connecting to his network to transmit their boot processes to a server for validation before gaining network access. Which technology should he employ to achieve this functionality on the workstations?**
   - [ ] UEFI/Trusted boot 
   - [ ] BIOS/Trusted boot
   - [X] UEFI/Measured boot
   - [ ] BIOS/Measured boot

   **UEFI/Measured boot**: Measured Boot, when used with UEFI, ensures that each component involved in the boot process is measured          (hashed) and those measurements are sent to a trusted server for validation. This helps to ensure the integrity of the boot process      and can prevent compromised systems from gaining network access.

**2. Fred aims to secure the administrative interfaces for switches and routers, preventing access by potential attackers. Which solution should he propose as a component of his organization's network design?**
   - [X] Out-of-band management
   - [ ] NAC
   - [ ] Trunking
   - [ ] Port security

   **Out-of-band (OOB)**: management provides a separate and dedicated network channel for management traffic. This channel is isolated       from the main data network, meaning that administrative access to network devices like switches and routers does not occur over the      same network as user data traffic. This separation enhances security by ensuring that even if the main network is compromised, the       administrative interfaces remain inaccessible to potential attackers.

**3. Ivan oversees an enterprise wireless network and notices from his heatmap that two access points are possibly interfering with each other. What action is the enterprise access controller most likely to take to address this conflict?**
   - [ ] Increase the broadcast power of one of the access points.
   - [X] Decrease the broadcast power of the access points.
   - [ ] Change the SSID for one of the access points.
   - [ ] Disable one of the access points.

   **Decrease the broadcast power of the access points**: By reducing the broadcast power, the access points' coverage areas are decreased, which can help minimize overlap and interference between the two APs. This adjustment can improve overall network performance and reduce co-channel and adjacent-channel interference.

**4. Gary seeks to employ secure protocols for email access among his end users. Which combination of protocols should he deploy to achieve this objective?**
   - [ ] DKIM, DMARC, HTTPS.
   - [ ] SPF, POPS, IMAPS.
   - [ ] DMARC, DKIM, SPF.
   - [X] POPS, IMAPS, HTTPS

   **POPS, IMAPS, HTTPS**:
   - POPS is a secure version of the POP3 protocol, which is used by email clients to retrieve emails from a mail server. By using SSL/TLS, it encrypts the email messages during transmission, ensuring that the email contents are protected from eavesdropping.
   - IMAPS is a secure version of the IMAP protocol, which is used by email clients to access and manage emails on a mail server. Like POPS, it uses SSL/TLS to encrypt the communication between the email client and server, providing secure access to emails.
   - HTTPS is the secure version of HTTP, and it is used to encrypt web traffic. In the context of email, it ensures that any web-based email access (such as accessing email via a webmail interface) is secure and encrypted. 

**5. What kind of malware is probably involved if John suspects that a system he manages got infected when a user inserted a USB drive, with the user stating they only accessed one file to identify its owner?**
   - [ ] A worm 
   - [X] A virus
   - [ ] A trojan
   - [ ] A spyware tool

   **A virus**: is a type of malware that attaches itself to legitimate files or programs and spreads to other files       and systems when those files or programs are executed. USB drives are common vectors for viruses because they can      easily transfer infected files between computers.

**6. During a penetration test, Kyle infiltrates an organization's database server and installs a backdoor for future access. Which term most accurately describes this action?**
   - [X] Persistence
   - [ ] Retention
   - [ ] Lateral movement
   - [ ] Privilege escalation

   **Persistence**: refers to techniques used by attackers to maintain their access to a compromised system over a         long period. By installing a backdoor, Kyle ensures he can access the database server in the future, even if the       initial point of entry is discovered and closed.


## Resources<a name="id7"></a>

- [CompTIA Security+ Certification Exam Objectives](https://static.platzi.com/media/public/uploads/comptia-security-sy0-701-objectives_2a47ec72-7e00-4723-99a5-667ae2b9e074.pdf)
- [CompTIA Example Simulation](https://demosim.comptia.io/)



