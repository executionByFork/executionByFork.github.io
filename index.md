---
layout: default
---

## Education
### University of Missouri – Columbia  (Core GPA 3.53 | Overall GPA 3.04)  
- Graduated May 2019 - [Bachelors in Computer Science](./assets/degree.jpg) (Cyber Security emphasis)  

## Achievements

|   |   |
|:-----:|-----|
| ![Cert](./assets/images/certificate20px.png)  | [GIAC Certified Forensic Analyst](./assets/GIAC_Cert.jpg)  |
| ![Cert](./assets/images/certificate20px.png)  | [CompTIA Security+ Certified](./assets/Security_Plus_Cert.pdf)  |
| ![silver](./assets/images/silverMedal20px.png)  | 2nd place in the [SEC National Cyber Security Competition](https://engineering.missouri.edu/2018/04/mizzou-showcases-cyber-security-strength-at-sec-academic-conference/) at Auburn University  |
| ![star](./assets/images/gold_star20px.png)  |  [7th place](https://web.archive.org/web/20190223210500/https://mitrestemctf.org/teams/1592/summary) out of 129 undergraduate teams in the [MITRE STEM CTF](https://web.archive.org/web/20190319062530/https://mitrestemctf.org/game/teams#division-5-tab) ([Cert](./assets/MITRE_Competition_Certificate.pdf))<br>&nbsp;&nbsp;&nbsp;(14th/539 in the college bracket, 45th/1,190 overall)  |
| ![star](./assets/images/gold_star20px.png) | Participated in the 2019 CCDC State Qualifiers ([team photo](./assets/images/CCDC2019team.png)) |
| ![gold](./assets/images/goldMedal20px.png)  | 1st place in the Mizzou 2016 Engineering FIG Olympics  |

____
<br>
## Work Experience

### Protiviti | _Senior Security Consultant_ | July 2019 - Present
I have worked on a large variety of projects at Protiviti, primarily in the Technology, Healthcare, and Banking industries. During these projects, I have assessed client security postures through hands on security testing, application source code reviews, and threat modeling application designs. Over the course of my career as a security and privacy consultant, I have executed multiple penetration tests against web applications, internal client networks, and client's externally facing services. I have used numerous tools, both commercial and open source, as well as written custom scripts and programs for exploitation. Aside from hands on testing, I have gained further experience with threat modeling during a long running client engagement. My job here was to consult with development teams to review and assess new or changed functionality to various applications, create threat modeling diagrams, and give guidance on how best to secure said features.  
<br>
### World Wide Technology Asynchrony Labs | _Application Security Intern_ | May 2018 - August 2018
At Asynchrony Labs, I was responsible for developing an extensible threat modeling methodology (see [LP_ThreatModeling](https://executionbyfork.github.io/#lp_threatmodeling)) tailored to the company’s needs, that could be applied to a wide assortment of applications. I applied this threat model to their internal applications, and conducted vulnerability assessments on the apps and the associated infrastructure. During this process I found multiple vulnerabilities, and demonstrated how they could be exploited by writing proof of concept scripts before presenting them to the developers. I submitted pull requests to patch a number of these vulnerabilities myself, and informed the appropriate teams of those that remained. The threat modeling methodology I developed for Asynchrony is now applied to each of their applications during the development process, and has helped the teams to uncover and locate various security related issues in their projects.  
<br>
### Exegy | _Developer Intern_ | May 2016 - August 2016 & May 2017 - August 2017
During my Freshman internship, I built and stood up a web application to act as a central information resource for Exegy’s infrastructure. I coded the front end webapp using the ReactJS framework, while the server ran Python. Flask routing and the SQLAlchemy libraries were utilized for communication with the client and database respectively, using RESTful techniques. This application has helped to increase productivity for Exegy’s developers by providing a central location for them to gather information about servers and resources.  
For my second internship with Exegy, I set up a dependency management system using an open source package manager called Conan. I wrote cross platform python scripts to automate compiling and testing for several of their applications on both Windows and Linux architectures. My work has made testing for stability across platforms a simpler task, and has abstracted away the difficulty of managing project dependencies in multiple environments.  

____
<br>
## Projects

### [MCC Mod Manager](https://github.com/executionByFork/MCC_Mod_Manager)
_This is a simple mod manager for Halo Master Chief Collection which I wrote from scratch in C#. I decided to create this application because at the time when MCC was released to PC, there was no good solution available for installing/uninstalling the many mods that were being released. My goal for this project was to create an easy to use tool for managing halo mods for all users (including the technically unsavvy), so I decided to go with a GUI application. I've made it as lightweight as possible, and although there are still a number of things I would like to update when I find time, the tool works really well. It even implements patch files created with the Blamite library from Assembly, a popular tool for halo modding which a majority of modders use to create mods. This allows for smaller storage use, as mods can be stored as patch files instead of entire file copies._

### [LP_ThreatModeling](https://github.com/tleachman1234/LP_ThreatModeling)
_This project is a threat modeling methodology created by myself and another intern during my 2018 summer internship. This methodology is based off of several common threat modeling methodologies used in the industry. We took the best things from each of them to create a streamlined, practical method of assessing threats in any application. This methodology is currently in use at the company I interned at. By using our threat modeling system, we helped find and patch several critical vulnerabilities in the corporate systems and applications. This repository contains templates, slides, examples, and instructions to make it easy to learn and begin using our methodology._

### [BaitPhish](https://github.com/tleachman1234/BaitPhish)
_This is a scripting library meant to make it easy to write a script that floods a website with fake user data. I originally created this as a one off script when a phishing scam was sent to my university inbox. The person was trying to get Mizzou student login information and I decided to make things difficult for them. Since then, I've adapted the script into a library of sorts, which can be pulled into any script._

_The intention of this tool is to muck up the logs of Phishers with so much fake data that the real stuff gets obscured and lost. Most of the functions provided generate various forms of fake, but realistic looking data. There are also currently several functions used to get information from a webpage or send data in a post request, and they have an option to enable or disable routing the traffic over TOR. By integrating TOR into this tool, it creates assurance that the phishers can't log your IP address with the data they are collecting, and throw out all the data from one IP. It also prevents the blacklisting of your IP to stop the flood of fake information. In the future I plan to add more library functions, and support threading._

### [JokenetCTF](https://github.com/tleachman1234/JokenetCTF)
_This is a CTF challenge website I wrote Junior year of college. There are ten total vulnerabilites/flaws in "Jokenet" that give you a flag upon finding them, which you turn in for points. Nine of these flags have hints, and there is one easter egg flag. The challenges range from easy to slightly difficult. The CTF site even comes with a leaderboard!_

_The main section of the site was created starting with a CSS template, while the Jokenet portion of the site was coded from scratch by me, and intentionally made to look amateur and vulnerable. If you would like to take a look or even try out some of the challenges, there is a live demo hosted on Heroku [here](https://jokenet.herokuapp.com)_

### [privilegeEscalation](https://github.com/tleachman1234/privilegeEscalation)
_This repository is a group of example programs that are vulnerable to privilege escalation. In other words, a normal user can upgrade themselves to a superuser if these programs are compiled into binaries that are owned by a superuser, and have their `setuid` bit set. I created these examples for my CyberSecurity SIG as challenges for the other students to try and solve. Overall they are good examples as to why the `setuid` and `setgid` bits are so dangerous, and why certain programming practices are frowned upon._

### [Cyber Security SIG Slides](https://drive.google.com/open?id=0BwzZDYyka2urMTJMTnBnd0JHS2s)
_This Google Drive folder houses all of the slides I have made during my time as the leader of [MCA](http://mca.missouri.edu/)'s Cyber Security Special Interest Group (SIG). As a SIG leader, you hold meetings once a week about a specific topic. During my two years as the CyberSec SIG leader, I created numerous slides to supplement my lectures on various intro and medium level topics in security. In addition to these slides, during some weeks we would have interactive challenges for students to try their hand at, and I also organized a few trips to different security conferences._


## Hacker/Challenge sites
The following is a list of accounts I have on various CTF challenge sites. These websites provide puzzles and challenges for users to test their hacking skills, and upon completion you are awarded points, which get displayed on your profile. Through these services, I've developed practical skills and learned techniques that I can apply to other tasks and projects. CTF challenges have given me hands on practice and taught me a lot about Cyber Security and it's various subtopics.
- [Root-me](https://www.root-me.org/executionbyfork?inc=statistiques&lang=en)
- [HackTheBox](https://www.hackthebox.eu/profile/47787)
- [HackThisSite](https://www.hackthissite.org/user/view/executionByFork/) - Will complain about a bad referrer. Click the URL box, and hit enter.
- [WeChall](https://www.wechall.net/profile/executionByFork)
