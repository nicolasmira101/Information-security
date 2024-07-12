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

![Imagen](https://i.imgur.com/jWyn4H7.png)

![Imagen](https://preview.redd.it/xegh56kbrk751.png?width=679&format=png&auto=webp&s=178918de96031d24292c15c8cc34f2163b70f84b)


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

**7. Ryan intends to perform a vulnerability assessment on a business-critical system utilizing high-risk plug-ins. What would be the most effective strategy for the initial scan?**
   - [ ] Do not run the scan to avoid disrupting the business.
   - [ ] Run the scan during business hours.
   - [X] Run the scan in a test environment.
   - [ ] Run the scan against production systems to achieve the most realistic results possible.

   **Run the scan in a test environment**: this ensures that any potential disruptions or negative impacts caused by the high-risk plug-ins do not affect the actual business operations. This approach allows you to identify and address vulnerabilities without jeopardizing the stability and availability of the production system.

**8. Among the following methods, which technique qualifies as passive reconnaissance?**
   - [ ] Footprinting.
   - [ ] Port scans.
   - [ ] Vulnerability scans.
   - [X] WHOIS lookups

   **WHOIS lookups**: involve querying public databases to obtain information about the ownership and registration details of a domain name or IP address. This method does not interact directly with the target system or network, making it a passive form of reconnaissance.

**9. Kevin is setting up a web server to utilize digital certificates. What technology enables clients to swiftly confirm the status of those certificates without reaching out to a remote server?**
   - [ ] Certificate pinning
   - [X] Certificate stapling
   - [ ] OCSP
   - [ ] CRL

   **Certificate stapling**: allows a web server to obtain a time-stamped response from the Certificate Authority (CA) about the status of its certificate (using the Online Certificate Status Protocol, OCSP) and "staple" this response to the TLS handshake. This way, the client can verify the certificate status immediately without needing to contact the CA's OCSP server directly.

**10. Which digital certificate offers the highest level of confidence that the certificate owner's identity is genuine?**
   - [X] EV
   - [ ] UV
   - [ ] OV
   - [ ] DV

   **EV (Extended Validation)**: certificates require a rigorous validation process, including verification of the organization’s legal existence, physical address, and operational status. This thorough vetting process provides the highest level of assurance regarding the certificate owner's identity.

**11. Layla recently uncovered an incident where an attacker compelled a network user to utilize weak encryption,subsequently decrypting the content. What term accurately characterizes this attack?**
   - [ ] Collision
   - [X] Downgrade
   - [ ] Homomorphic encryption
   - [ ] Birthday attack

   **Downgrade**: this attack involves forcing a system or user to use a weaker encryption protocol or cipher than it would normally use, thereby making it easier for the attacker to decrypt the communication. This can happen if the attacker manipulates the communication or compromises the negotiation process between the client and server to select a weaker encryption standard.

**12. Among the following servers in a substantial PKI implementation, which one is typically an offline CA?**
   - [ ] Internal CA
   - [ ] RA
   - [ ] Intermediate CA
   - [X] Root CA

   **Root CA**: is typically an offline server. It is the top-most CA in the hierarchy, responsible for issuing and signing Intermediate CA certificates. Root CA keys are kept offline to protect them from compromise.

**13. Kevin aims to establish a security measure capable of enforcing access restrictions across all of his organization's SaaS solutions. Which control would be most suitable for fulfilling his requirements?**
   - [ ] SWG
   - [X] CASB
   - [ ] Security groups
   - [ ] Resource policy

   **CASB (Cloud Access Security Broker)** are specifically designed to provide visibility and control over data that is stored in and accessed through cloud applications. They allow organizations to enforce access policies, monitor activities, and protect data across multiple SaaS solutions.

**14. Greg is in search of a document that provides guidance on mapping cloud security controls to various regulatory standards. Which would be most helpful for this purpose?**
   - [ ] NIST SP 500-292
   - [ ] ISO 27002
   - [X] CSA CCM
   - [ ] PCI DSS

   **CSA CCM (Cloud Security Alliance Cloud Controls Matrix)**: provides a detailed mapping of security controls to various regulatory standards, frameworks, and industry standards. It is specifically designed to help organizations align their cloud security practices with different compliance requirements and regulatory frameworks.

**15. Which access control scheme most accurately characterizes the Linux filesystem?**
   - [X] DAC
   - [ ] ABAC
   - [ ] RBAC
   - [ ] MAC

   **DAC (Discretionary Access Control)**: DAC allows users to control access to their own resources. In Linux filesystems, file and directory permissions (such as read, write, execute) are set by the owner of the file or directory, which aligns with DAC principles.

**16. Linda developed a new payroll system which she provides to her clients. She hosts the payroll system on AWS, and her clients access it via the web. Which level of cloud computing most accurately characterizes Linda's service?**
   - [X] SaaS
   - [ ] IasS
   - [ ] FaaS
   - [ ] PaaS

   **SaaS (Software as a Service)**: in this model, the provider (Linda) hosts applications and makes them available to customers (her clients) over the internet. Clients access the software using a web browser without needing to manage any underlying infrastructure, such as servers, operating systems, or network components.

**17. Samantha is deploying a PAM solution and seeks to guarantee accessibility to root passwords during system outages. Which PAM-associated tool is most apt for addressing this scenario?**
   - [X] Password vaulting
   - [ ] Ephemeral accounts
   - [ ] Just-in-time permissions
   - [ ] Token-based authentication

   **Password vaulting**: this tool securely stores and manages passwords, allowing authorized users to retrieve them when needed, including during system outages.

**18. John intends to acquire a forensic duplicate of an operational virtual machine. Which method should he employ to capture the image?**
   - [ ] Run dd from within the running machine.
   - [X] Use FTK Imager from the virtual machine host.
   - [ ] Use the VM host to create a snapshot.
   - [ ] Use WinHex to create a copy from within the running machine

   **Use FTK Imager from the virtual machine host**: FTK Imager is a forensic imaging tool that can create a forensic duplicate of a virtual machine's disk. Running it from the virtual machine host ensures that the image is captured without interfering with the live state of the virtual machine, providing a more accurate and reliable forensic image.

## Resources<a name="id7"></a>

- [CompTIA Security+ Certification Exam Objectives](https://static.platzi.com/media/public/uploads/comptia-security-sy0-701-objectives_2a47ec72-7e00-4723-99a5-667ae2b9e074.pdf)
- [CompTIA Example Simulation](https://demosim.comptia.io/)
- [CompTIA SY0-701 Security+ Training Course](https://www.youtube.com/playlist?list=PLG49S3nxzAnl4QDVqK-hOnoqcSKEIDDuv) 



