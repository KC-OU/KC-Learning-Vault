# TryHackMe - Junior Penetration Tester (PT1) and SOC01

> [!infobox| wikipedia]+
> # TryHackMe - Junior Penetration Tester (PT1) and SOC1 
> ![[sec0-card.e59fca49.png|cover hsmall]]
> # Recommended Learning
> # **Start your learning here**
> | Name | Difficulty | Path or Room |
> | ------ | -------- |----------------|
> |  [Pre Security](##Pre%20Security) | Easy | Path |
> | Cyber Security 101 | Easy | Path |
> | Jr Penetration Tester | Intermediate | Path |
> | Web	Fundamentals | Easy | Path |
> | Windows Privilege Escalastion | Medium | Room |
> | Linux Privilege Escalastion | Medium | Room |
> | Lateral Movement and Pivoting | Easy | Room |
> |Credentials Harvesting | Medium| Room |
> |Exploit Vulnerabilites | Easy | Room |
> |Writting Pentest Reports | Easy | Room |
> | AD: Basic Enumeration | Easy | Room |
> |  AD: Authenticated Enumeration | Medium | Room |

> [!infobox| wikipedia]+
> ![[thm-pt1.png|cover hsmall]]
>## **Practice - Practice your skills**
> | Name | Difficulty | Path or Room |
> | ------ | -------- |----------------|
> |  Blue  | Easy | Room |
> |  Net Sec Challenge | Medium | Room |
> |  Pickle Rick  | Easy | Room |
> |  Reset | Hard | Room |
> |  Ledger | Hard | Room |
> |  Billing | Easy | Room |
> |  Rabbit Store | Medium | Room |
> |  K2  | Hard | Room |
> |  Stealth  | Medium | Room |
> |  Silver Platter  | Easy | Room |
> |  Lockback  | Easy | Room |
> |  AVenger | Medium | Room |

# Introduction
The **TryHackMe Junior Penetration Tester** pathway is an immersive, hands-on learning track designed to bridge the gap between foundational cybersecurity knowledge and practical, real-world ethical hacking skills. Tailored for aspiring security professionals, this pathway serves as an accessible yet comprehensive stepping stone into the world of offensive security.

At its core, the Junior Penetration Tester track focuses on equipping learners with the methodology and technical skills required to assess and secure modern digital environments. It assumes a basic understanding of networking, command-line interfaces (Linux/Windows), and web fundamentals, allowing it to dive straight into core penetration testing concepts.

The curriculum is divided into several expertly crafted modules, covering critical areas such as:

- **Web Application Security:** Understanding the OWASP Top 10, exploiting common web vulnerabilities (like SQL Injection, XSS, and Command Injection), and mastering essential proxy tools like Burp Suite.
    
- **Network Security:** Learning how to map networks, enumerate active services using tools like Nmap, and exploit network-based vulnerabilities.
    
- **Exploitation Frameworks:** Gaining hands-on experience with industry-standard tools like Metasploit to discover and exploit vulnerable software.
    
- **Privilege Escalation:** Discovering how to elevate access rights on both Windows and Linux systems post-compromise to gain administrative control.
    

What sets this pathway apart is TryHackMe’s interactive, browser-based learning environment. Instead of passively reading theory, you actively deploy virtual machines and practice exploits in a safe, legal, and gamified setting.

Ultimately, the Junior Penetration Tester pathway is the perfect launchpad. It prepares you for entry-level offensive security roles, builds a rock-solid foundation for practical industry certifications (such as the CompTIA PenTest+ or eJPT), and provides a clear, guided roadmap to launching a successful career as an ethical hacker.

---
>[!quote|author] Mathias Detmers - Security Analyst
> PT1 is a well-designed certification that truly tests your thoroughness and methodology. The AppSec section stood out as my favourited, demanding patience, precision, and a structured approach. If you're looking for a hands-on exam that reflects real-world scenarios, PT1 delivers.


## Pre Security

This course is related to the THM-SEC0 and THM-SEC01 Professional Certification and to the PT1 Certification. 

> [!column|list 2 ] Categories
> - [**Introduction to Cyber Security**](##Introduction%20to%20Cyber%20Security)
>     - [Offensive Security Intro](###Offensive%20Security%20Intro)
>     - Defensive Security Intro
>     - Careers in Cyber
>     - Topic Transition Recap
> - **Network Fundamentals**
>     - What is Networking 
>     - Intro to Lan
>     - OSI Model
>     - Packets and Frames
>     - Extending your Network
>     - Topic Transition Recap
> - **How the web works**
> 	- DNS in Detail
> 	- HTTP in Detail
> 	- How Websites work
> 	- Putting it all together
> 	- Topic Rewind Recap
> - **Computer Fundamentals**
>    - Inside a Computer System
>    - Computer Types
>    - Client-Server Basics
>    - Virtulisations Basics
>    - Cloud Computing Fundamentals
>    - Topic Rewind Recap
> - **Operating Systems Basics**
> 	- Operating System: Introduction
> 	- Windows Basics
> 	- Linux Cli Basics
> 	- Operating System Security
> 	- Topic Rewind Recap
> - **Software Basics**
> 	- Data Representation
> 	- Data Encoding
> 	- Python: Simple Demo
> 	- JavaScript: Simple Demo
> 	- Database SQL Basics
> 	- Topic Rewind Recap
> - **Attacks and Defenses**
> 	- The CIA Triad
> 	- Cryptography Concepts
> 	- Become  a Hacker
> 	- Become a Defender
> 	- Topic Rewind Recap

---

## Introduction to Cyber Security
Understand what is offensive and defensive security, and learn about careers available in cyber.

Explore both offensive and defensive security. Start by learning basic offensive security concepts, where you will hack a vulnerable online-banking application. Get exposure to defensive security and protect a system by blocking an ongoing cyber attack. In this module, you will also learn about the different careers within cyber security.

### Offensive Security Intro
#### Task 1 - What is Offensive Security?
Hack your first website (legally in a safe environment) and experience an ethical hacker's job.

"To outsmart a hacker, you need to think like one."

This is the core of "Offensive Security." It involves breaking into computer systems, exploiting software bugs, and finding loopholes in applications to gain unauthorized access. The goal is to understand hacker tactics and enhance our system defences.

Beginning Your Learning Journey

In this TryHackMe lesson, you will be guided through hacking your first website in a legal and safe environment. The goal is to show you how an ethical hacker operates.

#### Task 2 - Hacking my First Machine?

> [!warning] 
> This page does not contain the room's practical tasks, due to limited capability. If you would need to see the rooms, please see this link [Room Task](https://tryhackme.com/room/offensivesecurityintro?taskNo=2&sharerId=63680c95dda7750062b89afe)

#### Task 3- Careers in Cyber Security?

How can I start learning?

People often wonder how others become hackers (security consultants) or defenders (security analysts fighting cybercrime), and the answer is simple. Break it down, learn an area of cyber security you're interested in, and regularly practice using hands-on exercises. Build a habit of learning a little bit each day on TryHackMe, and you'll acquire the knowledge to get your first job in the industry.

Trust us; you can do it! Just take a look at some people who have used TryHackMe to get their first security job:

- Paul went from a construction worker to a security engineer. [Read more](https://tryhackme.com/r/resources/blog/construction-worker-to-security-engineer-how-paul-used-tryhackme-to-land-his-first-job-in-security
- Kassandra went from a music teacher to a security professional. [Read more](https://tryhackme.com/r/resources/blog/the-teacher-becomes-the-student)
- Brandon used TryHackMe while at school to get his first job in cyber. [Read more](https://tryhackme.com/r/resources/blog/brandons-success-story)

What careers are there?

The cyber careers lesson goes into more depth about the different careers in cyber. However, here is a short description of a few offensive security roles:

- Penetration Tester - Responsible for testing technology products for finding exploitable security vulnerabilities.
- Red Teamer - Plays the role of an adversary, attacking an organization and providing feedback from an enemy's perspective.
- Security Engineer - Design, monitor, and maintain security controls, networks, and systems to help prevent cyberattacks.


