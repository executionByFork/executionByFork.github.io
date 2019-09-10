---
layout: default
---

## My Achievements

|   |   |
|:-----:|-----|
| ![Cert](./assets/images/certificate20px.png)  | [Bachelors in Computer Science](./assets/degree.jpg) from the University of Missouri Columbia  |
| ![Cert](./assets/images/certificate20px.png)  | [CompTIA Security+ Certified](./assets/Security_Plus_Cert.pdf)  |
| ![silver](./assets/images/silverMedal20px.png)  | 2nd place in the [SEC National Cyber Security Competition](https://engineering.missouri.edu/2018/04/mizzou-showcases-cyber-security-strength-at-sec-academic-conference/) at Auburn University  |
| ![star](./assets/images/gold_star20px.png)  |  [7th place](https://web.archive.org/web/20190223210500/https://mitrestemctf.org/teams/1592/summary) out of 129 undergraduate teams in the [MITRE STEM CTF](https://web.archive.org/web/20190319062530/https://mitrestemctf.org/game/teams#division-5-tab) ([Cert](./assets/MITRE_Competition_Certificate.pdf))<br>&nbsp;&nbsp;&nbsp;(14th/539 in the college bracket, 45th/1,190 overall)  |
| ![star](./assets/images/gold_star20px.png) | Participated in the 2019 CCDC State Qualifiers ([team photo](./assets/images/CCDC2019team.png)) |
| ![gold](./assets/images/goldMedal20px.png)  | 1st place in the Mizzou 2016 Engineering FIG Olympics  |

## My Hacker Accounts
The following is a list of accounts I have on various CTF challenge sites. These websites provide puzzles and challenges for users to test their hacking skills, and upon completion you are awarded points, which get displayed on your profile. Through these services, I've developed practical skills and learned techniques that I can apply to other tasks and projects. CTF challenges have given me hands on practice and taught me a lot about Cyber Security and it's various subtopics.
- [Root-me](https://www.root-me.org/executionbyfork?inc=statistiques&lang=en)
- [HackTheBox](https://www.hackthebox.eu/profile/47787)
- [HackThisSite](https://www.hackthissite.org/user/view/executionByFork/) - Will complain about a bad referrer. Click the URL box, and hit enter.
- [RingZer0Team](https://ringzer0ctf.com/profile/24017/ExecutionByFork)

## My Projects

### [LP_ThreatModeling](https://github.com/tleachman1234/LP_ThreatModeling)
_This project is a threat modeling methodology created by me and another intern during my 2018 summer internship. This methodology is based off of several other common threat modeling methodologies used in the industry, and we tried to take the best things from each of them to create a streamlined, practical method of assessing threats in any application. This methodology is currently being used at the company I interned at, and by using our threat model they have found and patched several critical vulnerabilities in their systems. This repository contains templates, slides, examples, and instructions to make it easy to learn and begin using our methodology._

### [PhishermanFlood](https://github.com/tleachman1234/BaitPhish)
_This is a scripting library meant to make it easy to write a script that floods a website with fake user data. I originally created this as a one off script when a phishing scam was sent to my university inbox. The person was trying to get Mizzou student login information and I decided to make things difficult for them. Since then, I've adapted the script into a library of sorts, which can be pulled into any script._

_The intention of this tool is to fill the logs of Phishers with so much fake data that the real data gets lost in the sea. Most of the functions provided generate various forms of fake, but realistic looking data. There are also currently several functions used to get information from a webpage or send data in a post request, and they have an option to enable or disable routing the traffic over TOR. By integrating TOR into this tool, it creates assurance that the phishers can't log your IP address with the data they are collecting, and dump all the data from one IP. It also prevents the blacklisting of your IP to stop the flood of fake information. In the future I plan to add more library functions, and support threading._

### [JokenetCTF](https://github.com/tleachman1234/JokenetCTF)
_This is a CTF challenge website I wrote Junior year of college. There are ten total vulnerabilites/flaws in "Jokenet" that give you a flag upon finding them, which you turn in for points. Nine of these flags have hints, and there is one easter egg flag. The challenges range from easy to slightly difficult. The CTF site even comes with a leaderboard!_

_The main section of the site was created starting with a CSS template, while the Jokenet portion of the site was coded from scratch by me, and intentionally made to look amateur and vulnerable. If you would like to take a look or even try out some of the challenges, there is a live demo hosted on Heroku [here](https://jokenet.herokuapp.com)_

### [privilegeEscalation](https://github.com/tleachman1234/privilegeEscalation)
_This repository is a group of example programs that are vulnerable to privilege escalation. In other words, a normal user can upgrade themselves to a superuser if these programs are compiled into binaries that are owned by a superuser, and have their `setuid` bit set. I created these examples for my CyberSecurity SIG as challenges for the other students to try and solve. Overall they are good examples as to why the `setuid` and `setgid` bits are so dangerous, and why certain programming practices are frowned upon._

### [Cyber Security SIG Slides](https://drive.google.com/open?id=0BwzZDYyka2urMTJMTnBnd0JHS2s)
_This Google Drive folder houses all of the slides I have made during my time as the leader of [MCA](http://mca.missouri.edu/)'s Cyber Security Special Interest Group (SIG). As a SIG leader, you hold meetings once a week about a specific topic. During my two years as the CyberSec SIG leader, I created numerous slides to supplement my lectures on various intro and medium level topics in security. In addition to these slides, during some weeks we would have interactive challenges for students to try their hand at, and I also organized a few trips to different security conferences._

### [AudioVisualizer](https://github.com/tleachman1234/AudioVisualizer)
_This is a small Java application I created in my Object Oriented Languages class Sophomore year. I coded it using NetBeans IDE. The app is rendered using JavaFXML and allows you to play audio or video files, to which the bars dance like any audiovisualizer app would. I found this to be a cool project, and so I went beyond the course requirements to add options (like choosing the number of bars), and three separate themes in total. The program dynamically reads the audio data and maps it to the UI bars as the media plays._
