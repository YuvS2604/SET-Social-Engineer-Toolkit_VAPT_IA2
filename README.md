# SET-Social-Engineer-Toolkit_VAPT_IA2

Department of Computer Engineering

VAPT - IA II
Software Engineering Tool (SET)
Bhoomi Sanghvi - 16010122161
Nishtha Savla - 16010122165
Jay Shah - 16010122170
Yuv Shah - 16010122177
Batch: H1

Department of Computer Engineering
K. J. Somaiya College of Engineering
(Constituent College of Somaiya Vidyavihar University)
Academic Year 2024-25






Table of Contents

I) Overview	3
II) Setup and Installation	4
III) Features and Applications	4
IV) Social Engineering Attacks	5
Setting Up the Testing Environment	5
1) Spear-Phishing Attack Vectors	5
2) Website Attack Vectors	6
3) Mass Mailer Attack	6
4) Infectious Media Generator	6
5) Create a Payload and Listener	6
6) QRCode Generator Attack Vector	7
7) Arduino-Based Attack Vector	7
8) Wireless Access Point Attack Vector	7
9) PowerShell Attack Vectors	7
10) Third Party Modules	8
V) Conclusion	8
Key takeaways	8



I) Overview

The Social-Engineer Toolkit (SET) is an advanced open-source penetration testing framework designed specifically to perform social engineering attacks. Unlike many cybersecurity tools that focus on technical vulnerabilities in networks or systems, SET is unique in that it focuses on exploiting the human element. It is used to simulate realistic social engineering attacks including phishing emails, website cloning, malicious file delivery, and credential harvesting. The aim is to test an organization’s awareness and preparedness against psychological manipulation techniques that hackers employ.
SET’s framework is written in Python and integrates seamlessly with other well-known tools like Metasploit. With its menu-driven interface and customizable payload options, it allows even novice testers to craft and execute sophisticated attacks. Its ability to create realistic, convincing attack vectors makes SET invaluable for training, simulation, and awareness campaigns.



II) Setup and Installation
SET is pre-installed in security-focused Linux distributions like Kali Linux. For other systems:
Installation on Debian-based systems requires running apt-get install set
Manual installation involves cloning the GitHub repository: git clone https://github.com/trustedsec/social-engineer-toolkit.git
After installation, launching SET is done through the terminal with the command setoolkit
The toolkit requires Python and various dependencies, which are automatically installed during setup
Administrative privileges are necessary for proper functionality
III) Features and Applications

Social-Engineering Attacks: A Social Engineering Attack manipulates human behavior to gain unauthorized access to systems, data, or physical locations.
Penetration Testing (Fast-Track): Contains rapid penetration testing tools including database attacks, automated Metasploit launches, and simplified exploitation techniques for quick assessment
Third Party Modules: Extends SET functionality through community-developed modules for specialized attack scenarios and emerging threat vectors
Update Management: Built-in update functionality ensures security professionals always have access to the latest attack vectors and countermeasures
Configuration Management: Allows customization of SET parameters to adapt to specific testing environments and organizational requirements
[Note: Out of the above features, we have implemented Social-Engineering Attack]





IV) Social Engineering Attacks
Setting Up the Testing Environment
For a controlled assessment environment:
Configure an attacker machine (typically running Kali Linux) with SET installed
Set up a target machine that represents an employee workstation
Establish an isolated network to prevent unauthorized access
Document the testing scope and obtain proper authorization before conducting any assessments
Implement monitoring tools to track attack progression and effectiveness.
The Social Engineering Attacks provides these attacks:-


The Social Engineering Attacks menu provides access to various attack vectors that exploit human psychology and behavior to compromise security. These include:
1) Spear-Phishing Attack Vectors
Highly targeted phishing attacks customized for specific individuals or organizations.
Includes options for crafting personalized emails with malicious attachments.
Supports email template customization to mimic legitimate communications.
Enables attachment of various payload types including executable files and office documents.
Offers tracking capabilities to monitor victim interactions with phishing content.


2) Website Attack Vectors
In Website Attack Vectors, there are multiple methods used as shown:-






Here, the main focus will be on the Credential Harvester Attack Method.
The credential harvester is among SET's most powerful features:
This attack creates a clone of legitimate websites (e.g., corporate portals, webmail).
The victim is directed to the cloned site through phishing emails or other social engineering methods.
When users enter credentials on the fake site, the information is captured by the attacker.
SET provides real-time monitoring of submitted credentials.
Attack effectiveness is enhanced through domain spoofing techniques and SSL certificate manipulation.




3) Mass Mailer Attack
Enables large-scale phishing campaigns targeting multiple recipients.
Allows customization of email templates with organization-specific content.
Supports HTML emails with embedded malicious links or attachments.
Features tracking capabilities to monitor email open rates and link clicks.
Includes options for email address spoofing to impersonate trusted sources.
Can be configured to use various SMTP servers for delivery.
Provides analytics on campaign effectiveness for reporting purposes.


4) Infectious Media Generator
Creates autorun-enabled payloads for USB drives and other removable media.
Supports multiple payload types including executable files and batch scripts.
Exploits Windows autorun functionality to execute payloads automatically.
Includes options for disguising malicious files as legitimate documents.
Provides multi-staged payload capabilities for advanced attack scenarios.
5) Create a Payload and Listener
SET enables creation of complete attack scenarios:
Payload generation involves creating malicious files disguised as legitimate documents.
The toolkit supports various payload types including executable files, office documents, and PDFs.
Metasploit integration allows creation of sophisticated payloads with advanced capabilities.
The listener component establishes connection channels between the victim and attacker machine.
Once executed on the victim's system, payloads can provide remote access, data exfiltration, or privilege escalation.



6) QRCode Generator Attack Vector
Mobile-focused attack vectors in SET include:
QR code generator creates codes that direct users to malicious websites or trigger malware downloads.
Android attack frameworks allow creation of trojanized applications.
SMS spoofing capabilities enable text-based phishing campaigns.
Mobile attack vectors can bypass traditional security controls focusing on computer systems.
These techniques exploit the growing reliance on mobile devices and reduced security awareness on these platforms.

7) Arduino-Based Attack Vector
Leverages Arduino devices for physical access attacks.
Creates programmable HID (Human Interface Device) attacks.
Enables keystroke injection for credential theft and command execution.
Supports automatic deployment of payloads through USB connections.
Provides options for disguising malicious devices as legitimate peripherals.



8) Wireless Access Point Attack Vector
Creates rogue wireless access points to intercept network traffic.
Implements captive portal attacks for credential harvesting.
Supports DNS spoofing to redirect users to malicious websites.
Enables man-in-the-middle attacks against wireless communications.
Includes options for Evil Twin attacks impersonating legitimate networks.
9) PowerShell Attack Vectors
Advanced attack methods in SET include:
PowerShell-based attacks that evade traditional antivirus detection.
Creation of infectious media (USB drives, CDs) that automatically execute when connected.
Autorun functionality exploitation to trigger payload execution.
HTA (HTML Application) attack vectors for web-based delivery.
These techniques leverage trusted applications and processes to bypass security controls.





10) Third Party Modules
Extends SET functionality through community-developed modules.
Includes SMS spoofing tools for text-based phishing campaigns.
Provides wireless attack tools beyond standard SET capabilities.
Offers specialized modules for emerging attack vectors.
Supports integration with other security testing frameworks.
Enables customized attack scenarios for specific target environments.
V) Conclusion
The Social Engineering Toolkit represents an essential resource for security professionals conducting authorized penetration tests focused on human factors. Its comprehensive suite of tools enables realistic assessment of an organization's resilience against social engineering threats. By identifying vulnerabilities in human security awareness, organizations can develop targeted training programs and implement appropriate technical controls.
Key takeaways:
Social engineering remains one of the most effective attack vectors in the current threat landscape
SET provides a structured methodology for assessing these vulnerabilities
Testing must always be conducted ethically and with proper authorization
Results should inform comprehensive security awareness training programs
Regular assessments are necessary as social engineering techniques continuously evolve
Technical controls should complement human awareness to create defense-in-depth
Understanding and testing social engineering vulnerabilities through tools like SET is crucial for developing a robust security posture that addresses both technical and human aspects of cybersecurity.


