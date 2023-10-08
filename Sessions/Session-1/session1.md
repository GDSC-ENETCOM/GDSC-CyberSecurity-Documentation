# CYBER SECURITY SESSIONS DOCUMENTATION
This is the first session's documentation

# Understanding Cybersecurity
## 1. What is Cybersecurity?
Cybersecurity protects computer systems, networks, and digital information from theft, damage, unauthorized access, and other cyber threats.
![growing-need-social-share](https://github.com/nattycoder/GDSC-ENETCOM-CYBERSECURITY-DEPARTMENT/assets/88007154/fcfed18c-665d-43cf-8499-51e33f44aafb)

## 2. Why is Cybersecurity Important?
* ### Data Protection:
  Cybersecurity safeguards sensitive personal, business, and government data from theft or compromise.
* ### Reputation Preservation:
  It prevents loss of trust, financial damage, and lasting harm to an individual, organization, or government's reputation.
* ### Business Continuity:
  Cybersecurity ensures uninterrupted operations by preventing downtime caused by cyberattacks.
* ### National Security:
  It's critical for protecting critical infrastructure and sensitive government information.
* ### Global Impact:
  In an interconnected world, cyber threats can have international consequences.
  
In essence, cybersecurity is vital for safeguarding data, preserving trust, maintaining operations, protecting nations, and addressing global cyber threats.

## 3. Types of Cybersecurity : 
![image](https://github.com/nattycoder/GDSC-ENETCOM-CYBERSECURITY-DEPARTMENT/assets/88007154/f88cf641-6c4c-4652-8695-8db190f7feba)
* ### Network Security:
  Protects computer networks from unauthorized access, data breaches, and cyberattacks. It includes technologies like firewalls, intrusion detection systems, and VPNs.
* ### Endpoint Security:
  Focuses on securing individual devices (endpoints) such as computers, smartphones, and tablets. It includes antivirus software and endpoint protection tools.
* ### Cloud Security:
  Ensures the security of data, applications, and services hosted in cloud environments. It involves access controls, encryption, and secure configurations.
* ### Application Security:
  Protects software applications and code from vulnerabilities and threats. It includes secure coding practices, penetration testing, and web application firewalls.
* ### Identity and Access Management (IAM):
  Manages user access to systems and data, preventing unauthorized access. It employs techniques like multi-factor authentication and access controls.
* ### Data Security:
  Safeguards data from unauthorized access, disclosure, or alteration. It involves encryption, data loss prevention, and secure data storage methods.
  
And a lot more...

# Cyberattacks and Threats
## 1. Introduction to Cyberattacks
Cyberattacks are harmful actions that hackers take to break into computer systems, steal information, or disrupt digital operations.
![622b1df712adfa4ebff027a5_types of cyber attack](https://github.com/nattycoder/GDSC-ENETCOM-CYBERSECURITY-DEPARTMENT/assets/88007154/54207ae5-e979-4669-b45e-b895b6337a2d)

## 2. Common Cyberattacks types
* ### Malware:
  Malicious software, such as viruses, worms, Trojans, and ransomware, infects systems and can damage, steal, or encrypt data.
* ### Phishing:
  Deceptive emails or messages that trick individuals into revealing sensitive information like passwords or credit card numbers.
* ### Denial-of-Service (DoS) Attack:
  Overwhelming a system, network, or website with excessive traffic to make it unavailable to legitimate users.
* ### Ransomware:
  Encrypting files or systems and demanding a ransom for their release.
* ### Social Engineering:
  Manipulating people through psychological tactics to gain access to confidential information or systems.
  
And a lot more...

## 3. Malware
Malware is harmful software designed to damage or compromise computers, devices, or networks. It includes viruses, worms, and other malicious programs.
![flag_logo](https://github.com/nattycoder/GDSC-ENETCOM-CYBERSECURITY-DEPARTMENT/assets/88007154/922e1762-4011-467b-83c4-430baa098b54)

# Capture The Flag (CTF)
## 1. Introduction to Capture The Flag (CTF)
A Capture The Flag (CTF) competition is like a cybersecurity game. Participants solve puzzles and find hidden information, called "flags," to earn points. These challenges test their cybersecurity skills, and the goal is to collect as many flags as possible within a time limit. It's a fun way to learn and practice cybersecurity.
https://github.com/nattycoder/GDSC-ENETCOM-CYBERSECURITY-DEPARTMENT/issues/1#issue-1932043853
## 2. Jeopardy-Style CTF
* ### Challenges:
  In Jeopardy-style CTFs, challenges are categorized based on different aspects of cybersecurity, such as cryptography, web security, reverse engineering, and more.
* ### Points:
  Each challenge has a point value based on its difficulty. Solving a challenge earns you the associated points.
* ### Solve Independently:
  Participants can choose which challenges to attempt and can work on them independently or as a team.
* ### Flag Submission:
  When a participant solves a challenge, they find a "flag," which is a specific piece of information or code unique to that challenge. They submit this flag to earn points.
* ### Winning:
  The participant or team with the most points at the end of the competition wins.

## 3. Attack-Defend Style CTF
* ### Teams:
  Attack-Defend-style CTFs involve teams of participants. Each team is given a networked environment to defend and is tasked with attacking the environments of other teams.
* ### Roles:
  Teams have both "attackers" and "defenders." Attackers try to exploit vulnerabilities in other teams' systems, while defenders work to secure and protect their own systems.
* ### Scoring:
  Points are awarded for successful attacks (by the attackers) and for successfully defending against attacks (by the defenders).
* ### Real-Time:
  These competitions typically run in real-time, and teams must constantly monitor and adapt to the changing security landscape.
* ### Winning:
  The team that accumulates the most points, either through successful attacks or defense, wins the competition.

# Interactive Activities
## 1. Hands-On CTF Demonstration
### Steganography Challenge
In the context of Capture The Flag (CTF) challenges, #### steganography refers to the practice of hiding information, messages, or data within other files or media in a way that is not immediately apparent to the casual observer. The goal of steganography challenges in CTFs is to uncover or extract hidden information.

Here's how steganography works in CTFs:
* ### Hiding Data:
  A piece of information, often referred to as a "flag" in CTFs, is concealed within another file or medium. Common cover files include images (JPEG, PNG), audio files (MP3), or even text documents.
* ### Extraction:
  Participants are presented with the cover file, which contains the hidden data. Their task is to extract the hidden information using steganography techniques.
* ### Flag:
  The extracted information is often in the form of a flag, which typically follows a specific format like #### "CTF{flag_text_here}." Participants must identify and submit this flag to complete the challenge.

### Our Challenge
* #### Understand the Challenge:
  embed a flag within a file of your choice (in our case it's a .jpg image)

* #### Install Steghide:
  go under root: type "sudo su" then type "parrot"
  install the tool, type "apt-get install steghide"

* #### Use steghide
  create a new folder under /Desktop directory, type "cd Desktop && mkdir Challenge" then type "cd Challenge" (if you're already under a directory just type "cd" and do what's mentioned) 
  download an image of your choice and move it to that folder ("Challenge" in our case)
  use the tool, type "steghide embed -ef file.txt -cf image.jpg" (name the file the way you want, and the name of image that you downloaded)

* #### Passwords and Passphrases
  to add a password or passphrase, add this to the command before executing it "-p password" (use whatever password you want)

* #### Verify the Flag
  extract the flag, type "steghide extract -sf image.jpg -xf file.txt" (name the file the way you want, and the name of the image that you embedded the flag into)
  add "-p password" if you used a password
